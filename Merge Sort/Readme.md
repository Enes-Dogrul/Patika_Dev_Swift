# Veri-yapilari-ve-algoritmalar
[Patika.dev](http://patika.dev "Patika.dev")
## Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
------------
| Steps  |Merge   |
| ------------ | ------------ |
|  Diziyi 2 parçaya ayırırız |  [16,21,11] - [8,12,22]  |
|  Bölünmüş Dizileri Tekrardan 2 Parçaya Ayırırız | [16,21] [11] - [8,12] [22]   |
|  Bölünen Dizilerde 2 Eleman veya az eleman varsa Dizi Bölme işlemini Durdururuz |  [16,21] [11] - [8,12] [22]  |
|  İkili Olarak Birleştirme işlemine başlarız | [11,16,21] - [8,12,22]  |
| Kendi Aralarında Büyüklük Küçüklük Karşılaştırmasını yaparız ve Birleştiririz|[8,11,16,21,22] |
ve İşlemimiz Bitmiş Olur.
## Big-O gösterimini yazınız.
O(nlogn)
