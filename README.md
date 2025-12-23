# 🚀 Install Android Studio

Panduan ini menjelaskan cara menyiapkan Android Studio versi terbaru untuk pengembangan aplikasi Android pada Windows dan macOS.

> **Catatan:**  
> Android Studio versi terbaru sudah menyertakan JDK bawaan, sehingga instalasi JDK terpisah **tidak wajib** untuk sebagian besar kebutuhan.

---

## 📋 System Requirements

### Supported Operating Systems

| Windows | macOS |
|--------|------|
| Windows 10 (64-bit) atau lebih baru | macOS 10.15 (Catalina) atau lebih baru |

### Hardware Requirements

- **RAM**
  - Minimum: 4 GB  
  - Direkomendasikan: 8 GB atau lebih
- **Storage**
  - Minimum: 8 GB ruang kosong  
  - Direkomendasikan: 15–20 GB (IDE, SDK, dan Emulator)
- **CPU**
  - Mendukung virtualisasi (Intel VT-x / AMD-V) untuk Android Emulator

---

## 🧩 Required Software

- Android Studio (Latest Stable Version)
- JDK (sudah termasuk di Android Studio)

---

## 🔽 Step 1: Download Android Studio

Unduh Android Studio dari situs resmi Android Developer:

https://developer.android.com/studio

Pilih installer sesuai sistem operasi:
- Windows (`.exe`)
- macOS (`.dmg`)

---

## 💻 Step 2: Install Android Studio

### Windows
1. Jalankan file installer `.exe`
2. Ikuti proses instalasi hingga selesai
3. Gunakan pengaturan default (direkomendasikan)
4. Pastikan komponen berikut terpasang:
   - Android SDK
   - Android Emulator
   - Android Virtual Device (AVD)

### macOS
1. Buka file `.dmg`
2. Drag **Android Studio** ke folder **Applications**
3. Jalankan Android Studio
4. Ikuti Setup Wizard

---

## ⚙️ Step 3: Initial Setup & SDK Configuration

Saat pertama kali menjalankan Android Studio:

1. Pilih **Standard Setup**
2. Android Studio akan otomatis mengunduh:
   - Android SDK
   - Platform Tools
   - Build Tools
   - System Image untuk Emulator
3. Tunggu hingga proses selesai

---

## ☕ Step 4 (Optional): External JDK Configuration

Langkah ini **opsional** dan hanya diperlukan jika:
- Menggunakan project lama
- Membutuhkan versi Java tertentu

### Mengatur JDK di Android Studio
1. Buka **Settings / Preferences**
2. Masuk ke **Build, Execution, Deployment → Build Tools → Gradle**
3. Pada **Gradle JDK**, pilih:
   - **Embedded JDK** (direkomendasikan), atau
   - JDK eksternal sesuai kebutuhan

---

## ✅ Step 5: Verify Installation

Buka Terminal (macOS) atau Command Prompt (Windows), lalu jalankan:

```bash
java -version
javac -version
```

Jika Android Studio dapat membuat dan menjalankan project tanpa error, instalasi berhasil.

---

## 📱 Optional: Run App Without Emulator

Jika spesifikasi komputer terbatas:
1. Aktifkan **USB Debugging** di perangkat Android
2. Hubungkan perangkat ke komputer
3. Jalankan aplikasi langsung ke device

---

## 🧠 Notes & Best Practices

- Gunakan Android Studio **Stable Channel**
- Gunakan **Kotlin** sebagai bahasa utama
- Update SDK melalui **SDK Manager**
- Gunakan emulator hanya jika diperlukan untuk performa optimal

---

## 🎯 Conclusion

Dengan mengikuti panduan ini, lingkungan pengembangan Android kamu sudah siap menggunakan tool dan standar terbaru.

Happy coding 🚀
