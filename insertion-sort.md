# **Project 1 - Insertion Sort**

### **[22, 27, 16, 2, 18, 6]** > Insertion Sort

## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```Javascript
[2, 22, 27, 16, 18, 6]
[2, 6, 22, 27, 16, 18]
[2, 6, 16, 22, 27, 18]
[2, 6, 16, 18, 22, 27]
```

## 2. Big-O gösterimini yazınız.

```
O(n^2)
```

## 3. Time Complexity

- ### Average case ( The number we are looking for is in the middle. )
  ```Javascript
  [2, 6, 16, 18, 22, 27] = 16 | 18
  ```
- ### Word Case ( The number we're looking for is at the end. )
  ```Javascript
  [2, 6, 16, 18, 22, 27] = 27
  ```
- ### Best Case ( The number we're looking for is at the very beginning of the array. )
  ```Javascript
  [2, 6, 16, 18, 22, 27] = 2
  ```

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer.

### **- Avarege Case**

## 5. [7 ,3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```Javascript
[2, 7, 3, 5, 8, 9, 4, 15, 6]
[2, 3, 7, 5, 8, 9, 4, 15, 6]
[2, 3, 4, 7, 5, 8, 9, 15, 6]
[2, 3, 4, 5, 7, 8, 9, 15, 6]
```
