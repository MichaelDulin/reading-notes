# Trees

[Back to main](https://michaeldulin.github.io/reading-notes)

**Trees Resources**
- [Trees]([https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html))

****

**Common Terminology**
- Node:
  - A Tree node is a component which may contain its own values, and references to other nodes
- Root:
  - The root is the node at the beginning of the tree
- K:
  - A number which specifies the maximum number of children any node may have 
- Left:
  - A reference to one child node in a binary tree
- Right:
  - A reference to another child node in a binary tree
- Edge:
  - The edge in a tree is the link between a parent and child node
- Leaf:
  -  A leaf is a node that does not have any children
- Heaight:
  - The height of a tree is the number of edges from the root to the furthest leaf

**Traversals**
- Depth First: 
  - Priorite going throught the depth(height) of the tree first
  - Pre-order:
    - root -> left -> right 
  - In-order:
    - left -> root -> right
  - Post-order: 
    - left -> right -> root 
- Breadth First:
  - Iterates through the tree by going through each level node-by-node
  - Linear 

**K-ary Trees**
- Nodes are able to have more than to children
- 'K' refers to the max # of children each node may have

**Binary Search Tree (BST)**
- Does not have a specified structure as it stores value in numerical order
- Values are placed differently depending on their size:
  - Right:
    -  if value is larger than current node
  - Left:
    -   if value is smaller than current node 
  - Adding values continue in this fashion, where earlier added values are further up and closer to root












