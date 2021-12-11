# Patika.dev-repo-14
### Insertion Sort Projesi

**Soru - 1** 

[22,27,16,2,18,6] -> Insertion Sort

- Dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: 
    - Average case: Aradığımız sayının ortada olması,
    - Worst case: Aradığımız sayının sonda olması, 
    - Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 




**Dizinin sort türüne göre aşamaları.**
```
- 1. Adım : ilk sayıdan bahsettiğimiz için 22 kendi başına sıralıdır. Hiç bir işlem yapmadan devam eder.
22| 27 16 2 18 6
```
```
- 2. Adım: 27 ile gerisindeki sayı olan 22’ü kıyaslar. 22 27'den küçüktür. Herhangi bir değişiklik yapılmaz.
22| 27 16 2 18 6 --> 22 27| 16 2 18 6
```
```
- 3. Adım: 16 ile bir gerisindeki sayıyı kıyaslar 16 27' den küçüktür. 16 ile 27 yer değiştirir. Daha sonra tekrar 16 ile 22' yi kıyaslar 16 22' den de küçüktür. 16 ile 22 yer değiştirir.
22 27| 16 2 18 6 --> 22 16 27| 2 18 6 --> 16 22 27| 2 18 6
```
```
- 4. Adım: 2 27' den küçüktür. 2 ile 27 yer değiştirir. Daha sonra tekrar 2 ile 22' yı karşılaştırır 2  22' dan da küçüktür yer değiştirirler. En sonda 2 ile 16' yı karşılaştırır 2  16' da küçük olduğu için tekrar yer değiştiriler.
16 22 27| 2 18 6 --> 16 22 2 27| 18 6 --> 16 2 22 27| 18 6 --> 2 16 22 27| 18 6
```
```
- 5. Adım : 18 ile 27' yi karşılaştırır. 18  27' den küçük olduğu için yer değiştirirler. Daha sonra 18 ile 22' yi karşılaştırır. 18  22' den küçük olduğu için yer değiştiriler. Daha sonra 16 ile 18' i karşılaştırır. 16  18' den küçük olduğu için hiçbir işlem yapılmaz.
2 16 22 27| 18 6 --> 2 16 22 18 27| 6 --> 2 16 18 22 27| 6
```
```
- 6.Adım: 6 ile 27' yi karşılaştırır. 6 27' den küçük olduğu için yer değiştirirler. Daha sonra 6 ile 22 'yi karşılaştırır. 6  22' den küçük olduğu için yer değiştirirler. Daha sonra 6 ile 18' i karşılaştırır. 6  18' den küçük olduğu için yer değiştirirler. Daha sonra 6 ile 16' yı karşılaştırır. 6  16' dan küçük olduğu için yer değiştirirler. En son 6 ile 2' yi karşılaştırır. 6  2' den büyük olduğu için hiçbir işlem yapılmaz. 
2 16 18 22 27| 6 -->  2 16 18 22 6 27| -->  2 16 18 6 22 27| -->  2 16 6 18 22 27| -->  2 6 16 18 22 27|
```
**Big-O gösterimini yazınız.**  
```
O(n²)
```
**Time Complexity**

```
Best Case: O(n)
Average Case: O(n²)
Worst case: O(n²)
```
**Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?**
```
Average Case
```


**Soru - 2**

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. Adım: İlk sayı kendi başına sıralıdır. Hiç bir işlem yapmadan devam eder.
7| 3 5 8 2 9 4 15 6
```
```
2. Adım: 3 ve 7' yi karşılaştırır. 3  7' den küçük olduğu için yer değiştirirler.
7| 3 5 8 2 9 4 15 6 --> 3 7|5 8 2 9 4 15 6
```
```
3. Adım: 5 ve karşılaştırır. 5  7' den küçük olduğu için yer değiştirirler. Daha sonra 5 ve 3' ü karşılaştırır. 5  3' ten büyük olduğu için işlem yapılamz.
3 7|5 8 2 9 4 15 6 --> 3 5 7| 8 2 9 4 15 6
```
```
4. Adım: 8 ve 7' yi karşılaştırır. 8  7' den büyük olduğu için işlem yapılmaz
3 5 7| 8 2 9 4 15 6 --> 3 5 7 8| 2 9 4 15 6
```


