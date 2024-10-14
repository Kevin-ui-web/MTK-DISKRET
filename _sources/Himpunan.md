---
title: MAT DISKRET

---

## HIMPUNAN
### 1. Hukum De Morgan
Hukum De Morgan adalahh impunan dan logika yang menggambarkan hubungan antara operasi gabungan (∪) dan irisan (∩) dengan komplemen. Hukum ini digunakan untuk membalikkan pernyataan himpunan atau logika secara akurat. Berikut adalah bentuk dari kedua hukum De Morgan:

1. Hukum De Morgan untuk HimpunanJika A dan B  adalah dua himpunan, maka Hukum De Morgan menyatakan:

*Komplemen dari gabungan dua himpunan:
(A ∪ B)' = A' ∩ B'*

*Komplemen dari irisan dua himpunan:
(A ∩ B)' = A' ∪ B'*

2. Hukum De Morgan untuk Logika
Dalam konteks logika proposisional, Hukum De Morgan juga berlaku untuk operator logika. Jika  dan  adalah dua proposisi, maka:

Negasi dari disjungsi (OR) dua proposisi
Negasi dari konjungsi (AND) dua proposisi

Contoh Penerapan Hukum De Morgan
1. Contoh Himpunan:
Misalkan:
A = {1, 2, 3}
B = {3, 4, 5}
Semesta S = {1, 2, 3, 4, 5, 6}
Maka:
A ∪ B = {1, 2, 3, 4, 5}
A' = {4, 5, 6}
B' = {1, 2, 6}
(A ∪ B)' = {6} = A' ∩ B'
Jadi, hukum De Morgan terbukti pada operasi himpunan ini.

2. Contoh Logika:
Jika P: "Saya belajar" dan Q: "Saya bekerja".
Maka:
 berarti "Saya tidak belajar dan tidak bekerja".
 berarti "Saya tidak belajar atau tidak bekerja (salah satu atau keduanya)".
 
 
### 2. Hukum Absorpsi (Absorption Laws)

Hukum Absorpsi dalam aljabar himpunan dan logika merupakan hukum yang menunjukkan bagaimana operasi gabungan (∪) dan irisan (∩) berinteraksi dengan himpunan itu sendiri. Hukum ini memungkinkan penyederhanaan ekspresi himpunan atau logika.

1. Hukum Absorpsi dalam Himpunan

Jika A dan B adalah dua himpunan, maka Hukum Absorpsi dinyatakan sebagai berikut:

Gabungan dengan irisan:


A ∪ (A ∩ B) = A

Irisan dengan gabungan:


A ∩ (A ∪ B) = A

2. Hukum Absorpsi dalam Logika

Dalam konteks logika proposisional, Hukum Absorpsi juga berlaku untuk operator logika "OR" (atau, ∨) dan "AND" (dan, ∧). Jika  dan  adalah dua proposisi, maka Hukum Absorpsi menyatakan:

Disjungsi (OR) dengan konjungsi (AND)

Konjungsi (AND) dengan disjungsi (OR)

Contoh Penerapan Hukum Absorpsi

1. Contoh Himpunan:
Misalkan:

A = {1, 2, 3}

B = {3, 4, 5}


Maka:

A ∩ B = {3}

A ∪ (A ∩ B) = {1, 2, 3} = A

A ∩ (A ∪ B) = {1, 2, 3} = A



2. Contoh Logika:
Jika P: "Saya belajar" dan Q: "Saya bekerja".
Maka:
= "Saya belajar atau (Saya belajar dan bekerja)" yang akan selalu menghasilkan "Saya belajar".
= "Saya belajar dan (Saya belajar atau bekerja)" yang akan selalu menghasilkan "Saya belajar".


### 2. Hukum Absorpsi (Absorption Laws)
Hukum Absorpsi dalam aljabar himpunan dan logika merupakan hukum yang menunjukkan bagaimana operasi gabungan (∪) dan irisan (∩) berinteraksi dengan himpunan itu sendiri. Hukum ini memungkinkan penyederhanaan ekspresi himpunan atau logika.

1. Hukum Absorpsi dalam Himpunan
Jika A dan B adalah dua himpunan, maka Hukum Absorpsi dinyatakan sebagai berikut:

Gabungan dengan irisan:
A ∪ (A ∩ B) = A

Irisan dengan gabungan:
A ∩ (A ∪ B) = A


### 3. Complement laws
Hukum komplemen (complement laws) adalah prinsip dasar dalam aljabar Boolean yang digunakan dalam logika digital, ilmu komputer, dan teori himpunan. Hukum ini melibatkan operasi dengan variabel logika seperti konjungsi (AND), disjungsi (OR), dan negasi (NOT).

Dalam hukum komplemen, ada dua aturan utama:

1. A ∨ A' = 1
Artinya, hasil operasi OR antara suatu variabel Boolean (A) dengan komplemennya (A') adalah 1 (benar). Ini mencerminkan bahwa salah satu dari A atau komplemennya pasti benar.


2. A ∧ A' = 0
Artinya, hasil operasi AND antara suatu variabel Boolean (A) dengan komplemennya (A') adalah 0 (salah). Ini mencerminkan bahwa A dan komplemennya tidak bisa benar bersamaan.