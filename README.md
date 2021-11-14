# labspy01
## Latihan 1

Program Sederhana Menampilkan Blangan Terbesar </p>

![img 1](screenshot/1.png)

Penjelasan :

    1. Buatlah integer untuk menginput bilangan bulat untuk di proses dan dimasukan ke variabel maks

````
a = int(input("Masukan Nilai 1 : "))
b = int(input("Masukan Nilai 2 : "))
````
Proses : 
    2. jika (if) bilangan a lebih besar dari biangan b maka bilangan a lebih besar
````
if a > b:
    makx = a
````
    3. jika (if) bilangan b lebih besar dari bilangan a maka bilangan b lebih besar
````
else:
    makx = b
````
    4. Untuk menampilkan hasil
````
print ("Bilangan terbesar Adalah : ",makx)
````

## Latihan 2

Program Menampilkan Sebuah Bilangan Dari Bilangan Terkecil ke Bilangan Terbesar

![Img 2](screenshot/2.png)

Penjelasan :

    1. Untuk menginput lima buah bilangan yang akan dimasukan ke list variabel 
````
bilangan = []
for i in range(1,6):
    bilangan.append(int(input("Masukan Bilangan : ")))
````

    2. Data akan diproses menggunakan metode sort. yaitu metode untuk mengurutkan data, baik itu dari nilai terkecil ataupun terbesar.
````
bilangan.sort()
````
    3. Untuk Menapilkan Data
````
print("Urutan Bilangan",bilangan)
````
SELESAi

## Latihan 3

Program Perulangan Bertingkat (Nested for)

![Img 3](screenshoot/3.png)

Penjelasan :
Note : i (Baris), j (Kolom)

    1. Untuk melakukan perulangan baris dan kolom dengan nilai 10, menggunakan nested for

````
for i in range (10):
    for j in range (10):
        
````
    2. Untuk hasil dari perulangan
````
print ('%3d'%(i+j), end = '')
    print()
````

## Latihan 4

Program Menampilkan N Bilangan Acak yang Lebih Kecil dari 0.5

![IMG 4](screenshot/4.png)

Penjelasan :

    1. Import Module Bilangan Random

````
from random import random
```` 

    2. Untuk menginput nilai yang ingin dikonversikan kedalam bilangan bulat (Integer) yang akan di masukan kedalam variabel a

````
a = int(input("Masukan Bialngan : "))
````
    3. Untuk pengulangan range yang diinputkan oleh variable a
````
while a==a:
    break
for i in range(a):
    bil = random()%0.5
````

    4. Untuk Menampilkan bialangan a

````
 print ("Perulangan ke- :", bil)
print ("Selesai")
````