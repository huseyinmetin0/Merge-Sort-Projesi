# Merge-Sort-Projesi

Merhaba. [Patika.dev](https://www.patika.dev/tr)'in Veri Yapıları ve Algoritmalar dersinin proje 2 ödevini tamamladım.

## [16,21,11,8,12,22] -> Merge Sort

#### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Cevap; [16,21,11,8,12,22]

Diziyi ikiye bölerek yeniden yazıyoruz ve bu işlemi tek eleman kalana kadar devam ettiriyoruz.

    [16,21,11]            [8,12,22] 

    [16,21] [11]          [8] [12,22]
   
    [16] [21] [11]        [8] [12] [22]
   
Tek elemanlı dizileri küçükten büyüğe sıralancak şekilde ikili ikili birleştirerek nihai sıralamaya getiriyoruz.
Küçükten büyüğe sıralama yaparken sol taraftaki dizinin 1. elemanıyla sağ taraftaki dizinin 1. elemanını karşılaştırarak başlıyoruz.
Daha sonra bu şekilde 2. ve 3. elemanları karşılaştırıyoruz.


    [16,21] [11]          [8,12] [22]

    [11,16,21]            [8,12,22]
    
    [8,11,12,16,21,22]
    
#### 2. Big-O gösterimini yazınız.

Dizide sürekli 2'ye bölünerek işlem yapılmıştır.
Her bölünmüş dizide n eleman olduğu için n işlem yapılmıştır.

Big O gösterimi => O(n*logn) olacaktır.






