# Insertion Sort Projesi

## [22,27,16,2,18,6]

**1.Insertion sort aşamaları:**

1. [22,27,16,2,18,6] (22)'nin solunda eleman olmadığından, (27) 22'den büyük olduğundan yerleri değişmez.
2. [16,22,27,2,18,6] (16) 22 ve 27'den küçük olduğundan ikisinin önüne geçer.
3. [2,16,22,27,18,6] (2) 16,22 ve ve 27'den küçük olduğundan üçünün önüne geçer.
4. [2,16,18,22,27,6] (18) 22 ve 27den küçük olduğundan ikisinin önüne geçer.
5. [2,6,16,18,22,27] (6) 16,18,22 ve 27'den küçük olduğundan dördünün önüne geçer.

**2. Big-O gösterimi:** O(n^2)

**3. Time Complexity:**
Average Case: O(n^2)
Worst Case: O(n^2)
Best Case: O(n)

**4. Dizi sıralandıktan sonra 18 sayısı "Worst Case" kapsamına girer.**


## [7,3,5,8,2,9,4,15,6]

**Insertion sort'un ilk 4 aşaması:**

1. [7,3,5,8,2,9,4,15,6] (7)'nin solunda eleman olmadığından yeri değişmez.
2. [3,7,5,8,2,9,4,15,6] (3) 7'den küçük olduğundan önüne geçer.
3. [3,5,7,8,2,9,4,15,6] (5) 7'den küçük olduğundan önüne geçer.
4. [3,5,7,8,2,9,4,15,6] (8) 7'den büyük olduğu için yeri değişmez.
5. [2,3,5,7,8,9,4,15,6] (2) önündeki tüm elemanlardan küçük olduğu için en öne geçer.

