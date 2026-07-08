# ZTE, Huawei & FiberHome WiFi Generator

---

## 📌 Ikhtisar

**ZTE, Huawei & FiberHome WiFi Generator** adalah aplikasi utilitas ringan yang dirancang untuk **validasi dan pemulihan (recovery)** kata sandi Wi-Fi *default* pada router dari tiga pabrikan besar, yaitu **ZTE**, **Huawei**, dan **FiberHome**.

Aplikasi ini dibuat khusus untuk bekerja dengan kombinasi **SSID bawaan** dan **PassKey default**. Alat ini **bukan** merupakan alat peretasan atau brute-force. Fungsinya adalah membangkitkan (generate) kata sandi bawaan berdasarkan pola SSID default sehingga menjadi solusi pemulihan yang sangat berguna ketika stiker di bagian bawah atau belakang router rusak, pudar, atau hilang.

> **Perlu diperhatikan:**  
> Aplikasi ini **hanya berfungsi jika kata sandi Wi-Fi belum pernah diubah**. Jika password sudah diedit atau diganti melalui halaman admin router, maka alat ini **tidak akan berfungsi**.

---

## 🖼️ Tampilan Aplikasi

<div align="center">
  <img src="./assets/ZTE Huawei & FiberHome Wifi Generator.jpg" alt="ZTE Huawei & FiberHome Wifi Generator" width="400" height="350">
</div>

---

## ⚙️ Cara Kerja

Aplikasi ini menggunakan algoritma atau pola tertentu yang umum digunakan oleh pabrikan untuk menurunkan kata sandi Wi-Fi default dari SSID default-nya. Jadi, Anda cukup memasukkan SSID yang terlihat, lalu alat ini akan menghitung password bawaannya.

---

## ✅ Contoh Format Default & Hasil Generate

| Pabrikan | Format SSID Default   | Contoh SSID          | Contoh Password Default |
|----------|------------------------|-----------------------|--------------------------|
| **FiberHome** | `fh_xxxxxx`       | `fh_abfa80`           | `wlan54057f`             |
| **ZTE**       | `ZTE_2.4G_xxxxxx` | `ZTE_2.4G_TC4dTU`     | `kd47sdc3`               |
| **Huawei**    | `HUAWEI-xxxx`     | `HUAWEI-ZpPu`         | `n5445Nah`               |

---

## 🛠️ Status Pengembangan Saat Ini

| Pabrikan     | Status                    |
|--------------|---------------------------|
| **FiberHome**| ✅ Berfungsi Penuh        |
| **ZTE**      | 🚧 Dalam Pengembangan     |
| **Huawei**   | 🚧 Dalam Pengembangan     |

> Saat ini, alat ini baru mendukung **FiberHome** secara penuh. Dukungan untuk ZTE dan Huawei sedang dalam tahap pengembangan aktif dan akan dirilis pada pembaruan berikutnya.

---

## 🎯 Tujuan & Penggunaan yang Dianjurkan

Proyek ini dibuat **semata-mata untuk tujuan edukasi dan pembelajaran**, serta sebagai **alat recovery** dalam situasi berikut:

- Anda baru saja melakukan *reset pabrik* (factory reset) pada router.
- SSID default masih terlihat saat memindai jaringan, tetapi stiker kata sandi default sudah hilang atau tidak terbaca.
- Anda perlu mengakses kembali jaringan pribadi Anda tanpa harus melakukan reset ulang.

---

## 🖥️ Persyaratan Sistem

Karena aplikasi ini dirancang khusus untuk ekosistem Windows, pastikan perangkat Anda memenuhi persyaratan berikut:

- **Sistem Operasi:** Windows 7 / 8 / 10 / 11 (32-bit atau 64-bit)
- **Arsitektur:** x86 / x64
- **Ekstra:** Tidak memerlukan instalasi tambahan; jalankan langsung file `.exe` yang disediakan.

---

## 📦 Instalasi & Cara Penggunaan

### 1. Unduh Aplikasi
Kunjungi halaman [Rilis (Releases)](https://github.com/MichaelJorky/zt-hw-fh-wifi-generator/releases) dan unduh file terbaru dengan ekstensi `.exe`.

### 2. Jalankan Aplikasi
Ekstrak file (jika dalam bentuk ZIP) lalu jalankan `ZTE HW & FH Wifi Generator.exe`.

### 3. Langkah Penggunaan:
1. Pilih pabrikan router (**FiberHome**, **ZTE**, atau **Huawei**).
2. Masukkan SSID default yang terlihat (contoh: `fh_abfa80`).
3. Klik tombol **Generate**.
4. Kata sandi default akan muncul di layar.
5. Gunakan kata sandi tersebut untuk terhubung ke jaringan Wi-Fi Anda.

---

## ⚖️ Peringatan (Disclaimer)

> **Aplikasi ini disediakan "apa adanya" (as is) untuk tujuan edukasi dan pemulihan perangkat milik sendiri.**
>
> - Pengembang **tidak bertanggung jawab** atas segala bentuk penyalahgunaan aplikasi ini.
> - Menggunakan alat ini untuk mengakses jaringan orang lain **tanpa izin** adalah tindakan melanggar hukum dan bertentangan dengan etika.
> - Segala tindakan yang dilakukan dengan menggunakan alat ini sepenuhnya menjadi **tanggung jawab pengguna akhir**.
> - Jika digunakan di luar konteks yang telah dijelaskan (edukasi dan recovery perangkat pribadi), maka hal tersebut berada di luar tanggung jawab kami.

---

## 🤝 Kontribusi

Kami sangat terbuka terhadap kontribusi! Jika Anda memiliki wawasan atau informasi tambahan mengenai algoritma kata sandi default untuk router ZTE atau Huawei, silakan buka *issue* atau kirimkan *pull request*.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT** – silakan lihat berkas [LICENSE](LICENSE) untuk informasi lebih lanjut.

---

## 📬 Kontak

Jika ada pertanyaan, saran, atau laporan bug, silakan buka *issue* di repositori GitHub ini atau hubungi pengelola proyek.

---

**Dibuat dengan ❤️ untuk komunitas jaringan di Indonesia.**
