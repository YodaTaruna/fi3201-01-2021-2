# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10298345'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
```python
Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined
```
Proof at OneCompiler [3xrun7udf](https://onecompiler.com/python/3xrun7udf) 


## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
```python
Output:

1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
3:◻◻◻
1:◻
```
Proof at OneCompiler [3xry4mxzj](https://onecompiler.com/python/3xry4mxzj)

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
```pyhton
Output:

1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
3:◼◼◼
1:◼
```
Proof at OneCompiler [3xry4y2j9](https://onecompiler.com/python/3xry4y2j9)
## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ Mengimport chart dari html dengan char1 kotak kosong dan char2 kotak hitam
+ NIM pada kode tersebut diimplentasikan char1 atau char 2 dengan bantuan 's' agar jumlah kotak akan terus bertambah sampai dengan angka pada NIM
