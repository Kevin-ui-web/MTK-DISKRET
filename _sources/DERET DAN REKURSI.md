---
title: DERET DAN REKURSI

---

Deretan (sequence) 
Deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu
Definisi: Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.

   N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb

Notasi deretan: {an}


Deretan umumnya dinyatakan dalam suatu formula, misalnya:
an = 2n
an = 1/n
an = 7 – 3n


Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
Deretan bilangan ganjil: 1,3,5,7,…
Deretan bilangan genap: 2,4,6,8,…
Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....


String adalah deretan berhingga karakter berbentuk
a1a2a3a4…an

    Panjang string S adalah jumlah karakter di dalam string tersebut
     
    Contoh:  informatika adalah string dengan panjang 11 karakter
         10100101 adalah string biner dengan panjang 8 bit

String kosong dilambangkan dengan , panjangnya = 0
9
Penjumlahan deretan 
10
11

Beberapa sumasi sudah ditemukan rumus penjumlahannya sebagai berikut:
![](https://cdn.mathpix.com/snip/images/Fi_Q4jzsZ9TiUX9vYJ3UCTXVI9vm89z3r0tgvE3SBmM.original.fullsize.png)


12
(deret geometri)
(deret aritmetika)
13
=
Sumasi ganda
14
Contoh penggunaan: Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 
15
x = 0
for j = 1 to 10 do
    for k = 1 to j do
           x = x + 2
   end for
end for 
16
Rekursi
Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

Perhatikan tiga buah gambar pada tiga slide berikut ini.


17
Objek fraktal  adalah contoh bentuk rekursif.
18
Fungsi Rekursif
Fungsi rekursif didefinisikan oleh dua bagian:
(i)  Basis 
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).

 (ii)  Rekurens
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

19
Contoh 6:  Misalkan f didefinsikan secara rekusif sbb


           
        Tentukan nilai f(4)!

Solusi:      f(4) = 2f(3) + 4` `
=  2(2f(2) + 4) + 4
=  2(2(2f(1) + 4) + 4) + 4
=  2(2(2(2f(0) + 4) + 4) + 4) + 4
=  2(2(2(23 + 4) + 4) + 4) + 4
=  2(2(2(10) + 4) + 4) + 4
=  2(2(24) + 4) + 4
=  2(52) + 4
= 108

20
basis
rekurens
Cara lain menghitungnya:
f(0) = 3
f(1) = 2f(0) + 4 = 2  3 + 4 = 10
f(2) = 2f(1) + 4 = 2  10 + 4 = 24
f(3) = 2f(2) + 4 = 2  24 + 4 = 52
f(4) = 2f(3) + 4 = 2  52 + 4 = 108

Jadi, f(4) = 108.
21
Contoh 7: Nyatakan n! dalam definisi rekursif

Solusi:

       Misalkan f(n) = n!, maka  




Menghitung 5! secara rekursif adalah:
         5! = 5  4! = 5  4  3! = 5  4  3  2! 
= 5  4  3  2  1! = 5  4  3  2  1  0!=  5  4  3  2  1  1 = 120
22
Algoritma menghitung faktorial:

function Faktorial (input  n :integer)integer
{ mengembalikan nilai n!;
  basis   : jika n = 0, maka 0! = 1
  rekurens: jika n > 0, maka n! = n  (n-1)!
}
DEKLARASI
      -
ALGORITMA:
    if n = 0 then
       return 1              { basis }
    else
       return  n * Faktorial(n – 1){ rekurens }
    end


Struktur Rekursif
Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 
![](https://cdn.mathpix.com/snip/images/lzDKlLmiKs7QerlZ3Uyq1jwJ5k-X_6PEQ6vnfDURT4c.original.fullsize.png)

Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.

Jumlah anak pada setiap simpul bisa 1, 2, atau 0.

Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)

Simpul yang tidak mempunyai anak disebut simpul daun (leave).


Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut  upapohon (subtree).

Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:
![](https://cdn.mathpix.com/snip/images/yIGKVI7iDaCYxae0Py-_MUOz4Nc2zUgYZz6Wg9hZt2o.original.fullsize.png)

(i) Basis: kosong adalah pohon biner
(ii) Rekurens: Jika T1 dan T2 adalah pohon biner, maka                        
          adalah pohon biner
                    T1       T2 
                       
Proses pembentukan pohon biner secara rekursif:
(i)                 
(ii)
![](https://cdn.mathpix.com/snip/images/XRbrGBAatuPFFPqsDj6Cs8KnJlVin897VGSTI428C3U.original.fullsize.png)