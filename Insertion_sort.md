www.patika.dev

1- [22,27,16,2,18,6] -> Insertion Sort  -----n
[2,27,16,22,18,6] -------n-1
[2,6,16,22,18,27] ------n-2
[2,6,16,18,22,27] 
n+(n-1)+(n-2)….+1 ----.n

2- Big O Notation Gösterimi

Worst Case:  n+(n-1)+(n-2)......+1=n*(n+1)/2O(n^2)
Average Case: O(n²)
Best Case: O(n)

3-Time Complexity 
worst case: O(n^2)
Average case: O(n^2)
Best case:, O(n)

4-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]
[2,3,4,8.7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
