# e-SKSB — Starter Prototype

Prototaip antaramuka untuk sistem bersepadu SK Sungai Buri.

## Kandungan
- `index.html` — prototaip interaktif: log masuk demo, garis masa 2027, kalendar bulanan, aktiviti dan paparan kehadiran/setting.
- `firestore.rules.example` — contoh asas peraturan keselamatan untuk dibangunkan lanjut.
- `firebase-config.example.js` — templat konfigurasi Firebase (isi sendiri melalui Firebase Console).

## Cara cuba
1. Ekstrak ZIP.
2. Buka `index.html` menggunakan pelayar web.
3. Masukkan kod sekolah `YBB4365`, nama demo dan pilih peranan.
4. Ini hanya simulasi frontend. Data contoh berada dalam memori pelayar dan tidak disimpan ke Firebase.

## Sebelum penggunaan sebenar
- Wujudkan Firebase project.
- Aktifkan Firebase Authentication dan Firestore.
- Wujudkan akaun pengguna individu; jangan gunakan kod sekolah sebagai kata laluan bersama.
- Tetapkan custom claims/role dan tugasan Editor di backend.
- Lengkapkan Firestore Security Rules dan Storage Rules.
- Integrasikan kehadiran mesin melalui kaedah eksport/API rasmi peranti yang disahkan.
- Jangan letakkan kata laluan admin, service account atau private key dalam HTML/JavaScript awam.

## Modul sasaran
1. Login dan identiti pengguna.
2. Timeline dan kalendar induk 2027.
3. Program, mesyuarat dan tarikh penting.
4. Kehadiran guru/AKP/pekerja.
5. Setting admin, tugasan Editor/Viewer.
6. Dokumen dan eksport PDF.

- `logo-sk-sungai-buri.png` — logo sekolah yang dibekalkan.
