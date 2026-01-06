# 负一屏定制

## 设备信息

联发科 Android15

## 桌面入门
- 桌面信息
  adb shell "dumpsys activity activities | grep Resume"

* daemon not running; starting now at tcp:5037
* daemon started successfully
  topResumedActivity=ActivityRecord{ed960c7 u0
  com.android.launcher3/com.android.searchlauncher.SearchLauncher t19}
  state=RESUMED delayedResume=false finishing=false
  Resumed activities in task display areas (from top to bottom):
  Resumed: ActivityRecord{ed960c7 u0 com.android.launcher3/com.android.searchlauncher.SearchLauncher
  t19}
  ResumedActivity: ActivityRecord{ed960c7 u0
  com.android.launcher3/com.android.searchlauncher.SearchLauncher t19}

- 负一屏界面信息
  adb shell "dumpsys activity activities | grep Resume"
  topResumedActivity=ActivityRecord{ed960c7 u0
  com.android.launcher3/com.android.searchlauncher.SearchLauncher t19}
  state=RESUMED delayedResume=false finishing=false
  Resumed activities in task display areas (from top to bottom):
  Resumed: ActivityRecord{ed960c7 u0 com.android.launcher3/com.android.searchlauncher.SearchLauncher
  t19}
  ResumedActivity: ActivityRecord{ed960c7 u0
  com.android.launcher3/com.android.searchlauncher.SearchLauncher t19}

- 负一屏UIView信息
  包名: com.google.android.googlequicksearchbox