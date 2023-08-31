# Insertion Sort Projesi
## Insertion Sort

>   [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

   > 1. [22,27,16,2,18,6]
   > 2. [2,27,16,22,18,6]
   > 3. [2,6,16,22,18,27]
   > 4. [2,6,16,18,22,27]

- Big-O gösterimini yazınız.

> n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n^2 Big-O = n^2

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
>    1. Average case: Aradığımız sayının ortada olması
>    2. Worst case: Aradığımız sayının sonda olması
>    3. Best case: Aradığımız sayının dizinin en başında olması.

Aradığımız sayı dizinin ortasında. **Average case.**

> - [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

>    1. [7,3,5,8,2,9,4,15,6]
>    2. [2,3,5,8,7,9,4,15,6]
>    3. [2,3,4,8,7,9,5,15,6]
>    4. [2,3,4,5,7,9,8,15,6]



## Merge Sort


>[16,21,11,8,12,22] -> Merge Sort

> 1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
> 2.Big-O gösterimini yazınız.

Sırsıyla ikiye bölünür

> [16 21 11 ] [ 8 12 22]

> [16 21] [ 11] [ 8 12] [22]

> [16] [21] [11] [8] [12] [22]

Sıralı bir şekilde birleştirme aşamasına geçilir

> [16 21] [11] [8 12] [22]
> [11 16 20] [8 12 22]

Son Birleştirme

> [8 11 12 16 20 22]

Big O gösterimi log2n=x yani logn olarak alınabilir.



## Binary Search tree

> [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root Seçilir

root 3 dür

Rootun Sağında ve Solunda olan değerler aşağıdadır

  &nbsp;   &nbsp;   3 <br>
        / &nbsp;  &nbsp;  &nbsp;&nbsp;\ <br>
    1&nbsp; &nbsp; &nbsp;&nbsp; &nbsp;  7 <br>
   /&nbsp;\ &nbsp;  &nbsp; &nbsp; / &nbsp; \ <br>
  0&nbsp; 2  &nbsp; 5 &nbsp; &nbsp; 8 <br>
&nbsp; &nbsp;&nbsp;&nbsp; &nbsp; / &nbsp;\ &nbsp;  &nbsp; &nbsp; \ <br>
&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 4 &nbsp;  &nbsp;6 &nbsp;&nbsp;&nbsp; &nbsp;9
