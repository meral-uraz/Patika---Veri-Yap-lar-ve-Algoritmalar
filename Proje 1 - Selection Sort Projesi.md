
1. [22,27,16,2,18,6] -> Insertion Sort

a. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
   1.Adım: [22,27,16,2,18,6]   || 22 27'den küçüktür herhangi bir değişiklik yapılmadı
   2.Adım: [22,16,27,2,18,6]   || 27 ile 16 yer değişti
   3.Adım: [16,22,27,2,18,6]   || 22 ile 16 yer değişti
   4.Adım: [16,22,2,27,18,6]   || 27 ile 2 yer değişti
   5.Adım: [16,2,22,27,18,6]   || 22 ile 2 yer değişti
   6.Adım: [2,16,22,27,18,6]   || 16 ile 2 yer değişti
   7.Adım: [2,16,22,18,27,6]   || 27 ile 18 yer değişti
   8.Adım: [2,16,18,22,27,6]   || 22 ile 18 yer değişti
   9.Adım: [2,16,18,22,6,27]   || 27 ile 6 yer değişti
   10.Adım: [2,16,18,6,22,27]  || 22 ile 6 yer değişti
   11.Adım: [2,16,6,18,22,27]  || 18 ile 6 yer değişti
   12.Adım: [2,6,16,18,22,27]  || 16 ile 6 yer değişti
```

b. Big-O gösterimini yazınız.
```
n+(n-1)+(n-2)...1 = n.(n+1)/2 = n^2+n/2 => O(n^2)

    1.Adım: 1
    2.Adım: 2
    3.Adım: 3
    .
    .
    .
    n.Adım: n
    Sum: (n*(n+1)/2) = --> O(n^2)
```

c. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
	- ==a. Average Case : Aradığımız sayının ortada olması==
	- b. Worst Case : Aradığımız sayının sonda olması
	- c. Best Case : Aradığımız sayının dizinin en başında olması.


2. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
    1.Adım: [2,3,5,8,7,9,4,15,6]
    2.Adım: [2,3,4,8,7,9,5,15,6]
    3.Adım: [2,3,4,5,7,9,8,15,6]
    4.Adım: [2,3,4,5,6,9,8,15,7]
```

