https://bl.ocks.org/d3noob/43a860bc0024792f8803bba8ca0d5ecd

# Data Structure 
* Arrays
    * Sorting
        * Merge Sort
            * Merge Function
        * Heap Sort
        * Quick Sort
    * Bit Manipulation
    * Hash table
        * Two Sum
    * Two pointers
        * Three Sum
            * Sort
            * For loop
                * While loop
                * if current == 0
                * increase left pointer
                * decrease right pointer
        * Sort Colors
            * Three variables for 0(start) , 2(end) and (i) for usual iteration.
            * while loop
                * in case of 0
                    * Swap i and start and then increment both.
                * in case of 2
                    * Swap end with i and then decrement end.
                * in case of 1
                    * Increment only i.
    * Linked List
    * Dynamic Programming
    * Binary Search
        * Define left and right
        * while left <= right
            * Define pivot
    * Prefix Sum
    * Greedy
    * Math
    * Matrix
    * Simulation
    * Divide and Conquer
        * Maximum Sub Array
            * max_cross_sub_array - base function
                * Calculate left sum
                    * for loop from mid to low
                * Calculate right sum
                    * For loop from mid to high
            * max_sub_array - main function to call max_cross_sub_array recursively
    * Depth First Search
    * Sorting
    * Backtracking
        * Combination
            * Recursive function
                * For loop
                    * Recursive Call
* String
    * Two pointers
    * Hash Table
    * Dynamic Programming
    * Queue
    * Counting
* Linked List
    * Recursion
    * Two pointers
    * Hash table
* Stack/Queue
    * Recursion
    * Design
    * String
* Tree
    * Operations
        * Depth-first search
        * Breadth-first search 
        * Divide and conquer
        * Backtracking
    * Binary Tree
        * Binary Search Tree
            * Operations
                * Traversal
                    * Breadth First search
                        * Level Order Traversal
                    * Depth First search
                        * Pre Order traversal
                            * root
                            * left
                            * right
                        * Post order traversal
                        * In order traversal
                            * left
                            * root
                            * right
            * Balanced Binary Search Tree
                * AVL
* Graph
    * Depth first search
    * Breadth first search
    * Hash table
* Heap(Priority Queue)
    * Divide and conquer
    * Hash table


# Algorithm

* Binary Search
    * Rotated sorted array
        * Define start , end
        * initiate while loop
            * define mid
            * Condition to return mid if target is found
            * if start is less than mid
                * if target is greater than mid or less than start then set start as mid + 1 else set end as mid - 1
            * if start is not less than mid
                * if target is less than mid or greater than start then set end as mid - 1 else set start as mid + 1
