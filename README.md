# Bug reproduction
## Show a modale above a navigation sheet
* To reproduce just launch ai generator cookbook and tap "Open modal" button
* Error
 ```
════════ Exception caught by rendering library ═════════════════════════════════
The sheet extent and the dimensions values must be finalized during the layout phase.
'package:smooth_sheets/src/foundation/framework.dart':
Failed assertion: line 125 pos 7: '_extent.hasPixels'
```
* Behavior on Andorid 14 emulator (same on Android 14 real device and Android 11 emulator)
  [bug_modal.webm](https://github.com/QuentinSc/qsc_smooth_sheets/assets/16439299/7ea3d42e-2438-4f96-b721-25cfe101c67e)



package/README.md
