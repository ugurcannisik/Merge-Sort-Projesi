[Patika.dev](https://www.patika.dev/tr)


## [16,21,11,8,12,22] -> Merge Sort

##  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
     - [16,21,11,8,12,22] Yapı ikiye bölünür.
     -   [16,21,11]               [8,12,22]        Tekrar bölüyoruz
     -  [16]    [21,11]         [8]    [12,22]     Tek eleman kalması için tekrar bölüyoruz.
     -  [16]   [21] [11]        [8]   [12] [22]    Bu yapıyı tekrar kademeli olarak birleştiriyoruz. Birleştirirken sıralama yapıyoruz.
     -  [16]    [11,21]         [8]    [12,22]     Bu diziyi tekrar sıralı olarak birleştiriyoruz.
     -    [11,16,21]              [8,12,22]        Son birleştirme işlemini gerçekleştiriyoruz.
     -           [8,11,12,16,21,22]
     
##  Big-O gösterimini yazınız.
     -O(nlogn)
