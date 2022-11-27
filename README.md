# PRAKTIKUM 6 ADITYA PUTRA WIJAYA

## DICTIONARY
#### - MEMBUAT DICTIONARY
```
a = {} # empty dict
a = ['n1': 100, 'n2': 20, 'n3': 7] # dict with key:value
```
#### - MENGAKSES DICTIONARY
```
print(a['n2']) # print element with key 'n2'
print(a.keys()) # print all key from dict
print(a.values()) # print all value form dict
print(a.items()) # print list of tuple(key, value) form dict
```
#### - MENGUBAH ELEMEN DICTIONARY
```
a['n2'] = 10 # change the item for key 'n2
```
#### - MENAMBAHKAN ELEMEN DICTIONARY
```
a['n4'] # add item with key 'n4'
```
#### - LOOP DICTIONARY
```
for item in a.items():
print(item) # print tuple (key, value)
print(item[0]) # print key item
```
#### - HASIL SETELAH DI RUN

![gambar1](gambar/gam11.png)


# LATIHAN 1
### MEMBUAT DICTIONARY DAFTAR KONTAK
- Nama sebagai Key dan Nomor sebagai Value
- Tampilkan kontaknya Ari
- Tambah kontak baru dengan nama Riko, nomor 087654544
- Ubah kontak Dina dengan nomor baru 088999776
- Tampilkan semua Nama
- Tampilkan semua Nomor
- Tampilkan daftar Nama dan nomornya
- Hapus kontak Dina.

### CONTOHNYA
![gambar1](gambar/gam2.jpeg)

### HASIL SETELAH DI RUN
![gambar1](gambar/gam1.png)


# TUGAS PRAKTIKUM 6
### DAFTAR NILAI MAHASISWA MENGGUNAKAN DICTIONARY
- Pertama kita membuat sebuah dictionary kosong yang nantinya akan diinputkan data ketika program dijalankan.
- Lalu kita membuat kondisi perulangan dan sebuah keterangan untuk pilihan menu yang akan menjalankan program.
- Membuat syntax untuk menambahkan data.
- Disini apabila kita menginputkan 'T' maka kita akan diminta untuk menginputkan beberapa data. Data yang kita inputkan akan masuk ke dictionary 'Data' yang telah dibuat tadi dengan data 'nama' sebagai keys dan sisanya sebagai values.
- Membuat syntax untuk mengubah data.
- Apabila kita menginput 'U' maka akan ada keterangan untuk mengubah data dan kita akan diminta untuk menginputkan nama yang mau diubah datanya, apabila nama tidak ada maka outputnya "Nama {} tidak ditemukan". Dimana {} adalah nama/data yang mau kita ubah.
- Membuat syntax untuk menghapus data.
- Apabila kita menginput 'H' maka kita akan diminta menginput nama yang akan dihapus. Jika nama ada di dalam dictionary, maka system akan menghapus keys/nama tersebut beserta valuesnya pada statement del Data[nama].
- Membuat syntax untuk mencari data.
- Apabila kita menginputkan 'C' maka kita akan diminta untuk memasukkan nama yang akan dicari. Apabila nama yang dicari ada di dalam dictionary maka outputnya akan menampilkan data dari nama tersebut.
- Membuat syntax untuk melihat atau menampilkan data.
- Apabila kita menginput 'l' maka sistem akan menampilkan data - data yang sudah kita masukkan. Jika kita belum memasukkan data maka outputnya menjadi "DATA TIDAK DITEMUKAN".
- Membuat syntax untuk menghentikan perulangan.
- Apabila kita menginput 'k' maka program akan langsung berhenti.
- Membuat syntax untuk apabila memilih pilihan yang tidak ada di menu.
- Jika kita menginputkan selain yang ada pada menu (T, U, H, C, L, K) maka kita akan diminta untuk memilih menu yang tersedia.




