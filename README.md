# Admin Path Scanner

Admin Path Scanner adalah alat sederhana yang ditulis dalam Python untuk memindai URL target dan mencari jalur login admin yang umum digunakan. Skrip ini menggunakan pustaka `requests` untuk melakukan permintaan HTTP dan `colorama` untuk memberikan warna pada output terminal.

## Fitur

- Memindai jalur login admin yang umum digunakan.
- Menampilkan status respons HTTP untuk setiap jalur yang diperiksa.
- Menyediakan umpan balik yang jelas dengan warna yang berbeda untuk status yang berbeda.

## Prasyarat

Sebelum menjalankan skrip ini, pastikan Anda telah menginstal Python dan pustaka yang diperlukan. Anda dapat menginstal pustaka yang diperlukan dengan menjalankan perintah berikut:

```bash
pkg install python
pkg instll git
pip install requests
pip install colorama
git clone https://github.com/RidXploit403/Admin-Finder.git
python admin_finder.py

Enter the target URL : http://example.com
[*] Scanning http://example.com for admin paths...
[+] Found: http://example.com/admin/login.php
[-] Not found: http://example.com/admin/index.php
[!] Status 203: http://example.com/wp-login.php
