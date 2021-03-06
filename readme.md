# Basic Pemrograman python
 Python adalah salah satu bahasa pemrograman yang baru - baru ini menjadi populer dikalangan developer. Python memliki kemudahan dalam pembacaan algoritma, karena code yang dipakai lebih simple

## contoh output "Hello World" dalam python dan java
- Python
```
print("Hello World")
```

- Java
```
System.out.println("Hello World");
```
Dalam hal perbandingan ini diketahui bahwa code bahsa python lebih sederhana dibanding code bahasa java.

## 1. Tipe Data
Tipe data dalam bahasa python tidak perlu mendeklarasikan tipe datanya terlebih dahulu, akan tetapi bisa langsung dengan variable yang dipakai, contoh :
```
print(1) 
print("Ini tipe data string")
print(bool(10>9))
print(12.3)
```
### Output
```
1
Ini tipe data string
True
12.3
```
### Bedah Code
```
a = 1
```
- ini adalah variable yang memakai type data Integer
```
b = "Ini tipe data string"
```
- Ini adalah type data yang menggunakan type data String
```
c = bool(10>9)
```
- Ini adalah type data boolean yang akan menghasilkan output True/False atau bisa dikatakan juga hasilnya dapat berupa "1" (True) dan "0" (False).
```
d = 12.3
```
- Ini adalah type data float di python

Dalam python, kita tidak perlu mendeklarasikan type data pada variabel tertentu, contoh :
```
a = 1
b = "String"
c = 1.0
d = True
```

## 2. Mengambil Input Data
Digunakan untuk mengambil suatu nilai atau value dari user dan disimpan dalam suatu variabel yang nantinya digunakan untuk kebutuhan program, contoh :

- Mengambil input berupa String
```
data = input("Masukkan string\t: ")
```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"\t" digunakan untuk memberikan satu tab
- Mengambil input berupa integer
```
data = int(input("Masukkan integer\t: ))
```
## 3. If Elif Else Statement
Ini digunakan untuk mempertimbangkan suatu kondisi yang terjadi dalam suatu kasus tertentu, contoh :
```
a = satu

if(a == "satu"):
    print(1)
elif(a == "dua"):
    print(2)
else:
    print("Error")
```
### Output
```
1
```
### Bedah Code
```
if(a == "satu"):
    print(1)
```
Statement if digunakan untuk memenuhi kondisi pertama, yaitu ketika variabel a bernilai 1, maka akan menghasilkan output 1. Akan tetapi, jika kondisi if ini tidak terpenuhi, maka akan masuk ke kondisi selanjutnya, yaitu :
```
elif(a == "dua"):
    print(2)
```
Seperti halnya if, elif juga memiliki kondisi yang setidaknya harus terpenuhi, yaitu a == "dua". Apabila kondisi tidak terpenuhi kembali, maka pasti akan terpilih kondisi terakhir, yaitu :
```
else:
    print("Error")
```

## 4. Perulangan
Perulangan digunakan untuk mengulang suatu nilai dalam kondisi tertentu baik terurut ataupun mengulang nilai yang sama.
## Perulangan For
```
for i in range(1, 10, 1):
    print(i)
```
### Output
```
0
1
2
3
4
5
6
7
8
9
```
Contoh menggunakan nilai dalam suatu list
```
list = [1,2,3,4,5,6]

for i in list:
    print(i)
```
### Output
```
1
2
3
4
5
6
```
### Bedah Code
Bentuk umum
```
for i in range(perulangan awal, panjang perulangan, selisih):
    print(i)
```
&nbsp;&nbsp;"i" digunakan untuk menampung nilai

Jika dilihat dari contoh,
```
for i in range(1, 10, 1):
    print(i)
```
Maka, perulangan tersebut mempunyai angka awal: 1, panjang perulangan: 10, dan selisih: 1.

## Perulangan While
```
i = 1
while i < 10:
  print(i)
  i += 1
```
### Output
```
1
2
3
4
5
6
7
8
9
```
### Bedah Code
Variabel ini digunakan untuk memulai perulangan (angka awal)
```
i = 1
```
Ini adalah bagian panjang perulangannya, bisa disesuaikan dengan kebutuhan
```
while i < 10:
```
Ini digunakan untuk selisihnya
```
i += 1
```
Bisa juga diganti dengan ini
```
i = i + 1
```

