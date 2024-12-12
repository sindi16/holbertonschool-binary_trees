# Holberton School Binary Trees

## Project Overview
This project focuses on implementing binary tree operations in C. The goal is to build and manipulate binary trees through various functions, from creating nodes to traversing and analyzing the tree structure. The project contains a collection of files, each responsible for implementing different aspects of binary trees, such as insertion, deletion, traversal, and tree properties.

## Files Description
The project contains 18 different C source files and additional header files. Below is a brief description of each of the main files:

- `0-binary_tree_node.c`: Implements the function to create a new binary tree node.
- `1-binary_tree_insert_left.c`: Function for inserting a node to the left of a parent node.
- `2-binary_tree_insert_right.c`: Function for inserting a node to the right of a parent node.
- `3-binary_tree_delete.c`: Deletes a binary tree.
- `4-binary_tree_is_leaf.c`: Checks if a given node is a leaf.
- `5-binary_tree_is_root.c`: Checks if a node is the root of the binary tree.
- `6-binary_tree_preorder.c`: Performs a preorder traversal on the binary tree.
- `7-binary_tree_inorder.c`: Performs an inorder traversal on the binary tree.
- `8-binary_tree_postorder.c`: Performs a postorder traversal on the binary tree.
- `9-binary_tree_height.c`: Computes the height of the binary tree.
- `10-binary_tree_depth.c`: Computes the depth of a node in the binary tree.
- `11-binary_tree_size.c`: Calculates the size (number of nodes) of the binary tree.
- `12-binary_tree_leaves.c`: Counts the number of leaf nodes in the tree.
- `13-binary_tree_nodes.c`: Counts the number of non-leaf nodes in the tree.
- `14-binary_tree_balance.c`: Calculates the balance factor of the tree.
- `15-binary_tree_is_full.c`: Checks if the binary tree is full.
- `16-binary_tree_is_perfect.c`: Checks if the binary tree is perfect.
- `17-binary_tree_sibling.c`: Finds the sibling of a node.
- `18-binary_tree_uncle.c`: Finds the uncle of a node.
- `binary_tree_print.c`: A helper function for printing binary trees (not part of the core requirements but useful for visualization).
- `binary_trees.h`: The header file containing function prototypes and necessary data structures.
- `README.md`: This file.

## Compilation

To compile the project, use the following command in your terminal:

```bash
gcc -Wall -Wextra -Werror -pedantic *.c -o binary_trees

## Functions Implemented
This project implements various functions that manipulate and query binary trees, including:

- **Insertion Functions**: Insert nodes to the left or right of a parent node.
- **Traversal Functions**: Preorder, inorder, and postorder tree traversal.
- **Tree Analysis Functions**: Compute tree height, size, balance, depth, and check properties like being full or perfect.
- **Node Property Functions**: Check if a node is a leaf or the root, and find the sibling or uncle of a node.

## Additional Information
- **Memory Management**: The functions in this project manage memory dynamically, ensuring that nodes are created and deleted properly when necessary.
- **Tree Traversal**: The project demonstrates various ways to traverse a binary tree, providing foundational knowledge on tree structures and algorithms.
- **Helper Functions**: Some helper functions like `binary_tree_print.c` are included for visualization during testing and debugging.

## Authors
This project was created as part of the Holberton School curriculum.
Sindi Bardhi, Mario Melengu.

## License
This project is licensed under the terms of the Holberton School.
