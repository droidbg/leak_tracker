<!---
Generated by https://github.com/polina-c/layerlens
Dependencies that create loops (inversions) are marked with `!`.
-->

```mermaid
flowchart TD;
_protocol.dart-->messages.dart;
_registration.dart-->delivery.dart;
_registration.dart-->messages.dart;
_registration.dart-->primitives.dart;
delivery.dart-->_protocol.dart;
delivery.dart-->primitives.dart;
```

### Inversions
In this folder: 0

Including sub-folders: 0

