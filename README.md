# Auto WordPress-Chaker

## Badge
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.6%2B-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20MacOS-lightgrey)
![Made With](https://img.shields.io/badge/made%20with-Python-orange)
![Status](https://img.shields.io/badge/status-active-success)

![Auto WordPress Chaker](https://e.top4top.io/p_3479ec0ly3.jpg)

## Deskripsi
**Auto WordPress Chaker** adalah alat untuk memeriksa login ke situs WordPress secara otomatis dan mengkategorikan login yang berhasil. Alat ini menggunakan teknik brute force untuk memeriksa kredensial pengguna di berbagai situs WordPress dan menyimpan hasilnya dalam file terpisah berdasarkan kategori.

## Fitur Utama
- ✅ Cek login otomatis ke WordPress  
- ✅ Kategorisasi login yang berhasil (WooCommerce, WP File Manager, Plugin Installer)  
- ✅ Menyimpan hasil login ke file yang berbeda    
- ✅ Mendukung multi-thread untuk mempercepat proses  
- ✅ Header random (User-Agent acak)  
- ✅ Tersedia waktu kadaluarsa untuk keamanan  

## Persyaratan
- Python 3.x
- Pustaka Python: `requests`, `idna`
- Platform: Windows, Linux, MacOS, Termux

## Instalasi

### Termux Command
```bash
pkg update -y
pkg upgrade -y
pkg install python -y
pkg install git -y
pip install requests idna
```

### Linux / Debian Command
```bash
sudo apt update -y
sudo apt upgrade -y
sudo apt install python3 python3-pip git -y
pip3 install requests idna
```

## Penggunaan

1. Clone repositori:
```bash
git clone https://github.com/LikeEx01/Wordpress-Cheker.git
```

2. Masuk ke direktori:
```bash
cd AutoCheker
```

3. Jalankan alat:
```bash
python AutoCheker.py
```

4. Input file .txt dengan format:
```
https://example.com|admin|password
http://site.com/wp-login.php|user|pass123
```

5. Tentukan jumlah thread saat diminta (misalnya: 10, 20, dll).

## Output

Hasil login yang dikategorikan akan otomatis disimpan ke file:

- `WooCommerce.txt`: Login sukses dengan plugin WooCommerce  
- `wpfilemanager.txt`: Login sukses dengan plugin WP File Manager  
- `plugin-install.txt`: Login sukses dengan akses instal plugin  


## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).

## Penafian
> ⚠️ **Peringatan:** Alat ini dibuat untuk tujuan **edukasi dan pengujian keamanan secara etis**.  
> **Dilarang keras menggunakan alat ini untuk menyerang situs tanpa izin eksplisit dari pemilik situs.**  
> Penggunaan tanpa izin adalah **tanggung jawab pengguna sepenuhnya**.

## Kontak
Jika Anda memiliki pertanyaan, permintaan fitur, atau laporan bug, silakan:

- Buka [Issue di GitHub](https://github.com/LikeEx01/Wordpress-Cheker.git)  
- Hubungi saya melalui Telegram: [LikeEx01](https://t.me/usernamee1337)

## Terima Kasih
Terima kasih telah menggunakan **Auto WordPress Chaker**.  
Semoga alat ini bermanfaat untuk mengamankan dan menguji keamanan situs WordPress Anda secara legal.

🔗 **Repo GitHub:** [LikeEx01](https://github.com/LikeEx01/Wordpress-Cheker.git)
