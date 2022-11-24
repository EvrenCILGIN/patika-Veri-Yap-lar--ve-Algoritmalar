# Selection Sort Projesi
### [22,27,16,2,18,6] -> Insertion Sort

***

#### 1) Verilen dizinin sort türüne göre aşamalarını yazınız.

1. [**2**,27,16,**22**,18,6] -> `2` dizinin küçük sayısıdır, en başa alabilmek için `22` ile yer değiştirir.
2. [2,**6**,16,22,18,**27**] -> İkinci küçük sayı `6`'dır ikinci sıraya almak için `27` ile yer değiştirir.
3. [2,6,**16**,18,22,27] -> Üçüncü sayı `16`'dır, sıralaması doğru olduğu için herhangi bir değişiklik yapılmaz. 
4.  [2,6,16,**18**,22,27] -> Dördüncü sayı `18`'dir sıralaması doğru olduğu için herhangi bir değişiklik yapılmaz. 
5.  [2,6,16,18,**22**,27] -> Beşinci sayı `22`'dir sıralaması doğru olduğu için herhangi bir değişiklik yapılmaz. 
6. [2,6,16,18,22,**27**] -> Altıncı sayı `27`'dir sıralaması doğru olduğu için herhangi bir değişiklik yapılmaz. 

*** 

#### 2) Big-O gösterimini yazınız.

(n²+n)/2 =  **O(n²)**

*** 

#### 2) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 

[2,6,16,**18**,22,27] 

**Average case: Aradığımız sayının ortada olması**
~~Worst case: Aradığımız sayının sonda olması~~
~~Best case: Aradığımız sayının dizinin en başında olması.~~

***

#### 4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. [**2**,3,5,8,7,9,4,15,6]
2. [**2,3**,5,8,7,9,4,15,6]
3. [**2,3,4**,8,7,9,5,15,6]
4. [**2,3,4,5**,7,9,8,15,6]

***