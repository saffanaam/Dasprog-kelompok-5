ANGGOTA:
1. JIHAN KHAERUNNISA BAHARI POETRY/5048251023
2. AILEEN FLORENCIA HARTONO/5048251026
3. SAFFANA AYUDYA MUTHI/5048251027

PEMBAGIAN TUGAS:
1. JIHAN:
2. AILEEN : Membuat Fungsi untuk Perhitungan
3. SAFFANA: Membuat Fungsi Main

PENJELASAN
1. (penjelasan jihan)

2. - Kalkulator Hukum Ohm
   digunakan untuk menghitung besaran listrik dasar, yaitu tegangan (V), arus (I), dan hambatan (R). Pengguna dapat memilih besaran yang ingin dihitung, kemudian memasukkan dua besaran lainnya. Program akan menghitung hasilnya menggunakan rumus Hukum Ohm sehingga memudahkan perhitungan dasar rangkaian listrik.

   - Kalkulator Daya Listrik
   berfungsi untuk menghitung besar daya listrik berdasarkan nilai tegangan dan arus. Program menggunakan rumus  dan menampilkan hasil perhitungan dalam satuan Watt.

   - Kalkulator Resistor Seri
   digunakan untuk menghitung total hambatan dari beberapa resistor yang disusun secara seri. Total hambatan diperoleh dengan menjumlahkan seluruh nilai resistor yang dimasukkan oleh pengguna.

   - Kalkulator Resistor Paralel
   digunakan untuk menghitung total hambatan dari beberapa resistor yang disusun secara paralel. Program menghitung hambatan total berdasarkan kebalikan dari masing-masing hambatan resistor sesuai konsep rangkaian paralel.

3. Penjelasan Fungsi Main
Fungsi main() berfungsi sebagai menu utama yang mengatur jalannya seluruh program. Program ini dijalankan menggunakan perulangan do-while yang menyebabkan menu akan terus ditampilkan selama pengguna belum memilih opsi Keluar (9). Perintah system("clear") digunakan untuk membersihkan layar terminal agar tampilan menu tetap rapi. Dilanjut dengan menampilkan daftar menu yang berisi berbagai fitur perhitungan kelistrikan dan konversi bilangan. Pengguna diminta memasukkan pilihan menu dalam bentuk angka. Setelah input diterima, perintah getchar() digunakan untuk membuang karakter Enter yang tersisa di buffer agar tidak mengganggu proses input berikutnya.
Pemilihan fitur dilakukan menggunakan struktur switch-case, di mana setiap pilihan akan memanggil fungsi yang sesuai, seperti kalkulator hukum Ohm, daya listrik, perhitungan resistor, dan konversi bilangan. Setelah satu fitur dijalankan, program akan menunggu pengguna menekan Enter sebelum kembali ke menu utama. Hal ini bertujuan agar hasil perhitungan dapat dilihat terlebih dahulu. Program akan berhenti sepenuhnya ketika pengguna memilih menu 9 (Keluar) dan menampilkan pesan penutup.
