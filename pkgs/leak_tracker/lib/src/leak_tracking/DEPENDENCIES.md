<!---
Generated by https://github.com/polina-c/layerlens
Dependencies that create loop are markes with `!`.
-->

```mermaid
flowchart TD;
_dispatcher.dart-->_object_tracker.dart;
_leak_checker.dart-->leak_tracker_model.dart;
_object_record.dart-->_gc_counter.dart;
_object_tracker.dart-->_gc_counter.dart;
_object_tracker.dart-->_object_record.dart;
_object_tracker.dart-->leak_tracker_model.dart;
_object_tracker.dart-->retaining_path;
leak_tracker.dart-->_dispatcher.dart;
leak_tracker.dart-->_leak_checker.dart;
leak_tracker.dart-->_object_tracker.dart;
leak_tracker.dart-->leak_tracker_model.dart;
orchestration.dart-->_gc_counter.dart;
orchestration.dart-->leak_tracker.dart;
orchestration.dart-->leak_tracker_model.dart;
```
