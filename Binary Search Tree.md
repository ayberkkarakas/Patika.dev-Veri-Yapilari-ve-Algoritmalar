# Binary Search Tree Projesi

## **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

**1. Binary-Search-Tree aşamaları:**

**1.** Kökümüzü 7 olarak seçersek dizinin geri kalan elemanları 7'den küçük ise soluna, 7'den büyük ise sağına yazılarak binary search tree oluşturulur.
**2.** 5,  kökümüzden küçük olduğundan sola yazılır.
```
      7     
     /    
    5
```
**3.** 1,  kökümüzden küçük olduğundan sola yazılır. Ardından 5'ten de küçük olduğundan onun da soluna yazılır.
```
      7     
     /   
    5
   /
  1
```
**4.** 8,  kökümüzden büyük olduğundan sağa yazılır.
```
      7     
     / \    
    5   8
   /
  1
```
**5.** 3,  kökümüzden küçük olduğundan sola yazılır. Ardından 5'ten de küçük olduğundan onun da soluna yazılır. Ardından 1'den büyük olduğundan onun sağına yazılır. 
 ```
      7     
     / \    
    5   8
   /
  1
   \
    3
```
**6.** 3,  kökümüzden küçük olduğundan sola yazılır. Ardından 5'ten büyük olduğundan onun sağına yazılır.
```
      7     
     / \    
    5   8
   / \
  1   6
   \
    3
```
**7.** 0,  kökümüzden küçük olduğundan sola yazılır. Ardından 5'ten de küçük olduğundan onun soluna yazılır. Ardından 1'den de küçük olduğundan onun soluna yazılır.
```
      7     
     / \    
    5   8
   / \
  1   6
 / \
0   3
```
**8.** 9,  kökümüzden büyük olduğundan sağa yazılır. Ardından 8'den de büyük olduğundan onun sağına yazılır.
 ```
      7     
     / \    
    5   8
   / \   \ 
  1   6   9
 / \
0   3
```
**9.** 4,  kökümüzden küçük olduğundan sola yazılır. Ardından 5'ten küçük olduğundan onun soluna yazılır. Ardından 1'den büyük olduğundan onun sağına yazılır. Ardından 3'ten büyük olduğundan onun sağına yazılır. 
```
      7     
     / \    
    5   8
   / \   \ 
  1   6   9
 / \
0   3
     \
      4
``` 
**10.** 2,  kökümüzden küçük olduğundan sola yazılır. Ardından 5'ten küçük olduğundan onun soluna yazılır. Ardından 1'den büyük olduğundan onun sağına yazılır. Ardından 3'ten küçük olduğundan onun soluna yazılır. 
```
      7     
     / \    
    5   8
   / \   \ 
  1   6   9
 / \
0   3
   / \
  2   4
``` 
