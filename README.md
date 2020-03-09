# binary-trees-and-tries

A binary tree is a tree data structure where each element/node has at most 2 children. These two children are referred to as the left child and right child.  A node in a binary tree will consist of three parts 1) data, 2) pointer to the left child, and 3) pointer to the right child.  Each node has only one parent.  Nodes at the edges which contain no children are referred to as leaves. At the top of a binary tree is called the root which is also just a node.  For every node, it follows the same pattern in where the left child points to a node with a value that is smaller and the right child points to a node with a larger value. 

Because of how a binary tree is structured elements that are inserted can be properly sorted based on the root and leaf of where it is being inserted. For example, if my root is 5 and the element I want to insert is 3, 3 would then be inserted on the next available leaf that is on the left side of the tree because it is smaller.  If my root is 5 and the element I want to insert is 6, 6 would then be inserted on the next available leaf on the right side of the tree because it is larger than my root. 

A binary tree is effective inserting, deleting, and searching elements.  To insert and delete, a binary tree is just consisted of nodes that point to other nodes.  If we need to insert, the nodes just have to insert to an available leave where that element could be; and then because of how the tree is ordered there's nothing extra needed. This is more effective than having an ordered array because the array has to maintain that particular order when we insert new values to it.  For searching, binary tree has the advantage of binary search which will cut in half the time it takes to do a linear search of traversing through every element.  This is because in a binary search we take split the array at the midpoint and take a subset of where the element could be and then we just repeat until it is found. Doing binary search,  we divide n by 2 until it is found {n/(2^k) = 1} which can rewritten as T(n) = log n. 

## links
https://www.geeksforgeeks.org/binary-tree-data-structure/
https://www.geeksforgeeks.org/complexity-different-operations-binary-tree-binary-search-tree-avl-tree/
https://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/
https://my.generalassemb.ly/activities/8
https://my.generalassemb.ly/activities/263
