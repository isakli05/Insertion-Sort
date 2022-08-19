
patika.dev Veri Yapıları ve Algoritmalar - [Insertion Sort Projesi ve Tüm projelerim](https://app.patika.dev/isakli05).
# Insertion Sort
## patika.dev Veri Yapıları ve Algoritmalar - Insertion Sort Projesi

## [22,27,16,2,18,6] -> Insertion Sort
## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

### [2] 22, 27, 16, 18, 6 = n-1
### [2, 6] 22, 27, 16, 18 = n-2
### [2, 6, 16] 22, 27, 18 = n-3
### [2, 6, 16, 18] 22, 27 = n-4
### [2, 6, 16, 18, 22] 27 = n-5
### [2, 6, 16, 18, 22, 27] = 1

## Birden n'e kadar olan sayıların toplamı = n*(n+1)/2 > n<sup>2</sup>+n/2;
## Big-O notation = O(n<sup>2</sup>)

## 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?.
##  Dizi sıralandıktan sonra 18 sayısı  **Average case** kapsamına girer.

------------------------------------------------------------------------

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### 1.adım --> [2] 7, 3, 5, 8, 9, 4, 15, 6
### 2.adım --> [2, 3] 7, 5, 8, 9, 4, 15, 6
### 3.adım --> [2, 3, 4] 7, 5, 8, 9, 15, 6
### 4.adım --> [2, 3, 4, 5] 7, 8, 9, 15, 6
