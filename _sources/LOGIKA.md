---
title: LOGIKA MATEMATIKA

---

### NEGASI
Negasi adalah operasi logika dimana operasi membalikkan suatu nilai kebenaran dari pernyataan/variabel dengan kata lain negasi adalah penyangkalan daeri pernyataan awal. Negasi dinyatakan dengan simbol NOT. Jika sebuah pernyataan bernilai benar (true), maka negasinya akan bernilai salah (false), dan sebaliknya.

\begin{array}{c|c|c}
P & NOT \\
\hline
\text{T} & \text{F}  \\
\text{F} & \text{T}  \\
\end{array}






contoh: 

Pernyataan asli: "Hari ini hujan." 
Negasi: "Hari ini tidak hujan."

Dalam logika simbolik, jika sebuah pernyataan dilambangkan dengan P, negasinya dilambangkan dengan -P . Contohnya, jika  adalah "Hari ini cerah," maka -P adalah "Hari ini tidak cerah."

### konjungsi
Konjungsi adalah operasi menggabungkan dua pernyataan dengan menggunakan kata dan, hasilnya akan benar hanya jika kedua pernyataan yang digabungkan juga benar. Dalam logika simbolik, konjungsi dilambangkan dengan simbol ∧.

\begin{array}{c|c|c}
P & Q & P \ ∧\ Q \\
\hline
\text{T} & \text{T} & \text{T} \\
\text{T} & \text{F} & \text{F} \\
\text{F} & \text{T} & \text{F} \\
\text{F} & \text{F} & \text{F} \\
\end{array}

Berikut adalah contoh konjungsi:

P: "Saya pergi ke sekolah." 
Q: "Saya membawa buku." 
Konjungsi: "Saya pergi ke sekolah dan saya membawa buku."

Konjungsi ini akan benar jika kedua pernyataan, yaitu "Saya pergi ke sekolah" dan "Saya membawa buku," benar atau p ∧ q. Jika salah satu atau kedua pernyataan itu salah, konjungsi akan menjadi salah.


### Disjungsi
Disjungsi adalah operasi logika yang menghubungkan dua pernyataan dengan kata "atau" atau "or". Dalam logika, disjungsi dinyatakan benar jika salah satu atau kedua pernyataan yang digabungkan benar. Disjungsi hanya salah jika kedua pernyataan itu salah. Disjungsi dilambangkan dengan simbol v .


\begin{array}{c|c|c}
P & Q & P \ v  \ Q \\
\hline
\text{T} & \text{T} & \text{T} \\
\text{T} & \text{F} & \text{T} \\
\text{F} & \text{T} & \text{T} \\
\text{F} & \text{F} & \text{F} \\
\end{array}


Contoh disjungsi:
Pernyataan 1: "Hari ini hujan." Pernyataan 2: "Saya pergi bermain." Disjungsi: "Hari ini hujan atau saya pergi bermain."

Secara simbolik, jika  adalah "Hari ini hujan" dan  adalah "Saya pergi bermain," disjungsi ditulis sebagai P v Q.

### implikasi
Implikasi adalah hubungan logika antara dua pernyataan, di mana satu pernyataan menjadi akibat dari yang lain. Implikasi dilambangkan dengan simbol .
Implikasi hanya salah jika premisnya benar tetapi konsekuennya salah. Jika premisnya salah, implikasinya selalu benar, terlepas dari konsekuennya.


\begin{array}{c|c|c}
P & Q & P \ -> Q \\
\hline
\text{T} & \text{T} & \text{T} \\
\text{T} & \text{F} & \text{F} \\
\text{F} & \text{T} & \text{T} \\
\text{F} & \text{F} & \text{T} \\
\end{array}

Contoh implikasi:

Pernyataan 1 (Premis): "Jika saya belajar keras." 
Pernyataan 2 (Konsekuen): "Saya akan lulus ujian."
Implikasi: "Jika saya belajar keras, maka saya akan lulus ujian."

Dalam logika simbolik, jika  adalah "Saya belajar keras" dan  adalah "Saya lulus ujian," maka implikasi ditulis sebagai .

### Biimplikasi

Biimplikasi adalah hubungan logika di mana dua pernyataan saling bergantung, yaitu keduanya benar atau keduanya salah. Dalam notasi logika, biimplikasi ditulis sebagai , yang berarti "P jika dan hanya jika Q." Dengan kata lain,  hanya benar jika  dan  memiliki nilai kebenaran yang sama.

Tabel kebenaran untuk biimplikasi  adalah sebagai berikut:

\begin{array}{c|c|c}
P & Q & P \leftrightarrow Q \\
\hline
\text{T} & \text{T} & \text{T} \\
\text{T} & \text{F} & \text{F} \\
\text{F} & \text{T} & \text{F} \\
\text{F} & \text{F} & \text{T} \\
\end{array}




Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\end{array}$$





