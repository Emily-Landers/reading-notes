# Trees

**Vocabulary**

- *Node*: A Tree node is a component which may contain its own values, and references to other nodes
- *Root*: The root is the node at the beginning of the tree
- K: A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- *Left*: A reference to one child node, in a binary tree
- *Right*: A reference to the other child node, in a binary tree
- *Edge*: The edge in a tree is the link between a parent and child node
- *Leaf*: A leaf is a node that does not have any children
- *Height*: The height of a tree is the number of edges from the root to the furthest leaf

- Traversing a tree allows us to search for a node, print out the contents of a tree, and much more!
- Depth first traversal is where we prioritize going through the depth (height) of the tree first. 
- The most common way to traverse through a tree is to use recursion.
- Pre-order: `A, B, D, E, C, F`
- In-order: `D, B, E, A, F, C`
- Post-order: `D, E, B, F, C, A`
- Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.
- Traditionally, breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree.
- There is no specific sorting order for a binary tree. 
- If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree.
- Because there are no structural rules for where nodes are “supposed to go” in a binary tree, it really doesn’t matter where a new node gets placed.
- A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.
- Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree.

## References

- https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html 
