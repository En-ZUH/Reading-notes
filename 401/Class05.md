# Linked Lists

## What Is a Linked List?

A linked list is a a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link, linear data structure that contains a sequence of nodes, and made up of data elements or nodes that are linked together by pointers, in which each node contains data and a pointer to the next node. The most common example is a singly linked list, where each node contains a piece of data and a pointer to the next list, as shown in the diagram below.

![](https://people.engr.ncsu.edu/efg/210/s99/Notes/LLdefs.gif)
![linked-list](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/Linkedlist-2.png)

***️

## The element of linked list:

1. Nodes: are the individual items/links that live in a linked list. Each node contains the data for each link ( the single item in the linked list that's holds the data).

2. Head: is a reference type of type Node to the first node in a linked list.

3. Next: Each node contains a property called Next. This property contains the reference to the next node, it will lead us where the next node  is and allow us to extract the data appropriately ( the final element isn't node but reference to null).

4. Current : regers to node currently being looked at, and when we do some operations to the linked list, we define the current as the head node to ensure we start at the beginning.

***️

## Types of Linked List


* singly Linked List => Item navigation is forward only (which means that there is only one reference, and the reference points to the next node in a linked list).

* Doubly Linked List => Item can be navigated forward and backward (which means that there is a reference to both next and previous nodes).

* Circular Linked List => Last item contains link of the first element as next and the first element has a link to the last element as previous (which means that there is a reference from the last node to the first node.)

***️

## Basic Operations


* Insertion => Adds an element at the beginning of the list.

* Deletion =>  Deletes an element at the beginning of the list.

* Display =>  Displays the complete list.

* Search => Searches an element using the given key.

* Delete => Deletes an element using the given key.

***️

### Advantages for linked lists: 

* Insertion and deletion operations are easier.

* Efficient memory utilization.

* Linked list can expand in constant time.

* Linked is a dynamic data structure.

***

### DisAdvantages of linked lists:

* Reverse Traversing is difficult in the linked list(though we can achieve this with the help of Doubly Linked List).

* The memory is wasted as pointers require extra memory for storage.

* No element can be accessed randomly, it has to access each node sequentially i.e. proper traversal must be done.

***

#### Refrences

* [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
* [What’s a Linked List, part1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
* [What’s a Linked List, part2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

