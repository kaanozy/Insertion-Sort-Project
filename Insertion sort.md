# Insertion Sort Project
Problem 1: [22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.

n*(n+1)/2 --> 1/2 * n² + 1/2 * n --> O(n²)

3. Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- Average Case: n*(n+1)/2*1/2 --> 1/4 * n² + 1/4 * n --> O(n²)
- Worst Case: n*(n+1)/2 --> 1/2 * n² + 1/2 * n --> O(n²)
- Best Case: O(n) because of n-1 steps

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 Average Case because this number is in the middle side not from the end sides. 

Problem 2: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6] 
- [2,3,4,5,6,9,8,15,7]
