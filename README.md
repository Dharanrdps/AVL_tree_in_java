# AVL_tree_in_java
An AVL tree, named after its inventors Adelson-Velsky and Landis, is a self-balancing binary search tree. It maintains a balance factor for each node, which is the difference in heights between its left and right subtrees. The balance factor helps keep the tree height balanced, ensuring that the tree remains efficient for search, insert, and delete operations.

Properties of an AVL tree:
1. Binary Search Tree Property: For every node in the tree, the values in its left subtree are less than the node's value, and the values in its right subtree are greater.

2. Balance Factor Property: For every node in the tree, the absolute difference between the heights of its left and right subtrees (the balance factor) is at most 1. The balance factor can be -1, 0, or 1.

Insertion and deletion in AVL trees involve rotations to maintain the balance factor property. Rotations are local transformations that restructure parts of the tree while preserving the binary search tree property.

There are four types of rotations in AVL trees:
1. Left Rotation (LL rotation): A single rotation that balances the left-heavy situation.
2. Right Rotation (RR rotation): A single rotation that balances the right-heavy situation.
3. Left-Right Rotation (LR rotation): A double rotation that balances a node that has a left child that is right-heavy.
4. Right-Left Rotation (RL rotation): A double rotation that balances a node that has a right child that is left-heavy.

When inserting or deleting nodes, AVL trees perform rotations as needed to maintain the balance factor property. This ensures that the height of the tree remains logarithmic, resulting in efficient search and other operations.

The main advantage of AVL trees is that they provide a worst-case time complexity of O(log n) for search, insert, and delete operations. However, they require extra space to store the balance factors and may involve more complex rotations during insertion and deletion.

AVL trees are used in various applications, including databases, language parsing, and other scenarios where balanced binary search trees are required to achieve efficient data manipulation operations.
