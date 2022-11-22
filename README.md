# Praktikum 5 Pertemuan ke 10

|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|Muhammad Ikhsan Fakhrudin|312210019|TI.22.A2|Pemrograman|

# Latihan 1

![gambar](screenshot/ss10.png)

Tulis Kode Program Seperti Berikut Ini :

![gambar 1](screenshot/ss1.png)

![gambar 2](screenshot/ss2.png)

# Output

Maka Hasil Kode Program Di Atas Akan Seperti Ini :

![gambar 3](screenshot/ss3.png)

# Tugas Praktikum 5

![gambar](screenshot/ss11.png)

# Kode Program

tulis kode program seperti berikut ini :

![gambar 4](screenshot/ss4.png)

![gambar 5](screenshot/ss5.png)

# Penjelasan

1. Membuat Dictonary Kosong yang akan Di Input Dengan Data.

```apa
data={}
```

2. Membuat Perulangan dengan While yang terdapat pada Menu untuk Menjalankan Program.

```
while True:
    print()
    a=input("[(L)ihat, (T)ambah, (U)bah, (H)apus, (C)ari, (K)eluar] :")
    print()
```

3. Menambahkan Data Yang Dibutuhkan Seperti Data Nim, Nama, Nilai Tugas, Uts, dan Uas. Data yang Di Input akan Masuk ke Dalam Dictonary Data dengan Nim sebagai keys sedangkan nama, tugas, uts dan uas sebagai Values.

```
if a=="t" or a=="T":
        print("TAMBAH DATA")
        print("-----------")
        nim=int(input("NIM\t: "))
        nama=input("Nama\t: ")
        tugas=int(input("Tugas\t: ")) 
        uts=int(input("UTS\t: "))
        uas=int(input("UAS\t: "))
        akhir=(int(tugas)*30/100)+(int(uts)*35/100)+(int(uas)*35/100)
        data[nim]=nama, tugas, uts, uas, akhir
        print()
```        



