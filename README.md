## Saya Jidan Abdurahman Aufan NIM [2205422] mengerjakan soal Latihan Praktikum-5 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin 

### Mengimplementasi Kode yang ada di Modul Praktikum, menambahkan attribut 'Fakultas', dan menambahkan pertanyaan konfirmasi penghapusan data.

#### Setelah mengimplementasikan kode sesuai yang ada di Modul Praktikum, untuk menambah attribut 'Fakultas' langkah langkahnya adalah sebagai berikut:

1. Menambahkan attribut fakultas di Mahasiswa.java dengan getter dan setternya juga
   ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/29aed953-bcfd-46eb-9a95-2c25cc0244b7)

2. Menambahkan JLabel dan JComboBox di Menu.form
   ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/05d16266-bdec-427d-8e54-df2004034321)
   fieldname JComboBox diubah menjadi fakultasComboBox

3. Mengatur isi pilihan ComboBox fakultas
   ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/5afe478c-ec0e-49e6-9f5d-dce92b641ef9)

4. Modifikasi mouselistener agar mengambil attribut fakultas dari data yang dipilih
   ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/9a67f0d0-fec9-4f2b-96c7-29d28582af0a)

5. Modifikasi DefaultTableModel menambah kolom fakultas
   ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/1ca57cd7-06a0-4db4-a3b9-5db6d9bb2a75)

6. Modifikasi fungsi - fungsi manipulasi data agar attribut fakultas ikut diproses
   - Insert Data
     ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/e1d5c7d5-6d38-489e-9a36-f0d39c5e1140)

   - Update Data
     ![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/9695beca-4336-486d-aa6c-35437a50a6de)

Berikut hasil tampilan yang diperoleh: 
![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/b2473168-7195-43bd-a7ed-a1985780fd4c)

##### Mengimplementasikan Konfirmasi Delete Data

Untuk menambahkan popup konfirmasi delete data cukup sederhana, cukup menambahkan confirm dialog saat event menekan tombol delete, dan mengecek pilihan user
![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/8e6a9bd0-ef22-4e46-95fb-fae1e4c19cc7)
![image](https://github.com/jidanSyn/LP5DPBO2024C2/assets/114399924/4f17df28-3379-49cd-95d8-b9da07445d9e)


