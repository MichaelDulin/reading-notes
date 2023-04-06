# Linked Lists

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 1**
- [Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
- [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
- [What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
- [What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

##Linked List Cheat Sheet

**Linear List**
- Components:
  - Head: 
    - Starting reference of first node in LL 
  - Node:
    - One part of the LL
    - Only contains it's data and a reference to the next node in LL
    - Last node reference is null
      - Node.Next(reference) = null indicates we have reached the end of the LL
  - Reference:
    - Indicator to next node
    - Without these references, our data cannot be accessed  

**Other Linked Lists**
- Doubly Linked List:
  - Similar to Linear LL but has two references
    - Allows us to traverse forward and back 
    - Each Node contains both references

- Circular Linked List:
  - Unique in it's referencing:
    - Sets the tail node's next reference as the first value in LL
    - Isolates tail node outside of looped LL 
      - Allows for much easier adding / removing nodes to / from LL   
