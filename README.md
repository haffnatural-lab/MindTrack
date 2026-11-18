# MindTrack Android

Aplikasi Android offline-first untuk pemantauan psikologis dan refleksi diri. Dibangun sebagai Android WebView lokal; data dicatat di penyimpanan lokal aplikasi (localStorage), tidak membutuhkan akun atau koneksi internet.

## Fitur
- Mood tracker: emosi, intensitas, pemicu, catatan.
- Energi, tidur, produktivitas, fokus, impulsivitas, pengeluaran.
- Financial Decision Guard berupa pengingat reflektif.
- Deep breathing, grounding 5-4-3-2-1, relaksasi otot progresif, positive self-talk, unsent letter, cognitive restructuring, peaceful place.
- Jurnal dan grafik ringkasan.
- Ekspor cadangan JSON dan CSV.

## Membuat APK
Persyaratan: Android Studio (Koala atau lebih baru), Android SDK Platform 35, JDK 17.
1. Ekstrak folder proyek.
2. Android Studio > Open > pilih folder `MindTrackAndroid`.
3. Tunggu Gradle Sync dan instal Android SDK 35 bila diminta.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK debug akan berada di `app/build/outputs/apk/debug/app-debug.apk`.

Untuk APK rilis: Build > Generate Signed Bundle / APK > APK, lalu buat atau pilih keystore pribadi. Simpan keystore dan kata sandinya dengan aman.

## Privasi dan batasan
- Data hanya disimpan pada perangkat melalui penyimpanan lokal aplikasi. Menghapus data aplikasi dapat menghapus catatan; gunakan ekspor cadangan.
- Aplikasi bukan alat diagnosis, terapi, atau layanan darurat. Gunakan sebagai pendamping refleksi dan diskusikan perubahan yang mengkhawatirkan dengan psikolog/dokter.
