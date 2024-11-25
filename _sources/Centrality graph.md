---
title: Centrality graph

---



## Social Network Analysis
![Picture1](https://hackmd.io/_uploads/HJQv_IdM1e.png)

merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut
![Picture2](https://hackmd.io/_uploads/r1NdOUdfke.png)

terdapat node yang mewakili 
orang atau individu atau aktor. 
Relasi  antar objek  dapat dinyatakan dengan link 
atau edges yang terjadi antara aktor tersebut 
Social network terdiri dari banyak aktor 
yang mempunyai relasi satu sama lain hingga
membentuk peta jaringan sosial yang dinyatakan dengan 
graph

### Tidak semua node dalam jaringan adalah penting  (aktor)
### Mencari node yang paling penting dalam suatu jaringan
### Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, 
- degree centrality, 
- betweeness centrality, 
- closeness centrality 
- eigenvector centrality

# Betweenness Centrality

- Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 

- Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan

- Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas

- Menghitung jumlah lintasan terpendek yang melewati suatu node
- Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi
= Betweenness Centrality