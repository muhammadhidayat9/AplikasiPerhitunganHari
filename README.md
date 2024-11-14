# Aplikasi Perhitungan Hari

## Deskripsi Program
Aplikasi ini adalah program GUI sederhana menggunakan Java Swing yang dapat menghitung jumlah hari dalam suatu bulan yang dipilih pengguna. Fitur utama:

- Pengguna memilih **bulan** dari JComboBox dan memasukkan **tahun** menggunakan JSpinner.
- Mendukung penggunaan **JCalendar** untuk memilih tanggal.
- Hasil jumlah hari dalam bulan ditampilkan setelah tombol "Hitung" ditekan.

## Komponen GUI
Aplikasi ini menggunakan beberapa komponen GUI, yaitu:

- `JFrame`: Jendela utama aplikasi.
- `JPanel`: Panel untuk tata letak komponen GUI.
- `JLabel`: Menampilkan informasi dan hasil kepada pengguna.
- `JComboBox`: Memilih bulan.
- `JSpinner`: Input tahun dari pengguna.
- `JButton`: Tombol untuk menghitung jumlah hari.
- `JCalendar`: Komponen kalender untuk memilih bulan dan tahun.

## Logika Program
Logika program menggunakan:

- **API tanggal Java (LocalDate)**: Untuk mendapatkan informasi jumlah hari dalam bulan dan tahun yang dipilih.
- Perhitungan tambahan untuk tahun **kabisat**, memastikan hasil yang akurat pada bulan Februari.

## Events
Aplikasi ini menggunakan event handling sebagai berikut:

- **ActionListener**: Untuk menangani klik pada tombol "Hitung".
- **ChangeListener**: Untuk memonitor perubahan pada JSpinner saat tahun diubah oleh pengguna.

## Fitur Tambahan
- Menampilkan informasi hari pertama dan hari terakhir dalam bulan yang dipilih.
- Menghitung selisih antara hari yang dipilih dengan hari terakhir dibulan itu menggunakan JCalendar.

## Cara Menggunakan
1. Pilih bulan dari JComboBox.
2. Masukkan tahun menggunakan JSpinner atau pilih tanggal menggunakan JCalendar.
3. Klik tombol "Hitung".
4. Hasil jumlah hari akan ditampilkan di JLabel. Jika ada error atau input tidak valid, pesan akan ditampilkan menggunakan JOptionPane.

## Variasi Pengembangan
- Menambahkan fitur untuk menentukan apakah tahun yang dimasukkan adalah **tahun kabisat**.
- Integrasikan fitur untuk menghitung selisih hari antara hari yang dipilih dengan hari terakhir dibulan itu.

## Teknologi yang Digunakan
- **Java Swing**: Untuk membangun antarmuka GUI.
- **Java Date and Time API (LocalDate)**: Untuk perhitungan tanggal dan validasi tahun kabisat.
- **NetBeans IDE**: Proyek ini dikembangkan menggunakan NetBeans IDE.

## Penulis
Muhammad Hidayat (2210010354).

