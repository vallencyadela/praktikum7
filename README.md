## Vallencya - NIM : 352310368
# Penjelasan Program Daftar Nilai Mahasiswa

Program ini dibuat untuk mengelola dan menampilkan daftar nilai mahasiswa dengan menggunakan dictionary. Pengguna dapat melakukan berbagai operasi seperti menambah, mengubah, menghapus, melihat, dan mencari data mahasiswa. Nilai akhir mahasiswa dihitung berdasarkan nilai tugas, UTS, dan UAS. Berikut ini gambar perintah program yang sudah dibuat dalam phyton:


![tampilan kedua](https://github.com/user-attachments/assets/48d05d9d-1991-405e-bfad-548cf79a5b11)
![tampilan kedua part 2](https://github.com/user-attachments/assets/f5e57947-f01a-4d0c-b969-e073a735e0e6)


## Alur perintah program

### 1. `menghitung_nilai_akhir(nilai_tugas, nilai_uts, nilai_uas)`
- **Deskripsi**: Menghitung nilai akhir mahasiswa berdasarkan komponen nilai.
- **Parameter**:
  - `nilai_tugas`: Nilai tugas mahasiswa.
  - `nilai_uts`: Nilai UTS mahasiswa.
  - `nilai_uas`: Nilai UAS mahasiswa.
- **Rumus**:
  
  ![rumus tugas akhir](https://github.com/user-attachments/assets/3608f9b9-f2a7-4f42-bd7b-a6bbd58bf48a)

- **Return**: Mengembalikan nilai akhir yang telah dihitung.

## Struktur Data

### Dictionary `data_mahasiswa`
- **Kunci**: NIM mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.
  - `nilai_akhir`: Nilai akhir yang dihitung.

## Menu Interaksi

Pengguna diberikan pilihan untuk melakukan operasi berikut:

1.  Lihat Data**
   - Menampilkan seluruh data mahasiswa dalam format tabel.

2.  Tambah Data**
   - Meminta input dari pengguna untuk menambahkan data mahasiswa baru, termasuk nama, NIM, nilai tugas, nilai UTS, dan nilai UAS. Data yang dimasukkan akan dihitung nilai akhirnya dan disimpan.

3. Ubah Data**
   - Meminta NIM mahasiswa yang ingin diubah. Jika data ditemukan, pengguna dapat memperbarui nilai tugas, UTS, dan UAS. Nilai akhir akan diperbarui sesuai dengan perubahan.

4.  Hapus Data**
   - Meminta NIM mahasiswa yang ingin dihapus. Jika data ditemukan, maka data mahasiswa tersebut akan dihapus dari daftar.

5.  Cari Data**
   - Meminta NIM mahasiswa yang ingin dicari. Jika data ditemukan, program akan menampilkan informasi mahasiswa tersebut.

6.  Keluar**
   - Mengakhiri program.


## FLOWCHART 

![flow chart](https://github.com/user-attachments/assets/f8b6be90-46b9-4708-ba94-d1cc1eb30ba4)

1. Start: Titik awal program.
2. Inisialisasi Dictionary data_mahasiswa: Membuat dictionary kosong untuk menyimpan data mahasiswa.
3. Tampilkan Menu: Menampilkan pilihan menu kepada pengguna (Lihat, Tambah, Ubah, Hapus, Cari, Keluar).
4. Input Pilihan Menu: Pengguna memasukkan pilihan menu.
5. Pilihan Menu:
Jika pengguna memilih T (Tambah):
Input data mahasiswa (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).
Hitung nilai akhir menggunakan fungsi hitung_nilai_akhir.
Simpan data ke dalam dictionary.
Tampilkan pesan bahwa data berhasil ditambahkan.
Jika pengguna memilih U (Ubah):
Input NIM mahasiswa yang ingin diubah.
Jika NIM ditemukan, input nilai baru (Tugas, UTS, UAS).
Hitung nilai akhir baru dan perbarui data.
Tampilkan pesan bahwa data berhasil diubah.
Jika pengguna memilih H (Hapus):
Input NIM mahasiswa yang ingin dihapus.
Jika NIM ditemukan, hapus data dari dictionary.
Tampilkan pesan bahwa data berhasil dihapus.
Jika pengguna memilih L (Lihat):
Tampilkan semua data mahasiswa dalam format tabel.
Jika pengguna memilih C (Cari):
Input NIM mahasiswa yang ingin dicari.
Jika NIM ditemukan, tampilkan informasi mahasiswa.
Jika pengguna memilih K (Keluar):
6. Tampilkan pesan bahwa program selesai dan keluar dari loop.
7. End: Titik akhir program.
