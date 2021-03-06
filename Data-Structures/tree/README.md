# Trees
Create a BinaryTree class

## Challenge
1. Create a Node class that has properties for the value stored in the node, the left child node, and the right child node.
2. Create a BinaryTree class (Define a method for each of the depth first traversals called preOrder, inOrder, and postOrder which returns an array of the values, ordered appropriately)
3. Create a BinarySearchTree class :
- Define a method named add that accepts a value, and adds a new node with that value in the correct location in the binary search tree.
- Define a method named contains that accepts a value, and returns a boolean indicating whether or not the value is in the tree at least once
4.  breadth first traversal method which takes a Binary Tree as its unique input. Without utilizing any of the built-in methods available to your language, traverse the input tree using a Breadth-first approach, and return a list of the values in the tree in the order they were encountered.

## Approach & Efficiency
- preOrder()  O(n)
- InOrder()  O(n)
- PostOrder() O(n)
- add() O(logn)
- contains() O(logn)
- breadth-first() O(n)
- findMaximumValue O(n)

## Solution
-  tree
![Whiteboard](./tree.jpg)

- breadth-first
![Whiteboard](./breadth-first.jpg)

- findMaximumValue
![Whiteboard](./find-maximum-binary-tree.jpg)
