# Class 5 Reading: Linked Lists

## Sources

- [Big O: Analysis](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
- [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
- [What's a Linked List, pt 1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
- [What's a Linked List, pt 2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

### Linked Lists

1. Contribute to the discussion by teaching something that you have learned, then review what one of your classmates learned and leave a comment. Below, there is a list of ideas you might want to teach.

- Use an analogy.

  - For example, you might explain a Linked List like a scavenger hunt, a treasure map, or an old-school video game like Pitfall.

- Explain a detail in depth.

  - For example, you might explain how a node is a self-referential class, or how a Linked List is similar to an array.

- Use WHY, WHAT, HOW structure.

  - For example, you might explain why a Linked List is useful, what it is, and how it works.

- Tutorial / walk through an example.

  - For example, you might write a step-by-step guide to building a Linked List.

- Write a quiz.

  - For example, you might write a quiz about Linked Lists.

- Create a vocabulary/definition list.

  - For example, you might create a list of terms and definitions related to Linked Lists.

- Anthropomorphize the concepts, and write a conversation between them.

  - For example, you might write a conversation between a node and a Linked List.

- Build a mpa of the information.

  - For example, you might create a diagram of a Linked List.

- Construct a fill-in-the-blank worksheet.

  - For example, you might create a worksheet about Linked Lists.

## My Linked List Tutorial

1. Linked Lists in JavaScript:

   - A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers. In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.

2. Node Structure:

   - A linked list is represented by a pointer to the first node of the linked list. The first node is called the head. If the linked list is empty, then the value of the head is NULL. Each node in a list consists of at least two parts:

     - data
     - Pointer (Or Reference) to the next node

3. Creating a Linked List:

    - To create a linked list, you need to define a node structure and initialize the list with a head pointer that initially points to `null`, indicating an empty list.

4. Inserting Nodes:

    - Inserting a node in a linked list involves the following steps:

      - Create a new node with the given data and next pointer as `null`.
      - Check if the linked list is empty, then make the new node as head.
      - Else, traverse the list till the last node and insert the new node at the end of the list.

5. Deleting Nodes:

    - Deleting a node from a linked list involves the following steps:

      - If the list is empty, then return.
      - Else, search for the node to be deleted.
      - If the node is found, then check if it is the head node.
      - If it is, then change the head pointer to the next node.
      - Else, change the next pointer of the previous node of the node to be deleted to the next node.
      - Free memory for the node to be deleted.

6. Traversing the Linked List:

    - Traversing a linked list is similar to traversal of a one-dimensional array. We just need to start from the head node and keep on traversing the next nodes till we reach the end of the list.

## My Linked List Walkthrough

1. Create a Node class:

   - ![Step 1](/img/linked-list-step1.png)

2. Node structure:

   - ![Step 2](/img/linked-list-step2.png)

3. Creating a Linked List:

   - ![Step 3](/img/linked-list-step3.png)

4. Inserting Nodes:

   - ![Step 4](/img/linked-list-step4.png)

5. Deleting Nodes:

   - ![Step 5](/img/linked-list-step5.png)

6. Traversing the Linked List:

   - ![Step 6](/img/linked-list-step6.png)
