# Merge-Sort-Projesi
Verilen dizimi merge sort ile detaylandırarak çözümlediğimiz Veri Yapıları ve Algoritmalar dersinin ikinci projesidir.
# Proje 2

## [16,21,11,8,12,22] -> Merge Sort türüne göre aşamalarını yazınız.

*Merge sort, sıralamak istediğimiz eleman dizisini bölerek çözdüğümüz bir algoritmadır. Her seferinde sorunu 2'ye bölüyoruz, ta ki tek eleman kalana kadar. Sonrasında, problemi çözerek, yani kendi içerisinde sıralayarak birleştiriyoruz.*

[16,21,11,8,12,22]

 [16,21,11]           [8,12,22]
 [16]  [21,11]       [8]  [12,22]
[16]  [21]  [11]    [8] [12]  [22]
[16]  [11,21]       [8] [12,22]
[11,16,21]          [8,12,22]
[8,11,12,16,21,22] dizimin son hali olacaktır.

## Big-O gösterimini yazınız.

Öncelikle elimizdeki diziyi eleman sayısına kadar böldük; yani n sayıya bölmüş olduk. Elimizdeki her diziyi de 2'ye böldük; yani 2^x= n --> x=logn
