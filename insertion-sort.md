# 1. [22,27,16,2,18,6] -> Insertion Sort verilen dizinin sort türüne göre aşamalarını yazınız.

ÇÖZÜM:
1. adım: [2,27,16,22,18,6]
2. adım: [2,6,16,22,18,27] 
3. adım: [2,6,16,18,22,27]


# 2. Big-O gösterimini yazınız.

ÇÖZÜM: 
n!= n*(n+1)/2= (n^2+n)/2 => O(n^2)

# 3. Time Complexity

Average case: Aradığımız sayının ortada olması,
ÇÖZÜM: O(n)

Worst case: Aradığımız sayının sonda olması,
ÇÖZÜM: O(n^2)

Best case: Aradığımız sayının dizinin en başında olması.
ÇÖZÜM: O(n^2)

# 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi sıralandıktan sonra 18 sayısı ortada kaldığı için Avarage case kapsamındadır.

# 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

ÇÖZÜM:
1. adım: [2,3,5,8,7,9,4,15,6]
2. adım: [2,3,4,8,7,9,5,15,6]
3. adım: [2,3,4,5,7,9,8,15,6]
4. adım: [2,3,4,5,6,9,8,15,7]