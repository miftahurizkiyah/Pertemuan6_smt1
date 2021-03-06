# Pertemuan6_ Tugas Bahasa Pemrograman

Repository ini dibuat untuk memenuhi tugas bahasa pemrograman pertemuan 6. <br> <br>
***Nama : Miftahu Rizkiyah***

***NIM  : 312010014***

***Kelas : TI.20.B.1***

<br>

==========================

DAFTAR ISI <br>
| No | Description | Link |
| --- | ----- | -----|
| 1 | Tugas Pertemuan 5 | [Tugas_pertemuan5](#pertemuan-5---tugas-bahasa-pemrograman)
| 2 | Tugas Pertemuan 6 Lab 1| [Tugas_Part6_Lab1](#pertemuan-6---lab-1)
| 3 | Tugas pertemuan 6 Lab 1-2| [Tugas_Part6_Lab1-2](#pertemuan-6---lab-1-2)
| 4 | Tugas Pertemuan 6 Lab 2| [Tugas_part6_Lab2](#pertemuan-6---lab-2)
<br>


## Pertemuan 5 - Tugas Bahasa Pemrograman

Pada pertemuan 5 Bahasa Pemrograman saya diberikan tugas oleh dosen untuk membuat aplikasi biodata dengan python (seperti gambar dibawah ini)
![Tugas_5](pict/Tugas_Part5.PNG)<br>
saat ini saya akan menjelaskan hasil dari tugas tersebut.<br>
Berikut *source code* nya atau klik link berikut ( [Tugas_5 python](tugas_p5.py) ): <br>
``` python
print("Please enter full name : ")
fullname=input()

print("please insert your Nickname : ")
nickname=input()

print("please enter your NPM : ")
NPM=input()

print("please enter your Born place : ")
bornplace=input()

print("please insert your age : ")
age=input()

print("please enter your home address : ")
address=input()

print("please enter your phone number : ")
phonenumber=input()


print("\nAssalamualaikum Wr, Wb.")
print(f"\nLet me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM is {NPM}. I was Born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
print("\n")
```
Berikut penjelasannya :<br>
``` python
print("Please enter full name : ")
```
source code diatas berfungsi untuk mencetak hasil / output berupa "***Please enter full name :***" <br>
untuk menampilkan input string, saya menggunakan *tanda petik dua* didalam fungsi input(), sedangkan jika saya ingin menampilkan output/hasil berupa angka/interger saya tidak perlu menggunakan *tanda petik dua*. contohnya :
``` python
print("Nama saya adalah ...")
print(12345)
```
(Seperti gambar dibawah ini)

![Output fungsi print](pict/output_print.PNG)<br>
* untuk source code berikutnya adalah inputan atau membuat variable, seperti syntax dibawah ini :
``` python
fullname=input()
```
Ket : <br>
-Variable adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan yang berfungsi sebagai variable dalam source code diatas adalah ***fullname***.
-Fungsi **input()* adalah untuk memasukan nilai dari layar console di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol enter *(newline)*<br>


![input](pict/Input_Nama.PNG)<br>
Pada gambar diatas hasil dari inputan tersebut berwarna **hijau**<br><br>
-untuk memasukan perintah lain seperti **nick name, NPM, born place, age, home address, and phone number** mengikuti perintah yang sama seperti memasukan *fullname* <br>
<br>
* Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen,<br>
Output pertama yang diminta dosen adalah menampilkan salam, yaitu dengan mengetikan syntax/source code berikut :
``` python
print("\n\n Assalamu'alaikum")
```
Ket :
1. Fungsi ***\n*** pada source code diatas adalah untuk memberi baris baru / enter / *newline*
2. Fungsi print(), seperti dijelaskan pada point *Output* diatas
Hasil dari source code diatas adalah seperti gambar dibawah ini :
![Output_Salam](pict/Assalamu'alaikum.PNG)<br><br>
*Langkah terakhir adalah menampilkan dari semua inputan diatas. Dengan mengetikkan source code berikut : <br>
``` python
print("\nAssalamualaikum Wr, Wb.")
print(f"\nLet me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM is {NPM}. I was Born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
```

Ket :
1. Fungsi huruf ***f*** pada perintah **print(f"...")** adalah fungsi print yang dapat memudahkan programmer untuk mencetak statement dalam satu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan simbol koma ( , ) atau ( + )<br>
2. Sedangkan fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variable<br>
Hasil dari output tersebut adalah :
![Alloutput](pict/All_Output.PNG)

<br>
---
<br>

## Pertemuan 6 - Lab 1

Pada tugas pertemuan 6 - Lab 1 saya diberikan tugas oleh dosen untuk mempelajari OPerator Aritmatika menggunakan bahasa pemrograman python. Berikut source code yang diberikan oleh Dosen :
![Pertemuan6_Lab1](pict/Part6_Lab1.PNG)<br>
``` python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
Kali ini saya akan menjelaskan materi yang diberikan oleh Dosen.<br>

*Penggunaan End
Penggunaan End digunakan untuk menambahkan karakter yang dicetak diakhir baris. Secara default penggunaan End adalah untuk ganti baris
``` python
print('A', end='')
print('B', end='')
print('C', end='')
```

> Penggunaan print() digunakan untuk mencetak output, seperti syntax dibawah ini :
``` python
print()
```

> Syntax dibawah ini digunakan untuk output berupa string
``` python
print('X')
print('Y')
print('z')
```



Hasil dari source code tersebut adalah :<br>
![Output_End](pict/Part6_End.PNG)<br>

*Penggunaan Separator
Separator adalah pemisah yang befungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanpa spasi.<br>

>Pendeklarasian beberapa variable beserta nilainya
``` python
w, x, y, z = 10, 15, 20, 25
```
>Menampilkan hasil untuk tiap variable dengan menggunakan pemisah koma ( , )
``` python
print(w, x, y, z, sep=',')
```
>Menampilkan hasil untuk tiap variable tanpa menggunakan pemisah
``` python
print(w, x, y, z, sep='')
```
>Menampilkan hasil untuk tiap variable dengan menggunakan pemisah titik dua ( : )
``` python
print(w, x, y, z, sep=':')
```
>Menampilkan hasil untuk tiap variable dengan menggunakan pemisah strip/ dash ( ----- )
``` python
print(w, x, y, z, sep='-----')
```

Hasil dari syntax / source code diatas adalah :
![Output_Separator](pict/Part6_Separator.PNG)
<br>


## pertemuan 6 - Lab 1-2

*String format<br>
String formatting memungkinkan kita menyuntikan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.

Penggunaan source code yang diberikan oleh Dosen adalah :<br>
![Part6_Lab1_String_format](pict/Part6_string_format.PNG)<br>

``` python
#string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

print()
print()

#string format
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
```
<br>
Sekarang saya akan membahas satu persatu syntax yang telah diberikan oleh Dosen.<br>

1. String format 1<br>
Pada syntax / source code string format 1 akan menampilkan output 2 outputan.<br>
Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga angka 10, sedangkan untuk sebelah kanan akan menampilkan operasi Aritmatika Pangkat.<br>
Dengan ketentuan, Operasi pangkat dengan angka kiri sebagai pokok (Rumus : **[bintang dua] )<br>
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pagkat 10, dengan output sebagai berikut : <br>
![Operasi Aritmatika Pangkat](pict/Part6_Lab1-2.PNG) <br>


2. String format 2<br>
Pada syntax / source code string format 2 akan menampilkan output 2 output'an juga, (seperti string format 1, yaitu kanan dan kiri)<br>
Dengan ketentuan : <br>
> Aligment, padding, precesion dengan **format()** dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan atau kiri, parameter pembulatan dan banyak lagi. contoh lain seperti berikut :
``` python
print('{0:8} | {1:9}'.format('Buah'.'Jumlah'))
print('{0:8} | {1:9}'.format('Anggur'.3.))
print('{0:8} | {1:9}'.format('Apel'.10))
```

Hasil dari source code diatas adalah :
![Contoh_Aligment](pict/Contoh_1.PNG)
>Secara Default, ***.format()*** menggunakan rata text ke kiri, angka ke kanan. Kita dapat menggunakan opsi opsional <,^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam menggunakan ***.format()*** sebagai berikut : <br>
``` python
print('{:<40}{:^40}{:>40}'.format(Kiri','Tengah','Kanan''))
print('{:<40}{:^40}{:>40}'.format(15,45,55))
```

Hasil dari source code diatas akan muncul seperti : <br>
![Output_Aligment](pict/Contoh_2.PNG)
<br><br>
Untuk hasil dari string Format 2 adalah :<br>
![OUtput_String_Format_2](pict/Part6_string_format2.PNG)


<br><hr><br>

## Pertemuan 6 - Lab 2
* Konversi Nilai Variable<br>
Untuk pembahasan terakhir, akan menyelesaikan tugas lab 2 dari Dosen. yaitu Konversi Nilai Variable<br>
Tugas yang diberikan oleh dosen adalah seperti gambar dibawah ini :<br>
![Picture_Lab2](pict/part6_Lab2.PNG) <br>
``` python
a=(input("masukkan nilai a:"))
b=(input("masukkan nilai b:"))
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
<br>
saya menemukan error saat menjalankan source code tersebut, seperti gambar dibawah ini :<br>

![Error1_Lab2](pict/Error_Lab2.PNG)<br>
Kita akan membaca error yang telah terjadi.<br>
> ***TypeError: %d format: a number is required, not str*** <br>


Pada error tersebut terbaca bahwa variable a adalah string, yang seharusnya dibaca oleh system adalah number / interger.<br>
**Bagaimana cara kita memperbaiki error tersebut** <br>
Kita lihat pada baris ke 5 (di notifikasi terbaca bahwa error terletak pada baris ke 5), yaitu pada pemformatan **.format()** adalah interger, sedangkan jika berupa string maka akan ada tanda petik dua ("..") pada pemformatan **.format()** <br>
Kita akan fokus pada variable a dan b. <br>
Pada line 1 tertulis syntax : *a=input("Masukan Nilai A : ")* <br>
Sedangkan pada line 2 tertulis syntax : *b=input("Masukan Nilai B : )* <br>
Untuk membuat inputan berupa interger / angka harus ditambahkan syntax int() pada format input(). yang harus nya dituliskan adalah : <br>
``` python
a=int(input("masukkan nilai a:"))
b=int(input("masukkan nilai b:"))
```
<br>

Kita akan ulangi semua syntax pada file ini :

``` python
a=int(input("masukkan nilai a:"))
b=int(input("masukkan nilai b:"))
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
Kita akan coba **Run** kembali file tersebut, maka akan muncul seperti gambar dibawah ini : <br>
![Fixed_error_lab6](pict/Part6_Fixed_lab2.PNG)
<br><br>
<hr>
Setelah semua file berhasil disimpan dan dijalankan, maka selesai sudah Tugas Pertemuan 6 - Bahasa Pemrograman kali ini. <br>


### ========== THANK YOU ========== <br>
###  ***MIFTAHU RIZKIYAH / 312010014 / TI.20.B.1*** <br>
### ============================== <br>



 








