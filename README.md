<p align="center">
  <img src="screenshots/logo.png" width="180">
</p>

<h1 align="center">🛡️ Visioncrypt</h1>

<p align="center">
Advanced Steganography & Data Sovereignty Vault
</p>

<p align="center">

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Language](https://img.shields.io/badge/Language-Kotlin-blue)
![UI](https://img.shields.io/badge/UI-Jetpack%20Compose-purple)
![Security](https://img.shields.io/badge/Focus-Security-red)
![Encryption](https://img.shields.io/badge/Encryption-AES--256-red)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-blue)
![Min Android](https://img.shields.io/badge/Min%20Android-8.0%20(Oreo)-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)
</p>

<p align="center">

<a href="https://github.com/CodingWorld-007/Visioncrypt-Application/releases/latest">
<img src="https://img.shields.io/badge/Download-APK-brightgreen?style=for-the-badge">
</a>

</p>

---

# 📥 Download

Download the latest APK from GitHub Releases.

🔗 https://github.com/CodingWorld-007/Visioncrypt-Application/releases/latest

---

# ✨ Features

• **Offline-First Encryption Engine**  
All cryptographic operations run locally on the device.

• **AES-256 GCM Encryption**  
Industry-standard authenticated encryption.

• **Multi-Channel RGB Steganography**  
Encrypted data is embedded across the Red, Green, and Blue pixel channels.

• **Firebase Authentication Gateway**  
User verification before vault access.

• **Zero Cloud Processing**  
Sensitive data never leaves the device.

• **Pixel-Level Data Embedding**  
Minimal visual distortion with maximum concealment.

---

# 🔐 Security Architecture

Visioncrypt encrypts data **before** embedding it inside an image.

```
User Data
   ↓
PBKDF2 Key Derivation
   ↓
AES-256 Encryption
   ↓
LSB Steganography
   ↓
PNG Carrier Image
```

Even if hidden data is extracted, it remains **cryptographically protected**.

---

# 📱 How to Use

## Introduction Screen

| Introduction |
|-------------|
| ![](screenshots/Intro.jpeg) |

---

# 🔏 Encode Data

1. Select a **carrier or sample image**
2. Enter your **secret message or file**
3. Enter a **password**
4. Encode the data and **export the generated PNG**

⚠ **Important**

Always send the encoded image as a **Document/File**.

Sending it as a **Photo** compresses the image and permanently destroys the hidden data.

---

| Encode Screen |
|---------------|
| ![](screenshots/Encode_screen_1.jpeg) |

| Encode Options |
|---------------|
| ![](screenshots/Encode_screen_2.jpeg) |

| Encryption Key |
|---------------|
| ![](screenshots/Encryption_Key.jpeg) |

---

# 🔓 Decode Data

1. Import the encoded PNG image  
2. Enter the **Encryption Key**  
3. Enter the **Password used during encoding**  
4. The hidden **message or file will be extracted**

| Decode Screen |
|---------------|
| ![](screenshots/Decode_screen.jpeg) |

---

# 🔐 Vault

The **Vault** stores:

• Saved encryption keys  
• Metadata related to encoded images  
• User encryption history  

| Vault Screen |
|---------------|
| ![](screenshots/vault.jpeg) |

---

# 🔒 Source Code Policy

Visioncrypt is **closed-source** to protect the cryptographic architecture and prevent reverse-engineering of the steganography engine.

Only **application binaries and documentation** are publicly distributed.

---

# 👨‍💻 Author

**Aman Joshi**

LinkedIn  
https://www.linkedin.com/in/amanajjoshi

---

# 📜 License

This project is licensed under the **MIT License**.
