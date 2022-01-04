## PROJE 1
```
[22,27,16,2,18,6] -> Insertion Sort

1.    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.    Big-O gösterimini yazınız.
3.    Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.    Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5.    [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```

## CEVAPLAR

1.        
        [2,27,16,22,18,6]     2 ile 22 yer değiştirir
        [2,6,16,22,18,27]     6 ile 27 yer değiştirir
        [2,6,16,22,18,27]     16 diğer değerlerden küçük olduğundan bir sonraki adıma geçilir.
        [2,6,16,18,22,27]     22 ile 18 yer değştirir.
        [2,6,16,18,22,27]     22 den küçük değer var mı diye kontröle devam edilir.
        [2,6,16,18,22,27]     ve sıralanmış olur.
        
2.    Big-O notation: ilk adımda n, ikinci adımda n-1, ücüncü adımda n-2 şeklinde ilerliyor.
      Yani n*(n+1)/2 = (n^2+n)/2
      O(n^2) notasyonu
        
3.    Time Complexity : 
                  Average Case: 16 ve 18
                  Worst Case  : 27
                  Best Case   : 2
        
4.    18 sayısı Average Case kapsamına girer.

5.    [2,3,5,8,7,9,4,15,6]    7 ile 2 yer değştirir
      [2,3,5,8,7,9,4,15,6]    3 den küçük değer yoktur. Bir sonraki adıma geçilir.
      [2,3,4,8,7,9,5,15,6]    5 ile 4 yer değştirir.
      [2,3,4,5,7,9,8,15,6]    8 ile 5 yer değştirir.
      
      
      
      
      
      
      
      
 
