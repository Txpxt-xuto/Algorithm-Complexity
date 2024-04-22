# Algorithm 🤖

อัลกอริทึม คือ กระบวนการแก้ไขปัญหาตามหลักเหตุและผลที่มีการอธิบายเป็นขั้นเป็นตอนอย่างชัดเจนโดยใช้ทักษะการแก้ปัญหาตามหลักการคิดอย่างมีวิจารณญาณ ตั้งแต่การวิเคราะห์ปัญหาจนไปถึงการวางแผนแก้ไขปัญหาเป็นข้อ ๆ ตามลำดับขั้นตอน<br>
-------------------------------------------------------------------------
Algorithms ที่สาย problem solving ทุกคนควรรู้ by Tapat Toungsakul <br><br>
1.Sorting Algorithms :

	Bubble Sort
	Insertion Sort
	Selection Sort
	Merge Sort
	Quick Sort
	Heap Sort

2.Searching Algorithms :

	Linear Search
	Binary Search
	Depth-First Search (DFS)
	Breadth-First Search (BFS)

3.Graph Algorithms :

	Dijkstra's Algorithm
	Bellman-Ford Algorithm
	Kruskal's Algorithm
	Prim's Algorithm

4.Dynamic Programming :

	Fibonacci Sequence using Dynamic Programming
	Longest Common Subsequence (LCS)
	Knapsack Problem
	Shortest Path in a Graph

5.Tree Algorithms :

	Depth-First Traversal of a Tree
	Breadth-First Traversal of a Tree
	Binary Search Tree (BST) Operations

6.String Algorithms :

	String Matching Algorithms
	Longest Common Substring

7.Sorting and Searching on Data Structures:

	Binary Search on Arrays and Trees
	Hashing and Hash Tables

8.Divide and Conquer Algorithms:

	Closest Pair of Points
	Matrix Multiplication

9.Greedy Algorithms :

	Huffman Coding
	Kruskal's Algorithm

10.Backtracking Algorithms :

	N-Queens Problem
	Sudoku Solver

11.Mathematical Algorithms:

	Euclidean Algorithm for Greatest Common Divisor (GCD)
	Sieve of Eratosthenes for Prime Numbers

12.Machine Learning Algorithms:

	Linear Regression
	k-Nearest Neighbors (kNN)
	Decision Trees
	k-Means Clustering
<br>
<h1>Big O คืออะไร</h1>
	<p>Big O หรือ Big O Notation คือระยะเวลาในการประมวลผลที่แย่ที่สุด (worst-case complexity) หรือ ใช้พื้นที่และทรัพยากรมากที่สุดในการ compile อัลกอริทึมใดๆ หรือที่เรียกกันว่า ความซับซ้อนของอัลกอริทึม (Algorithm Complexity) ซึ่งนำมาใช้วัดการวัดประสิทธิภาพของ Algorithm นั้นๆได้ว่าเหมาะสมหรือไม่</p><br>
<img src="https://www.freecodecamp.org/news/content/images/2021/06/1_KfZYFUT2OKfjekJlCeYvuQ.jpeg">
<h1>ประเภทของ Big O</h1>
	<p>O(1) - Constant Time : เป็น Big O ที่ใช้ทรัพยากรน้อยที่สุด โดยการทำงานจะเป็นลักษณะคงที่ แม้ Input จะมากหรือน้อย</p><br>
	<p>O(log n) - Logarithmic Time : การทำงานของอัลกอริทึมนี้จะลดจำนวนลูปครึ่งนึงทุกครั้งที่มีการทำงานสำเร็จ เช่น Binary Search</p><br>
	<p>O(n) - Linear Time : การทำงานของอัลกอริทึมนี้จะทำงานตามจำนวน Input ถ้ารับมาก ก็ทำมาก รับน้อย ทำน้อย เช่น loop</p><br>
	<p>O(n log n) - Linearithmic Time : การทำงานแบบซ้อนลูปที่ตัดข้อมูลที่ไม่ได้ใช้งานออกทีละครึ่ง เช่น merge sort, quick sort</p><br>
	<p>O(n^2) - Quadratic Time : การทำงานแบบซ้อนลูปที่ไม่ได้ตัดข้อมูล เช่น bubble sort, selection sort</p><br>
	<p>O(2^n) - Exponential Time : การทำงานแบบคำนวณทุกรูปแบบ เช่น ตัวซ้ำใน Array</p><br>
	<p>O(n!) - Factorial Time : เป็น Big O ที่ใช้เวลา พื้นที่และทรัพยากรมากที่สุด</p><br>
