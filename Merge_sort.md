
### [16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

### sort türüne göre aşamaları
```
1. Adım: Diziyi ikiye ye böl 
  16 21 11  |  8 12 22 
```
```
2. Adım: Ortaya çıkan bu dizileri ikiye böl
  16 | 21 11  |  8 12 | 22
```
```
3. Adım: Ortaya çıkan bu dizileri ikiye böl
  16 | 21 | 11  |  8 | 12 | 22
 ```
 ```
4. Adım: Bölünmüş dizileri sıralayarak birleştir.
  16 | 11 21  |  8 12 | 22
 ```
 ```
5. Adım: Bölünmüş dizileri sıralayarak birleştir.
  11 16 21  |  8 12 22 
 ```
 ```
6. Adım: Bölünmüş dizileri sıralayarak birleştir.
  8 11 12 16 21 22   
  ```   
### Big-O gösterimini yazınız.
```
O(nlogn)
```


  

    

         
