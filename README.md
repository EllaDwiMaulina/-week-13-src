# 362358302098_Ella Dwi Maulina

### Soal 3
1. Jelaskan fungsi keyword yield* pada kode tersebut! :
yield* dalam Dart digunakan untuk mendelegasikan semua elemen dari stream atau iterable lain ke pemanggil, sehingga pada kode ini nilai dari Stream.periodic dipancarkan setiap 1 detik secara berulang berdasarkan elemen-elemen dalam colors.

2. Apa maksud isi perintah kode tersebut? :
Kode tersebut membuat stream yang memancarkan warna dari daftar colors secara berulang setiap 1 detik menggunakan Stream.periodic dan didelegasikan dengan yield*.

### Soal 4
![Gif](assets/W13%20Jawaban%20Soal%204.gif)

### Soal 5
1. Jelaskan perbedaan menggunakan listen dan await for (langkah 9) ! :
Perbedaan antara listen dan await for adalah listen digunakan untuk memantau stream dengan callback dan memungkinkan kita menghentikan atau melanjutkan stream, sedangkan await for dipakai dalam fungsi async untuk memproses data dari stream satu per satu secara berurutan.