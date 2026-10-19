BANSOSSMART - VERSI HTML DENGAN ALGORITMA KNN

CARA MENJALANKAN
1. Ekstrak ZIP ke folder biasa (jangan buka langsung dari dalam ZIP).
2. Buka index.html menggunakan Chrome, Edge, atau Firefox.
3. Pilih Daftar sekarang, buat akun, kemudian login.
4. Gunakan menu Data Calon Penerima, Kriteria & Bobot, Penilaian, Hasil KNN, dan Laporan.

METODE KNN
- Data contoh penerima bansos disediakan untuk demonstrasi; bukan data pasien dalam PDF diabetes.
- Data dengan label historis Layak/Tidak Layak berfungsi sebagai data latih.
- Nilai atribut dinormalisasi min-max dan jarak dihitung menggunakan Euclidean.
- Kelas dipilih melalui voting mayoritas dari K tetangga terdekat.
- Label data contoh hanya ilustrasi. Ganti dengan data historis bansos yang valid dan sudah diverifikasi.
- Hasil KNN merupakan rekomendasi awal, bukan keputusan otomatis penerima bantuan.

CATATAN
- Akun dan data disimpan di localStorage browser ini. Data tidak tersinkron ke perangkat lain.
- Login/register HTML ini demo lokal, bukan autentikasi aman untuk produksi.
- Untuk memberi label data warga baru, edit app.js seed atau gunakan data historis yang sudah memiliki label.
- CSS responsive mendukung layar laptop dan ponsel; menu dapat dibuka melalui tombol Menu pada layar kecil.
- Reset data contoh menghapus perubahan data aplikasi dan mengembalikan contoh awal.
