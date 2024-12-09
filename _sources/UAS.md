---
title: UAS

---

# UAS

## 1.
$$\begin{array}{c|c|c|c|cc}P&Q&R&S\ &P\to\ Q&R->S \\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{F}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{T}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\end{array}$$


## 2. MELIHAT DARI JARAK 

MELIHAT DARI A-B (dalam bentuk tabel)

| a->b = 1 | melewati a,b | 
| -------- | ----------   | 
| a->c = 1 | melewati a,c  |
| a->d = 1  | melewati a,d |  |
| a->e = 2     | melewati (a,b,e)/(a,c,e)   |
| a->f = 2   | melewati (a,c,f)/(a,d,f)  |

soal:
- Hitunglah beetwenes central B
- Hitunglah closemen centrality F

jawab:
#### closeness centrality B  =(jumlah node -1)/(total jarak terpendek dalam setiap node)
#### betwenes centralitiy B = (jumlah kontribusi B)/(total jalur terpendek)

- jumlah node pada graph adalah(a,b,c,d,e,f)=6
total keseluruhan jarak terpendek pada setiap node adalah:
a->b=1
c->b=2
d->b=2
e->b=1
f->b=2
total keselurahan jarak terpendek antar not ke b=8

maka sesuai rumus:
closeness centrality B  =(jumlah node -1)/(total jarak terpendek dalam setiap node)
closeness centrality B  =(6-1)/(8)
closeness centrality B  =5/8

jadi closenes centrality B=5/8


- Hitunglah beetwenes central B

jarak terpendek yang melibatkan b hanya 1 yakni a->e
selain itu tidak melibatakan b.
kontribusi b dalam a->e = 1 dari 2 jalur terpendek.

 betwenes centralitiy B = (jumlah kontribusi B)/(total jalur terpendek)
 betwenes centralitiy B = (1)/(2)
 betwenes centralitiy B = 0,5
 
 jadi betwenes centrality B adalah 0,5
   












