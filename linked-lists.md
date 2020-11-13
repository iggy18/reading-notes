# linked lists

- A Linked List is a sequence of Nodes that are connected/linked to each other.
- There are two types of Linked List - Singly and Doubly.
- a linked lists is A data structure that contains nodes that links/points to the next node in the list.
- a singly linked list only has one reference
- a doubly linked list has two references within the node.
- Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
- each node contains a property called next which contains a reference to the next node.
- head is a reference type node at the head of the list.
- current is a reference to the node that is currently being looked at.
- you cant use for each or for loops to traverse a linked list. you have to use the next value.
- the best way to aproach traversal is to use a while loop.
the current node will tell us where we are in a linked list.

- first set current to the head.
- create a while loop to run if the noe that current is pointing to is not null
- while in the while loop if the value we are looking for is true we return true.
- if the Current node does not contain the value we are looking for, we then must move Current to the next node that is being referenced.
- Once we hit the end, we know that we did not find the value and return true at any point, so the value is not in the LinkedList. We return false.

## adding a node.
- Set Current equal to Head. This will guarantee us that we are starting from the very beginning.
- We can then instantiate the new node that we are adding. The values passed in as arguments into the Add() method will define what the value of the Node will be.
- when you add a new node it takes takes over the head role so you have to reasign the old head of the list so its not the head and tell the new node it IS the head

