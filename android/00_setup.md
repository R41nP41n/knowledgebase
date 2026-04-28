# Lab Setup

## Tools

| Tool | Purpose | Install |
|------|---------|---------|
| ADB | Device communication | Android SDK Platform Tools |
| JADX | Decompile APK to Java | https://github.com/skylot/jadx |
| Apktool | Decode/rebuild APK | https://apktool.org |
| Frida | Dynamic instrumentation | `pip install frida-tools` |
| Objection | Frida-based runtime explorer | `pip install objection` |
| Burp Suite | Traffic interception | https://portswigger.net |

## Device Setup

- Android version: `[fill in]`
- Rooted: Yes / No
- Emulator or physical: `[fill in]`

## ADB Basics

```bash
adb devices              # list connected devices
adb shell               # open shell
adb install app.apk     # install APK
adb logcat              # view device logs
```

## Notes

- [add your setup notes here]
