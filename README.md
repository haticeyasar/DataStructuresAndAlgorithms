# DataStructuresAndAlgorithms

PROJECT-1

 ***[22,27,16,2,18,6] dizisi
 
 1)Insertion Sort tüm adımları
 
          22 27 16 2 18 6
          16 22 27 2 18 6
          2 16 22 27 18 6
          2 16 18 22 27 6
          2 6 16 18 22 27
 
 2)Big-O gösterimi: O(N^2)
 
 3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
   Average case: O(N^2)
   Worst case:   O(N^2)
   Best case:    O(N)
   
 4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
   Average case kapsamına girer.
   
   
   ***[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
    
        3 7 5 8 2 9 4 15 6
        3 5 7 8 2 9 4 15 6
        3 5 7 8 2 9 4 15 6
        2 3 5 7 8 9 4 15 6
   
PROJECT-2
 ***[16,21,11,8,12,22] -> Merge Sort

1)Yukarıdaki dizinin sort türüne göre aşamaları
      16,21,11,8,12,22
      
    16 21 11       
    16  21  11     
    11 16 21  
    
    8 12 22
    8  12  22
    8 12 22
    
    8 11 12 16 21 22


2)Big-O gösterimi:O(N*log N)

PROJECT-3

 ***[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
             root -> 7
                   /   \
                  5     8
                 /       \
                1         9
               / \
              0   3
                 / \
                2   4

 Root 7' dir,sağında 8 solunda 5 bulunur.
 8'in sağında 9 bulunur.
 5'in sağında 6 solunda 1 bulunur.
 1'in sağında 3 solunda 0 bulunur.
 3'ün sağında 4 solunda 2 bulunur.
