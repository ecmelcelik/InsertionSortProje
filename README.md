# InsertionSortProje
Insertion Sort Proje ödevi tamamlandı



1. Proje:

[22,27,16,2,18,6] == Insertion Sort


#Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

#Big-O gösterimini yazınız.

#Time Complexity: Average case: Aradığımız sayının ortada olması
                   Worst case: Aradığımız sayının sonda olması
                   Best case: Aradığımız sayının dizinin en başında olması

#Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? yazınız.

#[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sorta göre ilk 4 adımını yazınız.

Cevaplar:


- [2,27,16,22,18,6] 
- [2,6,16,22,18,27] 
- [2,6,16,22,18,27] 
- [2,6,16,18,22,27] 
 

- O(n^2)

- Dizi sıralama işlemi yapıldıktan sonra 18 sayısı dizinin ortasında bulunduğu için "Avarage Case" kapsamına girmektedir.

- [7,3,5,8,2,9,4,15,6]

 1.Aşama: Örüntüye ait en küçük eleman olan 2 sayısı en baştaki sayı ile yer değiştirir.
 [2,3,5,8,7,9,4,15,6]

 2.Aşama: En küçük ücüncü eleman olan 4 sayısı 5 ile yer değiştirir.
 [2,3,5,8,7,9,4,15,6]

3.Aşama: En küçük dördüncü eleman olan 5 sayısı 8 ile yer değiştirir.
 [2,3,4,8,7,9,5,15,6]

 4.Aşama:
  [2,3,4,5,7,9,8,15,6]
