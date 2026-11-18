# Build APK online tanpa Android Studio di komputer

Project ini sudah dilengkapi workflow GitHub Actions pada `.github/workflows/build-apk.yml`.

1. Buat akun atau masuk ke https://github.com.
2. Buat repository baru bernama `MindTrack` (boleh Public atau Private).
3. Upload seluruh ISI folder `MindTrackAndroid` ke repository, termasuk folder tersembunyi `.github/workflows`.
4. Pastikan file `.github/workflows/build-apk.yml` terlihat di GitHub.
5. Buka tab **Actions** pada repository. Jika diminta, pilih **I understand my workflows, go ahead and enable them**.
6. Workflow **Build MindTrack APK** akan berjalan otomatis setelah push ke branch `main`. Bisa juga pilih workflow itu lalu klik **Run workflow**.
7. Tunggu sampai status hijau (sukses), buka hasil run tersebut.
8. Di bagian **Artifacts**, unduh `MindTrack-debug-apk`.
9. Ekstrak ZIP artifact dan ambil `app-debug.apk`, lalu pindahkan ke HP Android untuk dipasang.

Catatan:
- Build dilakukan di server GitHub; tidak perlu memasang Android Studio atau Gradle lokal.
- Artifact hasil build tersedia selama 14 hari.
- APK debug cocok untuk uji coba pribadi. Jangan membagikan APK debug sebagai distribusi publik.
- Jangan unggah password, keystore, atau data pribadi ke repository.
