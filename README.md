# binary-trees-and-tries

Trees and Tries are both data structures of branching nodes. 

## Binary Trees

A **Binary Tree** have nodes that store keys and  have at most two children. 

- The Root is at the top of the tree.
- The edges are branches
- Nodes at the edges are Leaves.
- The longest path is the height.
- The keys of the nodes can be numbers or strings.

### Inserting Nodes into a Binary Tree

- The left node is always less than its parent.
- The right node is always larger than its parent.
A binary tree is a tree data structure where each element/node has at most 2 children. These two children are referred to as the left child and right child.  

A node in a binary tree will consist of three parts:
1) data
2) pointer to the left child
3) pointer to the right child.  

Each node has only one parent.  Nodes at the edges which contain no children are referred to as leaves. At the top of a binary tree is called the root which is also just a node.  

For every node, it follows the same pattern in where the left child points to a node with a value that is smaller and the right child points to a node with a larger value. 

Because of how a binary tree is structured elements that are inserted can be properly sorted based on the root and leaf of where it is being inserted. 

For example: 
If my root is 5 and the element I want to insert is 3, 3 would then be inserted on the next available leaf that is on the left side of the tree because it is smaller.  If my root is 5 and the element I want to insert is 6, 6 would then be inserted on the next available leaf on the right side of the tree because it is larger than my root. 

A binary tree is effective inserting, deleting, and searching elements.  

To insert and delete, a binary tree is just consisted of nodes that point to other nodes.  If we need to insert, the nodes just have to insert to an available leave where that element could be; and then because of how the tree is ordered there's nothing extra needed. 

This is more effective than having an ordered array because the array has to maintain that particular order when we insert new values to it.  

For searching, binary tree has the advantage of binary search which will cut in half the time it takes to do a linear search of traversing through every element.  This is because in a binary search we take split the array at the midpoint and take a subset of where the element could be and then we just repeat until it is found. Doing binary search,  we divide n by 2 until it is found {n/(2^k) = 1} which can rewritten as T(n) = log n. 

## Tries

A **Trie** is similar to a Binary Tree, except that the nodes do not store the keys associated with the nodes. The position of the node within the tree determines the key of the node. 

- All of the descendents of the node have a common prefix of the string associated with the node.
- The keys of the nodes are usually strings, used for searching.
- The key part for each node in one of these Trees is (usually) a string.
- The root node is an empty string.
- Letters are added to the string key for each node, moving away from the root.
- Actual values are associated only with the “Leaves” of the trie.

It is used when there’s a partially completed field, and there’s a want to provide a list of possibilities connected to that partially completed field. 
In this example, all the descendents of a node have a common prefix.  

A trie (pronounced: “try”), also called digital tree and sometimes radix tree or prefix tree (as they can be searched by prefixes), is a kind of search tree.

Search Tree:  An ordered tree data structure that is used to store a dynamic set or associative array where the keys are usually strings

The key part for each node in one of these Trees is (usually) a string. 
The root node is an empty string.
Letters are added to the string key for each node, moving away from the root.  
Actual values are associated only with the “Leaves” of the trie.  
Example of use in the Real World:
Word completion in a google search field. 
It is used when there’s a partially completed field, and there’s a want to provide a list of possibilities connected to that partially completed field. 
In this example, all the descendents of a node have a common prefix.  
Time complexity of O(L)

## links
- https://www.geeksforgeeks.org/binary-tree-data-structure/
- https://www.geeksforgeeks.org/complexity-different-operations-binary-tree-binary-search-tree-avl-tree/
- https://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/
- https://my.generalassemb.ly/activities/8
- https://my.generalassemb.ly/activities/263
- https://www.google.com/amp/s/www.geeksforgeeks.org/trie-insert-and-search/amp/
- https://link.medium.com/SU8DcC4SH4
- https://www.google.com/amp/s/www.geeksforgeeks.org/binary-tree-set-1-introduction/amp/
- https://www.geeksforgeeks.org/trie-insert-and-search/
- https://www.geeksforgeeks.org/advantages-trie-data-structure/amp/

