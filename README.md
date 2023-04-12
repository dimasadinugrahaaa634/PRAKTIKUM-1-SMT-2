# PRAKTIKUM 1

1. Buat sebuah database dengan nama latihan2!
![png](gambar/1.png)

2. Buat sebuah tabel dengan nama biodata (nama, alamat) didalam database latihan1!
![png](gambar/2.png)

3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom terakhir!
![png](gambar/3.png)

4. Tambahkan kolom id (int 11) di awal (sebagai kolom pertama)!
![png](gambar/4.png)

5. Sisipkan sebuah kolom dengan nama phone (varchar 15) setelah kolom alamat!
![png](gambar/5.png)

6. Ubah tipe data kolom id menjadi char(11)!
![png](gambar/6.png)

7. Ubah nama kolom phone menjadi hp (varchar 20)!
![png](gambar/7.png)

8. Tambahkan kolom email setelah kolom hp
![png](gambar/8.png)

9. Hapus kolom keterangan dari tabel!
![png](gambar/9.png)

10. Ganti nama tabel menjadi data_mahasiswa!
![png](gambar/10.png)

11. Ganti nama field id menjadi nim!
![png](gambar/11.png)

12. Jadikan nim sebagai PRIMARY KEY!
![png](gambar/12.png)

13. Jadikan kolom email sebagai UNIQUE KEY
![png](gambar/13.png)

* ![png](gambar/14.png)
int(11) adalah tipe data integer dan memiliki panjang 11 karakter

* ![png](gambar/15.png)
Jika kolom "NULL" memiliki nilai "YES", artinya kolom tersebut diizinkan untuk berisi nilai "NULL". Ini berarti bahwa kolom tersebut tidak harus diisi dengan nilai tertentu saat melakukan operasi INSERT atau UPDATE pada tabel.

Jika kolom "NULL" memiliki nilai "NO", artinya kolom tersebut tidak diizinkan untuk berisi nilai "NULL". Ini berarti bahwa kolom tersebut harus diisi dengan nilai tertentu saat melakukan operasi INSERT atau UPDATE pada tabel. Jika kita mencoba melakukan operasi INSERT atau UPDATE tanpa menyediakan nilai untuk kolom yang tidak diizinkan "NULL", maka MySQL akan menghasilkan kesalahan dan operasi tersebut akan gagal.
