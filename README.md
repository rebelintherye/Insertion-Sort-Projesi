## Insertion-Sort-Projesi

# Birinci Soru
 [22,27,16,2,18,6] -> Insertion Sort
 
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

---
1. 
```print 
[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

[2,6,16,18,22,27]
```


---
2.
```
Worst Case: O(n^2)

Average Case: O(n^2)

Best Case: O(n)
```

---
3.
```
Dizi sıralandıktan sonra şu şekli alır: 2,6,16,18,22,27 
18 ortada olduğu için Avarage case kapsamına girer.
```

# İkinci Soru
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
---
```
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
```

Not: Insertion Sort konu anlatımının yorum kısımlarında bu konunun farklı kaynaklarda Selection Sort olarak adlandırıldığını gördüğüm için kafa karıştırıcı olduğunu düşünüyorum.
