# Veri-yapilari-ve-algoritmalar
[Patika.dev](http://www.patika.dev "Patika.dev")
## Insertion Sort Projesi-Patika.dev
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. Big-O gösterimini yazınız.
1. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
1. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
1. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

------------
Insertion Sort Asamalari
------------
1. Aşama [22,27,16,2,18,6]
2. Aşama [22,27,16,2,18,6]
3. Aşama [16,22,27,2,18,6]
4. Aşama [2,16,22,27,18,6]
5. Aşama [2,16,18,22,27,6]
6. Aşama [2,6,16,18,22,27]

------------
Big-O Gösterimi
------------
worst case durumu : n+(n-1)+(n-2)....+1 =n*(n+1)/2 = (n^2+n)/2 = O(n^2)

------------
Time Complexity
------------
Best Case : [2,6,16,18,22,27]
Worst Case : [27,22,18,16,6,2]

------------
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
------------
Son Hali : [2,6,16,18,22,27], 18 Sayısı Ortadadır. "Average Case"

------------
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
------------
1. Aşama [3,7,5,8,2,9,4,15,6]
2. Aşama [3,5,7,8,2,9,4,15,6]
3. Aşama [2,3,5,7,8,9,4,15,6]
4. Aşama [2,3,4,5,7,8,9,15,6]

------------
