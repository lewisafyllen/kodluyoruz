#  www.patika.dev
# insertion sort projesi
[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

Big-0 gösterimi

O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

 [22,27,16,2,18,6] 18 sayısı ortada olduğu için average case kapsamına girer.
 
 [7,3,5,8,2,9,4,15,6] ilk dört aşaması:
 
 [2,3,5,8,7,9,4,15,6] 
 
 [2,3,4,8,7,9,5,15,6] 
 
 [2,3,4,5,7,9,8,15,6] 
 
 [2,3,4,5,6,9,8,15,7] 
 
# merge sort projesi

          [16,21,11,8,12,22]
[16,21,11]             [8,12,22] 

[16,21]   [11]           [8,12] [22]
 
[16]   [21]   [11]        [8]   [12]   [22] tek eleman kalana kadar ayrılır.

[16,21]    [11]          [8,12]   [22]

[11,16,21]     [8,12,22]   

[8,11,12,16,21,22]

Big-O Gösterimi

O(nlogn)

# Binary Search Three projesi
            
            [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
            
                      
          sol            5           sağ
           
                  3              7 
                     
              1       4       6      9
                 
           0      2              8
           
root 5 sayısıdır. 5'in sağında 7 solunda 3 vardır. 

Big-O gösterimi

average case: O(logn)
worst case: O(n)
insertion case: O(logn)
