# anydesk
AnyDesk v5 adalah aplikasi remote desktop untuk mengakses dan mengontrol komputer dari jarak jauh dengan cepat dan aman. Keunggulan: koneksi ringan dan stabil, tampilan tetap halus, mendukung berbagai platform, transfer file mudah, enkripsi data, serta fitur akses tanpa konfirmasi (unattended access).


Solusi Jika Tidak bisa Terhubung ke Internet:

1. Tutup AnyDesk sepenuhnya
Di CMD Administrator:
net stop AnyDesk
Pastikan muncul The AnyDesk service was stopped successfully.
2. Rename konfigurasi, jangan hapus
Ini penting: rename, bukan delete.
ren "%ProgramData%\AnyDesk" "AnyDesk.old"
Lalu:
ren "%AppData%\AnyDesk" "AnyDesk.old"
3. Jalankan kembali AnyDesk
net start AnyDesk
Kemudian buka:
"C:\Program Files (x86)\AnyDesk\AnyDesk.exe"
Tunggu sekitar 30 detik.
4. Periksa hasilnya
Lihat apakah sekarang:
•       	This Desk sudah mendapatkan ID, atau
•       	masih 0 / Connecting.
