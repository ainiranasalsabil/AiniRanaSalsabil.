AINI RANA SALSABIL - BUILD APK TANPA ANDROID STUDIO

APK dibuat secara online menggunakan GitHub Actions. Kamu hanya perlu
browser dan akun GitHub gratis.

LANGKAH-LANGKAH:
1. Download dan ekstrak ZIP project ini.
2. Buka https://github.com lalu login / buat akun.
3. Klik tombol + > New repository.
4. Beri nama repository: AiniRanaSalsabil, pilih Public atau Private,
   lalu klik Create repository.
5. Di halaman repository, pilih Add file > Upload files.
6. Upload SEMUA ISI folder AiniRanaAndroid (termasuk folder .github).
   Pastikan build.gradle, settings.gradle, app/, dan .github/ terlihat
   di halaman utama repository.
7. Klik Commit changes.
8. Buka tab Actions. Pilih workflow "Build Android APK".
9. Jika belum berjalan otomatis, klik Run workflow > Run workflow.
10. Tunggu sampai proses selesai dengan tanda centang hijau.
11. Buka hasil run workflow, gulir ke bagian Artifacts, lalu unduh
    AiniRanaSalsabil-APK.
12. Ekstrak file ZIP hasil unduhan. Di dalamnya ada app-debug.apk.
    Kirim APK ke HP Android, buka file tersebut, lalu izinkan instalasi
    dari sumber ini jika Android memintanya.

CATATAN:
- Build dilakukan oleh GitHub Actions, bukan di laptop.
- File APK yang dihasilkan adalah debug APK untuk uji coba.
- Jangan bagikan repository jika kamu tidak ingin source project terlihat.
- Jika build gagal, kirim screenshot log tab Actions agar bisa diperbaiki.
