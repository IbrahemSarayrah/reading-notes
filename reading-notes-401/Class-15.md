# Implementation: Trees

* A binary tree is a tree-type non-linear data structure with a maximum of two children for each parent. Every node in a binary tree has a left and right reference along with the data element. ... The nodes that hold other sub-nodes are the parent nodes. A parent node has two child nodes: the left child and right child.

## Common Terminology

* Node - A Tree node is a component which may contain it’s own values, and references to other nodes

* Root - The root is the node at the beginning of the tree

* K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, `k = 2`

* Left - A reference to one child node, in a binary tree

* Right - A reference to the other child node, in a binary tree

* Edge - The edge in a tree is the link between a parent and child node

* Leaf - A leaf is a node that does not have any children

* Height - The height of a tree is the number of edges from the root to the furthest leaf

![Sample Tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)

## Traversals

* raversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:

* Depth First: Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root

* Breadth First: Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.

## K-ary Trees

* If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use `K` to refer to the maximum number of children that each Node is able to have.

## Adding a node

* Because there are no structural rules for where nodes are “supposed to go” in a binary tree, it really doesn’t matter where a new node gets placed.

* One strategy for adding a new node to a binary tree is to fill all “child” spots from the top down.

## Big O

* The Big O time complexity for inserting a new node is `O(n)`. Searching for a specific node will also be `O(n)`. Because of the lack of organizational structure in a Binary Tree, the worst case for most operations will involve traversing the entire tree. If we assume that a tree has n nodes, then in the worst case we will have to look at n items, hence the `O(n)` complexity.

## Binary Search Trees

* A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.
