# Tanjakan Raya

Game balap tanjakan mirip Hill Climb Racing. 12 peta, 12 mobil, upgrade, misi, dan efek suara.

## Cara membuat APK lewat GitHub

1. Buat repository baru di GitHub (boleh private).
2. Upload semua isi folder ini ke repository, termasuk folder `.github`.
3. Buka tab **Actions**, pilih **Build APK**, lalu klik **Run workflow**. Build juga jalan otomatis tiap push ke branch `main`.
4. Tunggu sekitar 5 sampai 8 menit sampai centang hijau.
5. Buka run yang selesai, lalu unduh **tanjakan-raya-apk** di bagian Artifacts. Di dalamnya ada `app-debug.apk`.
6. Kirim APK ke HP, buka, dan izinkan instal dari sumber tidak dikenal.

## Catatan

- Isi game ada di `www/index.html`. Ubah file itu lalu push, APK baru akan dibuat otomatis.
- APK ini versi debug. Untuk Play Store dibutuhkan build release yang ditandatangani.
- Progres game tersimpan di penyimpanan lokal aplikasi.
