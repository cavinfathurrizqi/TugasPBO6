# TugasPBO6
Koneksi JFrame Form Netbeans, Dan JDIALOG dengan PostgreSQL serta Exception Java di Netbeans.
# KONEKSI JFRAME FORM dengan POSGRESQL
Konektivitas antara JFrame Form dan tabel di PostgreSQL adalah proses menghubungkan aplikasi Java berbasis GUI dengan basis data PostgreSQL agar data dapat ditampilkan, ditambahkan, diubah, atau dihapus langsung melalui antarmuka pengguna. JFrame Form berperan sebagai tampilan interaktif yang berisi komponen seperti tombol, text field, dan tabel, sedangkan PostgreSQL menyimpan data dalam bentuk tabel. Koneksi dilakukan menggunakan JDBC (Java Database Connectivity), sehingga setiap aksi pada JFrame Form, seperti menekan tombol simpan atau hapus, akan diterjemahkan menjadi perintah SQL yang dieksekusi pada tabel PostgreSQL.
# JFRAME FORM NEATBEANS
JFrame Form di NetBeans adalah jendela utama dalam aplikasi GUI berbasis Java Swing yang berfungsi sebagai wadah untuk menampilkan berbagai komponen antarmuka seperti label, tombol, text field, dan tabel. Dengan memanfaatkan fitur drag-and-drop pada NetBeans, pembuatan tampilan menjadi lebih mudah karena kode antarmuka dihasilkan secara otomatis, sehingga programmer hanya perlu menambahkan logika atau event handler pada setiap komponen. JFrame Form memudahkan pengembangan aplikasi Java yang interaktif dan user-friendly tanpa harus menulis seluruh kode GUI secara manual.
# JDIALOG FROM NEATBEANS
JDialog adalah salah satu komponen dalam Java Swing yang digunakan untuk membuat jendela dialog. Berbeda dengan JFrame yang berfungsi sebagai jendela utama, JDialog bersifat sekunder dan biasanya digunakan sebagai pendukung jendela utama, misalnya untuk menampilkan form input, form update, konfirmasi penghapusan data, atau notifikasi informasi. Dalam penggunaannya, JDialog terbagi menjadi dua jenis, yaitu modal dan modeless. Modal dialog akan menahan interaksi pengguna dengan JFrame utama sampai dialog tersebut ditutup, sehingga cocok digunakan untuk proses penting seperti insert, update, atau delete. Sebaliknya, modeless dialog tetap memungkinkan pengguna berinteraksi dengan JFrame utama meskipun dialog masih terbuka, biasanya dipakai untuk menampilkan informasi tambahan.
# Langkah-langkah Pembuatan Projek JFrame Gui dan JDialog
1. Membuat Database PostgreSQL Create Tabel
2. Membuat Project di NetBeans beri nama Datasiswa
3. Buat package bernama Data Murid, Di dalam package tersebut buat file: Koneksi.java → untuk koneksi database, DataMurid.java (JFrame Form) → GUI utama,Bank.java → simulasi exception handling.
4. DataMurid.java (JFrame utama)
5. Desain JFrame dengan komponen:
   - JButton untuk Insert, Update, Delete, Clear, Exit.
   - JTable untuk menampilkan data siswa.
6. Buat JDialog insert, update, dan delete lalu sambunkan ke jbutton insert, update dan delete di jframe untuk mengisi, mengubah dan menghapus data dari JTabel.
