# Trees


* Trees are a fundamental data structure in computer science and are used to represent hierarchical relationships between elements. They find applications in various domains such as file systems, databases, and network routing algorithms.


## 1. What is a Tree?
* A tree is a collection of nodes connected by edges, with the following characteristics:

* It has a single root node that serves as the starting point.
* Each node can have zero or more child nodes.
* There is a unique path between the root and every other node in the tree.

---
---
## 2. Terminology:

* Node: An individual element within a tree that holds some data.
* Edge: The connection between two nodes.
* Root: The topmost node in the tree from which all other nodes are descendants.
* Parent: A node that has child nodes.
* Child: A node directly connected to another node when moving away from the root.
* Leaf: A node that has no children.
* Sibling: Nodes that share the same parent.
* Depth: The number of edges between the root and a given node.
* Height: The maximum depth of any node in the tree.

---
---
## 3. Types of Trees:

* Binary Tree: A tree in which each node has at most two children, referred to as the left child and the right child.

* Binary Search Tree (BST): A binary tree in which the left child of a node holds a value smaller than the node's value, and the right child holds a value greater than or equal to the node's value.

* Balanced Tree: A tree in which the heights of the left and right subtrees of any node differ by at most one. Examples include AVL trees and Red-Black trees.

---
---
## 4. Tree Traversal:
* Traversal refers to the process of visiting and processing all the nodes in a tree in a specific order. 
There are three common ways to traverse a tree:

* Pre-order traversal: Process the node, then recursively traverse the left and right subtrees.

* In-order traversal: Recursively traverse the left subtree, process the node, and then recursively traverse the right subtree. This results in nodes being visited in ascending order in a BST.

* Post-order traversal: Recursively traverse the left and right subtrees, and then process the node.

---
---
## 5. Tree Operations:

* Insertion: Adding a new node to the tree.

* Deletion: Removing a node from the tree.
* Searching: Finding a specific node in the tree.
* Height Calculation: Determining the height of the tree.
* Tree Validation: Checking if a given tree is a valid binary search tree.