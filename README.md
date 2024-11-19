**PRAKTIKUM 6**
# Soal
**Tugas Praktikum**

Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan
- Program dibuat dengan menggunakan Dictionary
- Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md. 
- Commit dan push repository ke github.

# Flowchart
![flowchart praktikum6](https://github.com/user-attachments/assets/441d6638-57e5-490a-a791-634a5176af11)

# Jawaban
1. Program dimulai dengan menampilkan menu pilihan:

- Lihat data mahasiswa
- Tambah data mahasiswa
- Ubah data mahasiswa
- Hapus data mahasiswa
- Cari data mahasiswa
- Keluar
2. Jika pengguna memilih "Lihat data mahasiswa", program akan menampilkan data mahasiswa yang ada. Jika tidak ada data mahasiswa, program akan menampilkan pesan "TIDAK ADA DATA".

3. Jika pengguna memilih "Tambah data mahasiswa", program akan meminta user untuk input NIM. Setelah itu akan dicek apakah NIM sudah ada di database. Jika NIM sudah ada, program akan menampilkan pesan "DATA SUDAH ADA". Jika belum ada, program akan meminta user untuk input data mahasiswa lainnya seperti nama, nilai tugas, nilai UTS, nilai UAS, dan program akan menghitung nilai akhir mahasiswa.

4. Jika user memilih "Ubah data mahasiswa", program akan meminta user untuk input NIM yang ingin diubah. Jika NIM ditemukan, program akan meminta user untuk input data mahasiswa lainnya yang ingin diubah, kemudian program akan menghitung nilai akhir mahasiswa yang sudah diubah.

5. Jika user memilih "Hapus data mahasiswa", program akan meminta user untuk input NIM yang ingin dihapus. Jika NIM ditemukan, program akan menghapus data mahasiswa tersebut.

6. Jika user memilih "Cari data mahasiswa", program akan meminta user untuk input NIM yang ingin dicari. Jika NIM ditemukan, program akan menampilkan data mahasiswa tersebut. Jika tidak ditemukan, program akan menampilkan pesan "DATA TIDAK DITEMUKAN".

7. Jika user memilih "Keluar", program akan berhenti.

**Keterangan:**

- **Input NIM**: Kotak ini menunjukkan bahwa program meminta user untuk memasukkan NIM.
- **Data Ditemukan?:** Kotak ini menunjukkan bahwa program akan memeriksa apakah data mahasiswa dengan NIM yang dimasukkan user sudah ada di database.
- **Tampilkan Data:** Kotak ini menunjukkan bahwa program akan menampilkan data mahasiswa.
- **Input Nama, Input Nilai Tugas, Input Nilai UTS, Input Nilai UAS:** Kotak ini menunjukkan bahwa program meminta user untuk memasukkan nama, nilai tugas, nilai UTS, nilai UAS.
- **Hitung Nilai Akhir:** Kotak ini menunjukkan bahwa program akan menghitung nilai akhir mahasiswa.
- **Simpan Data:** Kotak ini menunjukkan bahwa program akan menyimpan data mahasiswa yang baru dimasukkan atau yang sudah diubah.
- **Hapus Data:** Kotak ini menunjukkan bahwa program akan menghapus data mahasiswa
