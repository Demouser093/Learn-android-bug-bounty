### ✅ 1. **Create Emulator (GUI or CLI)**

#### GUI:

* Android Studio > **AVD Manager** > **Create Virtual Device**
* Choose: **Pixel 4**
* Select system image:
  `API 35` or `API 36` → **x86\_64 + Google APIs**
* Finish setup

---

### ✅ 2. **Start Emulator with writable system**

```bash
emulator -avd Pixel4-API35 -writable-system -no-snapshot -netdelay none -netspeed full
```

---

### ✅ 3. **Enable root + remount system**

```bash
adb root
adb remount
```

---

### ✅ 4. **Convert and Install Burp Certificate**

#### Convert `.der` to `.pem`:

```bash
openssl x509 -inform DER -in burp.der -out burp.pem
```

#### Get subject hash:

```bash
openssl x509 -inform PEM -subject_hash_old -in burp.pem | head -1
# Example: abcd1234
```

#### Rename and push to system:

```bash
mv burp.pem abcd1234.0
adb push abcd1234.0 /system/etc/security/cacerts/
adb shell chmod 644 /system/etc/security/cacerts/abcd1234.0
```

---

### ✅ 5. **Reboot Emulator**

```bash
adb reboot
```

---

### 🛡️ Optional: **SSL Pinning Bypass**

If the app still blocks HTTPS:

* Use Frida with:

  * `frida-android-unpinning`
  * `objection`
  * `disable-flutter-tls-v1` (for Flutter apps)

---

### ⚠️ Notes:

* Use **Google APIs image**, **not Play Store**.
* `adb root && remount` only works in emulator (not on physical device).
* This setup supports **ARM apps via translation** (if using `x86_64` + Google APIs image).
