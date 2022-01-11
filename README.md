# Veri-Yapilari-ve-Algoritmalar-Insertion-Sort
## Insertion Sort Proje 
## 1-  [22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
* 1.Aşama ---------->  [22,27,16,2,18,6]   

* 2.Aşama ---------->  [22,16,27,2,18,6]  
                       [16,22,27,2,18,6]

* 3.Aşama ---------->  [16,22,2,27,18,6]
                       [16,2,22,27,18,6]
                       [2,16,22,27,18,6]

* 4.Aşama ---------->  [2,16,22,18,27,6]
                       [2,16,18,22,27,6]
                       
* 5.Aşama ---------->  [2,16,18,22,6,27]
                       [2,16,18,6,22,27]
                       [2,16,6,18,22,27]
                       [2,6,16,18,22,27]
```
### Big-O gösterimini yazınız.
*   O(n^2)
### Time Complexity: 
* Average case: O(n^2) = O(36)
* Worst case: O(n^2) = 0(36)
* Best case: O(n) = O(6)
### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
* Average Case

## 2- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
* 1.Aşama ---------->  [3,7,5,8,2,9,4,15,6]   

* 2.Aşama ---------->  [3,5,7,8,2,9,4,15,6]   

* 3.Aşama ---------->  [3,5,7,8,2,9,4,15,6] 

* 4.Aşama ---------->  [3,5,7,2,8,9,4,15,6] 
                       [3,5,2,7,8,9,4,15,6] 
                       [3,2,5,7,8,9,4,15,6] 
                       [2,3,5,7,8,9,4,15,6] 
```
