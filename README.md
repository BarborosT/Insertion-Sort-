# Insertion-Sort-project

https://app.patika.dev/barborost

Insertion-Sort projesi sorularının cevapları

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Cevap:

[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27] n-2

[2,6,16,18,22,27] 1


2.Big-O gösterimini yazınız.

Cevap:

 (n.(n+1))/2
 
 (n^2+n)/2
 
 O(n^2)
 
 
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.



Cevap:


Average case: Aradığımız sayının ortada olması 18 = [2,6,16,18,22,27]

Worst case: Aradığımız sayının sonda olması 2 = [22,27,16,2,18,6]

Best case: Aradığımız sayının dizinin en başında olması = [2,6,16,18,22,27]





4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[2,6,16,18,22,27] Sıralanmış haldeki dizimiz budur. 18 ise bu dizide Average case kapsamına girmektedir.





5.[7,3,5,8,2,9,4,15,6]. dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


[7,3,5,8,2,9,4,15,6] n

[2,3,5,8,7,9,4,15,6] n-1

[2,3,4,8,7,9,5,15,6] n-2

[2,3,4,5,7,9,8,15,6] 1









