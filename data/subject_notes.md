Subject: Data Structures and Algorithms (DSA) – B.Tech CSE Core
Topic 1: Arrays vs Linked Lists
An Array is a linear data structure that stores elements of the same data type in contiguous memory locations. Each element can be accessed directly using its index, making random access very fast with a time complexity of O(1). However, inserting or deleting elements in the middle of an array is expensive because other elements may need to be shifted.

A Linked List is a linear data structure consisting of nodes, where each node contains two parts: data and a pointer to the next node. Unlike arrays, linked list nodes are stored in non-contiguous memory locations. Insertion and deletion are efficient when the required node position is known, generally taking O(1) time. However, accessing an element requires sequential traversal, resulting in O(n) time complexity.

Topic 2: Stack and Queue Data Structures
A Stack is a linear data structure that follows the LIFO (Last In, First Out) principle, meaning the last element inserted is the first one removed. Two fundamental operations are performed on a stack:

Push: Inserts an element at the top of the stack.

Pop: Removes the topmost element from the stack.

Peek: Returns the top element without removing it.

Stacks are commonly used in function calls, recursion, expression evaluation, and undo operations.

A Queue is a linear data structure that follows the FIFO (First In, First Out) principle, meaning the first element inserted is the first one removed. Its main operations include Enqueue (insertion), Dequeue (deletion), and Front (accessing the first element). Queues are widely used in CPU scheduling, printer management, and task processing.

Topic 3: Trees and Binary Search Trees (BST)
A Tree is a non-linear hierarchical data structure consisting of nodes connected through edges. The topmost node is called the Root, while nodes without children are called Leaf Nodes. Important terminology includes Parent, Child, Sibling, Height, Depth, and Subtree.

A Binary Search Tree (BST) is a special type of binary tree in which:

All values in the left subtree are smaller than the root node.

All values in the right subtree are greater than the root node.

Both left and right subtrees follow the same BST property.

Searching, insertion, and deletion in a balanced BST generally take O(log n) time, while in a skewed BST, these operations can take O(n) time.

Three important tree traversal techniques are:

Inorder: Left → Root → Right.

Preorder: Root → Left → Right.

Postorder: Left → Right → Root.

Topic 4: Sorting Algorithms (Bubble Sort, Merge Sort, and Quick Sort)
Sorting is the process of arranging data elements in a specific order, usually ascending or descending. Sorting algorithms improve data organization and make searching and processing more efficient.

1. Bubble Sort: Repeatedly compares adjacent elements and swaps them if they are in the wrong order. Its average and worst-case time complexity is O(n²). It is simple but inefficient for large datasets.

2. Merge Sort: Uses the Divide and Conquer technique by dividing an array into smaller subarrays, sorting them individually, and merging them into a sorted array. Its time complexity is O(n log n) in the best, average, and worst cases. It requires O(n) additional space for arrays.

3. Quick Sort: Selects an element called the Pivot and partitions the array so that smaller elements appear before the pivot and larger elements appear after it. Its average time complexity is O(n log n), while its worst-case complexity is O(n²).

These sorting algorithms are fundamental concepts in DSA and are frequently used in competitive programming, software development, and technical interviews.


