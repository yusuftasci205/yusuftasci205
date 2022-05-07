[22,27,16,2,18,6] -> Insertion Sort

A-)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Insertion Sort Aşamaları                                           
                                                             
1-) [22,27,16,2,18,6]  
2-) [2,27,16,22,18,6]
3-) [2,6,16,22,18,27]
4-) [2,6,16,18,22,27]
5-) [2,6,16,18,22,27]
6-) [2,6,16,18,22,27]

B-) Big-O gösterimi

Big-O Notation
dizinin her işlemi sırasıyla azaltarak gider n işlem ile başlar 1 işlem ile son bulur.
Bu da şu anlama gelir  1 den n  kadar olan tüm sayılarun toplamıdır.

(n * (n+1)) / 2 = (n^2 + n) / 2 O(n^2)


C-) Time Complexity(best-worst-average) case:

best case: aranan  sayının en başta olması durumudur.
average case : aranan sayının dizinin ortanca terimi olması durumuudur.
worst case: aranan sayının dizinin en sonunda olması durmudur.

D-)
[2,6,16,18,22,27]
Ortanca terimdir.yani 'average case' dir.

E-)
İnsertion Sorta göre dizinin ilk 4 terimi:

Dizi=[7,3,5,8,2,9,4,15,6] 

 [3,7,5,8,2,9,4,15,6]

 [3,5,7,8,2,9,4,15,6]
 
 [3,5,7,8,2,9,4,15,6]
 
 [2,3,5,7,8,9,4,15,6]
 
