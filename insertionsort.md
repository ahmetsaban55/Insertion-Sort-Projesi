## [22,27,16,2,18,6]-> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamaları

    1. [22|27 16 2 18 6]
    2. [27 22|16 2 18 6]
    3. [16 27 22|2 18 6]
    4. [2 16 27 22|18 6]
    5. [2 16 18 27 22|6]
    6. [2 6 16 18 27 22]

2. Big-O gösterimi O(n^2)'dir.
3. Time complexity
    
    1. Worst case: 22
    2. Average case: 16, 18
    3. Best case: 2

4. Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.


## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı;

1. [3 7|5 8 2 9 4 15 6]
2. [3 5 7|8 2 9 4 15 6]
3. [3 5 7 8|2 9 4 15 6]
4. [2 3 5 7 8|9 4 15 6]