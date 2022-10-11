Merge Sort

[16,21,11,8,12,22]  dizisinin sort türüne göre aşamaları 

1.                        [16,21,11]   [8,12,22]

2.                     [16]  [21,11]   [8,12]  [22]
                
3.                [16]   [21]   [11]   [8]   [12]   [22]
 
4.                    [16]   [11,21]   [8,12]   [22]

5.                        [11,16,21]   [8,12,22]
                    
---------------------------------------------------------------------

Dizi her seferinde tek eleman olana kadar ortadan ikiye bölüyoruz ve sonra soldaki elemanlar küçük olucak şekilde ikili olarak birleştiriyoruz.


Big-O Gösterimi 

-  O(n*(logn))




[Patika.dev](https://www.patika.dev/tr)

