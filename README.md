
# Android Security Toolkit
## Overview

The Android Security Toolkit is a bash script designed to assist in various security testing activities on Android devices. It provides a convenient interface for tasks such as extracting APKs, decompiling APKs, running activities, and identifying potential security vulnerabilities. The toolkit is particularly useful for security researchers, penetration testers, and developers concerned with Android app security.


## Features

- Connect to Android Device: Easily connect to an Android device using its IP address and port.
- View Package Information: Display all package names installed on the connected Android device.
- Show Installed App Packages: List installed app packages on the connected Android device.
- Extract APK: Extract the APK file of a specified package from the connected Android device.
- Decompile APK (JADX): Decompile an APK file using JADX, a tool for reverse engineering Android applications.
- Decompile APK (Apktool): Decompile an APK file using Apktool, a versatile tool for decompiling and rebuilding Android applications.
- Run Activity: Launch an activity on the connected Android device.
- Show Exploitable Activity: Identify potentially exploitable activities within APK files.
- Webview Exploit: Launch a webview activity with specified parameters, potentially useful for testing web vulnerabilities.


## Installation

```bash
  git clone https://github.com/nahid0x1/android-security-toolkit
```
```bash
  cd android-security-toolkit
```
```bash
  sudo bash androkit.sh --install
```

## Requirement Installation
For MacOS
```bash
  androkit --install-mac
```
For Linux Distribution
```bash
  androkit --install-linux
```

## Connect Android Device
```bash
  androkit <IP>:<PORT>
```


## Interface

```
⣿⣿⣿⣿⣿⣿⣧⠻⣿⣿⠿⠿⠿⢿⣿⠟⣼⣿⣿⣿⣿⣿⣿ v3.0
⣿⣿⣿⣿⣿⣿⠟⠃⠁⠀⠀⠀⠀⠀⠀⠘⠻⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡿⠃⠀⣴⡄⠀⠀⠀⠀⠀⣴⡆⠀⠘⢿⣿⣿⣿⣿
⣿⣿⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⣿⣿⣿
⣿⠿⢿⣿⠶⠶⠶⠶⠶⠶⠶⠶⠶⠶⠶⠶⠶⠶⠶⣿⡿⠿⣿  @nahid0x1
⡇⠀⠀⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⢸
⡇⠀⠀⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⢸
⡇⠀⠀⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⢸
⡇⠀⠀⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⢸
⣧⣤⣤⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣤⣤⣼
⣿⣿⣿⣿⣶⣤⡄⠀⠀⠀⣤⣤⣤⠀⠀⠀⢠⣤⣴⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⣿⣿⣿⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣤⣤⣴⣿⣿⣿⣦⣤⣤⣾⣿⣿⣿⣿⣿⣿

Selected Android [Galaxy S4]

01. All Packages Names             10. Setup Frida-Server To Android
02. Show Installed App Packages    11. Start Frida-Server [Android]
03. Extract APK                    12. SSL Pinning Bypass [Frida]
04. Decompile APK [JADX]
05. Decompile APK [Apktool]
06. Run Activity
07. Show Exploitable Activity
08. Webview Exploit
09. Install APK To Android

(connect)      (disconnect)
(devices)      (root)

Install requirement for:
$> Mac
$> Linux

[Galaxy S4] Console>

```



## Compatibility

The Android Security Toolkit is compatible with both Linux and macOS operating systems. It relies on standard bash scripting and commonly used tools for Android security testing.


## Disclaimer

This toolkit is intended for educational and security testing purposes only. It should be used responsibly and with appropriate permissions. The authors and contributors of this toolkit are not responsible for any misuse or damage caused by its usage. Always ensure that you have proper authorization before conducting security testing on any device or application.


## Author

- [@nahid0x1](https://www.linkedin.com/in/nahid0x1)

