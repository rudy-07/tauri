---
"tauri-cli": patch:bug
"@tauri-apps/cli": patch:bug
---

Set `ndkPath` and `ndkVersion` from `NDK_HOME` in the Android app template so release native libraries are properly stripped by the Android Gradle Plugin.
