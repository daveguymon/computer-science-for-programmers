## Binary Tree

A binary tree is a non-linear data structure that organizes data by nodes in a hierarcy. Each node in a binary tree consists of three parts:
  1. a data element,
  2. a pointer to the left sub-tree, and
  3. a pointer to the right sub-tree.
Unlike general trees, a binary tree limits each node to having no more than two sub-nodes. Another way of describing this characteristic is that a binary tree has a branching factor of two.

                                   15
                                  /  \
                                 /    \
                                /      \
                              13        20
                             /  \       / \
                            /    \     /   \
                           9     14   18   23
                          / \    / \ / \   / \
                         n   n  n  n n  n n   n

Binary trees must have a minimum of two levels, the topmost root node and two sub-nodes connected to the root node by branches. There is no limit to the amount of levels a binary tree can have, though search algorithms perform better on shorter trees.

Each node (apart from the root) that has at least one sub-node is called a parent node.

Each node that is branched directly from a parent node is called a child node.

Nodes that do not have any child nodes are called leaf nodes.

Nodes between the tree's root node and leaf nodes are called internal nodes.
