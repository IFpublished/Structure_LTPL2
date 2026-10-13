# GeoPDF Viewer – Android (APK)

Aplikasi Android dari GeoPDF Viewer (Capacitor). APK dibuild otomatis oleh GitHub Actions
setiap ada perubahan di branch `main`, lalu muncul di menu **Releases** repo ini.

- Web app: `www/index.html` (ganti file ini untuk update tampilan/fitur, lalu commit)
- Kode Android: folder `android/`
- Workflow build: `.github/workflows/build-apk.yml`
- Kunci tanda tangan APK: `android/app/geopdf-release.jks` – **jangan dihapus/diganti**,
  karena update APK hanya bisa di-install menimpa versi lama kalau kuncinya sama.
  Simpan repo ini sebagai **Private**.
