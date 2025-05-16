Here’s your updated **GitHub README** with the new links properly organized:

---

# Learn Android Bug Bounty

A curated collection of learning resources to get started with Android application security, mobile app pentesting, and bug bounty hunting. This repository includes video tutorials, blog posts, hands-on labs, and practice materials for both Android and iOS platforms.

---

## 🎥 Video Tutorials

* [Mobile Pentesting by Hackersploit](https://www.youtube.com/playlist?list=PLmqenIp2RQcjBWzwMZQbIkbuVDmkYi_KF)
* [Android Bug Bounty Playlist](https://www.youtube.com/playlist?list=PL1f72Oxv5SylOECx9M34pLZlNa7YkJJ14)
* [How to Hack Android Apps (Frida)](https://www.youtube.com/watch?v=mr64si_-YwI)
* [How to Bypass SSL Pinning](https://www.youtube.com/watch?v=vjCF_O6aZIg)
* [How to Root Android Emulator in 2 Minutes](https://www.youtube.com/watch?v=OLgmPxTHLuY)
* [Intercepting Android App Traffic with BurpSuite](https://www.youtube.com/watch?v=xp8ufidc514)
* [Mobile Application Pentesting](https://www.youtube.com/playlist?list=PLxlnw7Sfbtf9pBNKKQPJTSyI8KNHvgoMJ)
* [Finding Sensitive Data in Android Apps with Nerdwell](https://www.youtube.com/watch?v=D_-mHBkfThI)
* [Exploiting Android deep links and exported components](https://www.youtube.com/watch?v=lg1sN8njSYs)
* [Mobile App Pentesting by Hacking Simplified](https://www.youtube.com/playlist?list=PLGJe0xGh7cH2lszCZ7qwsqouEK23XCMGp)
* [Android Security Testing](https://www.youtube.com/watch?v=6-M_7O3A8AI)

---

## 📚 Guides & Cheatsheets

* [Android Pentesting Checklist (HackTricks)](https://book.hacktricks.wiki/en/mobile-pentesting/android-checklist.html)
* [Awesome Mobile CTF Resources](https://github.com/xtiankisutsa/awesome-mobile-CTF)
* [Mobile App Pentest Cheatsheet](https://github.com/tanprathan/MobileApp-Pentest-Cheatsheet#readme)
* [All Things Android Security](https://github.com/jdonsec/AllThingsAndroid)
* [Android Bug Bounty Reports & Resources](https://github.com/B3nac/Android-Reports-and-Resources)

---

## 🛠 Mobile Pentesting Tools & Techniques

* [Frida PDF Guide (Google Drive)](https://drive.google.com/file/d/1JccmMLi6YTnyRrp_rk6vzKrUX3oXK_Yw/view)
* [Frida script to bypass SSL pinning](https://gist.github.com/teknogeek/4dc35fb3801bd7f13e5f0da5b784c725)
* [HEXTREE.IO - Mobile Security Resources](https://www.hextree.io/)
* [APKLeaks - Extract secrets from APKs](https://github.com/dwisiswant0/apkleaks)

---

## 🔍 Bug Bounty POCs & Reports

* [HackerOne Report #583987](https://hackerone.com/reports/583987)
* [HackerOne Report #805073](https://hackerone.com/reports/805073)
* [HackerOne Report #637194](https://hackerone.com/reports/637194)
* [HackerOne Report #401793](https://hackerone.com/reports/401793)
* [HackerOne Report #258460](https://hackerone.com/reports/258460)
* [HackerOne Report #200427](https://hackerone.com/reports/200427)
* [HackerOne Report #351555](https://hackerone.com/reports/351555)
* [HackerOne Report #44727](https://hackerone.com/reports/44727)

---

## 🧪 Practice Resources

* [Android Java Challenges](https://application.security/free/%20Android-Java)
* [iPhone Swift Labs](https://application.security/free/marketing-iphone-swift)

---

## 🧬 Labs for Hands-On Learning

* [Mobile Hacking Lab](https://www.mobilehackinglab.com/free-mobile-hacking-labs)
* [Security Compass Android Labs](https://securitycompass.github.io/AndroidLabs/index.html)
* [Security Compass iPhone Labs](https://securitycompass.github.io/iPhoneLabs/)
* [OWASP iGoat (Android)](https://code.google.com/archive/p/owasp-igoat/)

---

## 🛠️ Security Tools

### Static Analysis Tools
1. [APKTool](https://ibotpeaches.github.io/Apktool/) – Decompile/modify APK (smali-level)
2. [Jadx](https://github.com/skylot/jadx) / JD-GUI – Convert DEX to readable Java code
3. [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) – Automated static + dynamic scanner
4. [Androguard](https://github.com/androguard/androguard) – Python tool for APK/DEX/smali analysis
5. [Bytecode Viewer](https://github.com/Konloch/bytecode-viewer) – Reverse engineering with multiple decompilers
6. [ClassyShark](https://github.com/google/android-classyshark) – Explore APK classes/methods/manifest
7. [QARK](https://github.com/linkedin/qark) – Detects security issues in APKs
8. [Enjarify](https://github.com/google/enjarify) / dex2jar – DEX to Java JAR conversion
9. [APKLeaks](https://github.com/dwisiswant0/apkleaks) – Extract secrets, tokens, and URLs

### Dynamic Analysis Tools
1. [Frida](https://frida.re/) – Hook/modify functions at runtime
2. [Objection](https://github.com/sensepost/objection) – Runtime exploitation via Frida (no root required)
3. [Xposed](https://repo.xposed.info/) / [LSPosed](https://github.com/LSPosed/LSPosed) – Framework for modifying app behavior
4. [Burp Suite](https://portswigger.net/burp) – Intercept/modify network traffic
5. [Drozer](https://labs.withsecure.com/tools/drozer) – Android app attack framework
6. [Magisk](https://github.com/topjohnwu/Magisk) – Systemless root; works with LSPosed modules
7. [ADB](https://developer.android.com/studio/command-line/adb) – Debugging bridge for Android device

### Logging Tools
1. Logcat – Default Android logging system (`adb logcat`)
2. [Pidcat](https://github.com/JakeWharton/pidcat) – Filtered Logcat output by package
3. [MatLog](https://github.com/plusCubed/matlog) – GUI log reader (useful for non-rooted devices)
4. XLog / Timber – In-app logging libraries used in apps
5. Logd – Android logging daemon behind logcat
6. Syslog – For rooted devices to log everything (system + kernel)

---

## 💡 Contribution

Feel free to raise issues or submit PRs to add more Android bug bounty and mobile hacking resources.
