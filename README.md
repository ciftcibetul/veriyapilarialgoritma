o	   [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

CEVAP: 
2 dizinin en küçük sayısıdır, en başa eklemek için 22 ile yer değiştirir. [2,27,16,22,18,6]
2'den sonra en küçük sayı 6'dır, 27 ile yer değiştirir.[2,6,16,22,18,27]
16 üçüncü küçük sayıdır ve 3.sırada olduğu için yer değiştirmez.[2,6,16,22,18,27]
Diğer küçük sayı 18'dir 22 ile yer değiştirir ve sonucunda sıralama doğru olduğu için işlem sonlanır.[2,6,16,18,22,27]


o	Big-O gösterimini yazınız.

CEVAP:
[22,27,16,2,18,6] dizisinde 6 eleman vardır bu da 6 kez işlem yapılacak demektir.
Big-O yöntemine göre sıralama yapılırken işlem sayısı da n olur. Son işlem sayısı 1 olana kadar devam eder.
•	n-> 6 tane işlem,
•	En küçük elemanı (birinci elemanı) bulmak için (n-1)-> 6-1=5 tane işlem,
•	İkinci elemanı bulmak için (n-2)-> 6-2=4 tane işlem,
•	 Üçüncü elemanı bulmak için (n-3)-> 6-3=3 tane işlem,
•	 Dördüncü elemanı bulmak için (n-4)-> 6-4=2 tane işlem yapılır.
•	Altı elemanlı dizi olduğu için daha fazla işlem yapılmasına gerek yoktur çünkü son eleman altıncı elemandır.
•	Bu algoritmada n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapılır. 
•	Bu işlemin formülü: [n(n+1)]/2'dir. Bu formül sadeleştirilerek: (n²+n)/2 elde edilir.
•	Big-O Notation'da kat sayı önemsizdir; yani domine eden fonksiyon n² alınır.
•	Big-O değeri = O(n²)


o	Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

[2,6,16,18,22,27] sonucunda “18” ortada kaldığı için Average Case’e girer.

o	[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
En küçük olan 2’dir 7 ile yerini değiştiriyoruz.
2,3,5,8,7,9,4,15,6
2,3,4,8,7,9,5,15,6
2,3,4,5,7,9,8,15,6
2,3,4,5,6,9,8,15,7







































