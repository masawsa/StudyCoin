# Cara mendapatkan APK (gratis, tanpa Android Studio)

1. Buat akun di github.com (gratis).
2. Klik "New repository", beri nama bebas (mis. koin-belajar), pilih Public, lalu Create.
3. Ekstrak ZIP ini. Di halaman repo, pilih "uploading an existing file" dan seret SEMUA isi folder,
   termasuk folder tersembunyi ".github". Klik "Commit changes".
   (Jika folder .github tidak terlihat: di Windows aktifkan "Hidden items"; di Mac tekan Cmd+Shift+titik.)
4. Buka tab "Actions". Proses "Build APK" jalan otomatis (sekitar 3-6 menit).
5. Setelah centang hijau, klik proses tersebut, lalu unduh "koin-belajar-apk" di bagian Artifacts.
6. Ekstrak, kirim app-debug.apk ke HP, buka, izinkan "Install dari sumber tidak dikenal".

Mengubah isi aplikasi: edit www/index.html, commit, tunggu build selesai, unduh APK baru.
