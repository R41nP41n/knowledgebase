# Android Pentesting

Notes from hands-on Android pentesting work.

## Pages

| # | Topic | Description |
|---|-------|-------------|
| 00 | [Setup](./00_setup.md) | Lab environment, tools, emulator config |
| 01 | [Recon](./01_recon.md) | APK info gathering, manifest analysis |
| 02 | [Static Analysis](./02_static_analysis.md) | JADX, Apktool, reading decompiled code |
| 03 | [Dynamic Analysis](./03_dynamic_analysis.md) | Frida, Objection, runtime hooks |
| 04 | [Traffic Interception](./04_traffic_interception.md) | Burp setup, SSL pinning bypass |
| 05 | [Auth & Storage](./05_auth_and_storage.md) | Auth bugs, insecure data storage |
| 06 | [Vulnerabilities](./06_vulnerabilities.md) | Vuln types reference |
| 07 | [Reporting](./07_reporting.md) | Writing up findings |
| — | [Resources](./resources.md) | External links & cheatsheets |

## Current Lab Target

- **APK:** `[app name here]`
- **Scope:** Full app — auth, storage, traffic, API
- **Status:** In progress

## Knowledge Checklist

- [ ] Understand Android manifest structure
- [ ] Can decompile APKs with JADX and navigate source
- [ ] Know what SSL pinning is and how to bypass with Frida
- [ ] Can intercept traffic with Burp on a real/emulated device
- [ ] Understand common Android vuln classes (OWASP MAS)
