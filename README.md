# Insertion Sort Projesi
<h3>A) [22, 27, 16, 2, 18, 6]</h3>


1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

>[22], 27, 16, 2, 18, 6<br>
>[22, 27], 16, 2, 18, 6<br>
>[16, 22, 27], 2, 18, 6<br>
>[2, 16, 22, 27], 18, 6<br>
>[2, 16, 18, 22, 27], 6<br>
>[2, 6, 16, 18, 22, 27]<br>

2) Big-O gösterimini yazınız.

>*O(n^2)*

3) Time Complexity: **Average case:** Aradığımız sayının ortada olması, **Worst case:** Aradığımız sayının sonda olması, **Best case:** Aradığımız sayının dizinin en başında olması. <br>

>Average Case: O(n^2)<br>
>Worst Case: O(n^2)<br>
>Best Case: O(n)<br>
  
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

>18 Average Case kapsamına girer.

<h3>B) [7, 3, 5, 8, 2, 9, 4, 15, 6]</h3>

Yukarıdaki dizinin Insertion Sort'a göre ilk 4 adımını yazınız.
>[7], 3, 5, 8, 2, 9, 4, 15, 6<br>
>[3, 7], 5, 8, 2, 9, 4, 15, 6<br>
>[3, 5, 7], 8, 2, 9, 4, 15, 6<br>
>[3, 5, 7, 8], 2, 9, 4, 15, 6<br>
>[2, 3, 5, 7, 8], 9, 4, 15, 6<br>
>[2, 3, 5, 7, 8, 9], 4, 15, 6<br>
>[2, 3, 4, 5, 7, 8, 9], 15, 6<br>
>[2, 3, 4, 5, 7, 8, 9, 15], 6<br>
>[2, 3, 4, 5, 6, 7, 8, 9, 15]<br>
# Merge Sort
<h3>[16, 21, 11, 8, 12, 22]</h3>
1) Yukarıdaki dizinin Merge Sort'a göre aşamalarını yazınız.

>{16, 21, 11, 8, 12, 22}<br>
>{16, 21, 11}------------{8, 12, 22}<br>
>{16,21}, {11}--------{8}, {12, 22}<br>
>{11, 16, 21}------{8, 12, 22}<br>
>{8, 11, 12, 16, 21, 22}

2) Big-O gösterimini yazınız.
>O(nlogn)
# Binary Search Tree
<h3>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]</h3>

Yukarıdaki dizinin Binary Search Tree'ye göre aşamalarını yazınız.

>Root 4 olarak belirledim ve başta 2-8 ekledim.<br>
>Sol tarafına 2, sağ tarafına 8 geçer.<br>
>Soldan ilerlediğimizde 2'nin soluna 1 sağına 3 ekledim.<br>
>1'in soluna son olarak 0 gelir.<br>
>Sağdan ilerlediğimizde 8'in soluna 6, sağına 9 ekledim.<br>
>6'nın sağına 7, soluna 5 ekledim.<br>
>![image](https://user-images.githubusercontent.com/75906919/153820300-04bcb1af-3414-4b96-acbc-ac11e8f3024a.png)
