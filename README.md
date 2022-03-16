# InsertionSortProject
Insertion Sort is a sorting algorithm used in Computer Science. The Insertion Sort algorithm repeats the operations of shifting large elements to the right in the array by comparing the element with the previous elements, starting from the second element.

[22,27,16,2,18,6] -> Insertion Sort

**1. Write the stages of the above given sequence according to the sort type.**

1-> [22,27,16,2,18,6]  --  **0**

2-> [22,27,16,2,18,6]  --  **2**

3-> [16,22,27,2,18,6]  --  **3**

4-> [2,16,22,27,18,6]  --  **2**

5-> [2,16,18,22,27,6]  --  **4**

6-> [2,6,16,18,22,27]

**2. Write the Big-O notation.**

So in total we have on average 0 + 2 + 3 + 2 + 4 = 11 shift operations.

n = 6 elements;

11 = [ (6 × 5) / 3 ] +1 

[ ( n × (n - 1) ) / 3 ] + 1 = [(n² - n) / 3 ] + 1

The highest power of n in this term is n²; the time complexity for shifting is, therefore, O(n²). 

**3. Time Complexity:**
 
Average case: The number we are looking for is in the middle, -->> O(n²)

Worst case: The number we are looking for is at the end, -->> O(n²)

Best case: The number we are looking for is at the beginning of the array. -->> O(n)

**4.After the array is sorted, which case does the number 18 fall into? Write.**

Since it will participate from step 4, it is included in the Average case.

**Write the first 4 steps of the array according to the Insertion Sort.**

1->  [3,7,5,8,2,9,4,15,6]

2->	 [3,5,7,8,2,9,4,15,6]

3->  [3,5,7,8,2,9,4,15,6]

4->	 [2,3,5,7,8,9,4,15,6] 

5->	 [2,3,5,7,8,9,4,15,6] 

6->	 [2,3,4,5,7,8,9,15,6] 

7->	 [2,3,4,5,7,8,9,15,6] 

8->  [2,3,4,5,6,7,8,9,15] 
