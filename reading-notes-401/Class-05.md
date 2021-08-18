# Linked Lists

## What is a Linked List

* A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

* There are two types of Linked List - Singly and Doubly.

* Singly Linked List looks like :

![Singly Linked List](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/LinkedList1.PNG)

* Traversal :

When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing. The Next property is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

The best way to approach a traversal is through the use of a while() loop. This allows us to continually check that the Next node in the list is not null.

* Traversal Example

```
ALGORITHM Includes (value)
// INPUT <-- integer value
// OUTPUT <-- boolean

  Current <-- Head

  WHILE Current is not NULL
    IF Current.Value is equal to value
      return TRUE

    Current <-- Current.Next

  return FALSE
```

## What is Linear data structures

* One characteristic of linked lists is that they are linear data structures, which means that there is a sequence and an order to how they are constructed and traversed.

## Memory management

* The biggest differentiator between arrays and linked lists is the way that they use memory in our machines.

* arrays are static data structures, while linked lists are dynamic data structures.

* ![Memory management](https://miro.medium.com/max/875/1*G43FVT5xJ1n1QDKVNZUxXQ.jpeg)

## What is Big O

* Big O notation is a way to express the amount of time that a function, action, or algorithm takes to run based on how many elements we pass to that function.

* Basic Big O Notation Equations :

![Basic Big O Notation Equations](https://miro.medium.com/max/625/1*FC0XX0-9Vx7yCS0dTS2Zrw.jpeg)
