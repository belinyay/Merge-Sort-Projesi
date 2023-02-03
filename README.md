# Merge-Sort-Projesi
Patika.dev-Sort

# [16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
## Big-O gösterimini yazınız.

---

## - [16, 21, 11, 8, 12, 22] 

## Elemanlar en çok iki eleman kalana kadar gruplanır.

- **[16, 21, 11]** **[8, 12, 22]**

- **[16, 21]** **[11]** **[8, 12]** **[22]**

## Her dizi kendi içerisinde küçükten büyüğe sıralanır.

- **[16, 21]** **[11]** **[8, 12]** **[22]**

## Ardından 2şerli gruplar halinde sıralanarak birleştirilir. Bu işlem tek biz dizi olana dek devam eder.

- **[11, 16, 21]** **[8, 12, 22]**

- **[8, 11, 12, 16, 21, 22]**


### Big-O gösterimi : O(n logn)
