# Praktikum5
Membuat Program Sederhana Pendaftaran Nilai Mahasiswa Dengan Ketentuan Sebagai Berikut :  <p>

Program dibuat dengan kamus <p>
menampilkan menu pilihan: <p>
--tambah data <p>
--Ubah Data <p>
--Hapus Data <p>
--Cari Data <p>
--Tampilkan Data <p>
Nilai akhir dihitung dari 3 komponen perhitungan (Tugas 30%, Uts 35%, Uas 35%) <p>
Buat flowchart dan penjelasan program pada README.md <p>
Komit dan Dorong repositori ke github <p>
FLOWCHART <P>
![gambar](gambar praktikum/flowchart.png)

---PROGRAM---
![gambar](gambar praktikum/pic1.png)
![gambar](gambar praktikum/pic2.png)
![gambar](gambar praktikum/pic3.png)
Hasil eksekusi <p>
![gambar](gambar praktikum/pic4.png)
![gambar](gambar praktikum/pic5.png)
## Penjelasan
--- PENJELASAN ---
1.Start
2.inputkan data={} sesuai kenginan dengan format kamus
3.Gunakan perulangan While True untuk menampilkan data sebanyak-banyaknya
4.masukan perintah g = input("(T)ambah, (U)bah, (H)apus, (L)ihat,(C)ari, (K)eluar: "),untuk mendapatkan perintah Tambah, Ubah, Hapus,Lihat ,Cari,Keluar.
5.menambahkan data menggunakan fungsi elif, lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ((tugas)*30/100+(uts)*35/100+(uas)*35/100
6.jika ingin memilih "lihat" gunakan fungsi 'elif' dan gunakan fungsi 'for x in data.items():' untuk memasukkan data ke dalam tabel data yang kita inputkan, dengan perintah "l". jika data yang tidak tercatat = 0
Untuk menampilkan pilihan "hapus"gunakan fungsi 'elif' kemudian gunakan fungsi 'jika nama di data.keys():' kemudian fungsi'del.data[nama] 7.jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan data tidak ada.
8.lalu untuk menampilkan pilihan "cari"" gunakan fungsi 'elif' kemudian gunakan fungsi if nama in data.keys():' untuk mencari data nama 9. kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita cari tidak ada.
9.lalu jika ingin keluar dari program gunakan fungsi 'jika' kemudian gunakan fungsi break untuk keluar dari data nilai/menghentikan program
10.Berhenti