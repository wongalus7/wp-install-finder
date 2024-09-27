# Mass WordPress Install Scanner
![image](https://github.com/user-attachments/assets/71670c7b-26f6-4208-8969-bbcf7203a301)
WP-Install-Finder merupakan kode sederhana untuk mencari file instalasi WordPress (setup-config.php) di berbagai direktori umum di website. Tujuan dari script ini adalah membantu mengidentifikasi instalasi WordPress yang belum dikonfigurasi (belum selesai setup) atau rentan terhadap eksploitasi.

# Fitur WP-Install-Finder
- Multi-threading: Script ini menggunakan multiprocessing untuk memindai banyak URL sekaligus, sehingga proses pemindaian lebih cepat.
- User-Agent Randomization: Setiap request dikirim dengan User-Agent yang dipilih secara acak dari file user-agents.txt, agar tidak mudah terdeteksi oleh server target.
- Status Code Reporting: Hasil pemindaian akan menunjukkan status code HTTP (seperti 200, 404, dll) untuk setiap path yang dipindai.

# Install (Linux)
```bash
apt install python3
apt install python3-pip
pip3 install requests colorama
apt install git
git clone https://github.com/wongalus7/wp-install-finder/
cd wp-install-finder
python3 wpinstall.py
```
# Disclaimer
Alat ini hanya untuk tujuan pembelajaran! Jangan digunakan untuk aktivitas ilegal atau tanpa izin pemilik situs. Selalu hormati privasi dan keamanan orang lain.
