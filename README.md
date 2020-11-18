# Rube Goldberg Machine

## What is a Rube Goldberg Machine?
This is an attempt to build a virtual Rube Goldberg machine to practice with some of the data structures (Linked Lists, Queues, Stacks, and Trees). A Rube Goldberg Machine is a complex device that performs simple tasks in indirect and convoluted ways Reuben Goldberg was an American engineer who changed his career to cartoonist. He was famous for his political cartoons and satire. However, the works which would lead to his lasting fame involved a character named Professor Lucifer Gorgonzola Butts shown in the following cartoon. 
<br>

<img src = "assets/Professor Lucifer Gorgonzola Butts.PNG" align = "left"> In this series, Goldberg drew absurd inventions that would later bear his name: Rube Goldberg Machines. Rube Goldberg received the Pulitzer prize for his satire in 1948. Today there are several contests around the world known as Rube Goldberg contests, which challenge high school students to make complex machines to perform a simple tasks.  These contests are not only fun, but they challenge students to practice fundamental engineering, physics, and mechanical principles as well as encourage creativity. They must utilize a specified number of various simple machines, using common junk and household items to perform absurdly simple tasks such as cracking open and egg, opening a door, ringing a bell, and so forth.

<br>

## Description
Creating a virtual Rube Goldberg Machine with ADTs. The ADTs used includes the queue, stack, binary tree, heap, and many of the associated operations on these ADTs. One way to approach the problem is to think about the functionality from the user’s perspective. This is a reasonable place to start, however we should think in terms of the application being composed of ADTs and operations upon them. The ADTs will contain the data and with each ADT, there are lots of operations upon them.
<br>

<img src = "assets/Queue.PNG" height = "230" width = "450"> <img src = "assets/Stack.PNG" height = "200" width = "300"> <img src = "assets/BinaryTree.PNG" height = "200" width = "430"> <img src = "assets/Heap.PNG" height = "200" width = "340">

<hr>
<br>

## Data-Structures with Real-Life Examples

### Linked List
A linked list is a linear data structure, in which the elements are not <img src = "assets/linked list.jpg" height = "125" align = "right"> stored at contiguous memory locations. The elements in a linked list are linked using pointers. In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.

<br>

### Queue
<img src = "assets/queue-eg.jpg" height = "125" align = "left"> A Queue is a linear structure which follows a particular order in which the operations are performed. The order is First In First Out (FIFO). A good example of a queue is any queue of consumers for a resource where the consumer that came first is served first. In a queue, we remove the item that is least recently added.

<br>

### Stack
Stack is a linear data structure which follows a particular order in which <img src = "assets/stack-example.png" height = "125" align = "right"> the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out). There are many real-life examples of a stack. Consider an example of plates stacked over one another in the canteen. The plate which is at the top is the first one to be removed, i.e. the plate which has been placed at the bottommost position remains in the stack for the longest period of time. So, it can be simply seen to follow LIFO(Last In First Out)/FILO(First In Last Out) order.

<br>

### Tree
<img src = "assets/egtree.png" height = "135" align = "left"> A Tree is a recursive data structure containing the set of one or more data nodes where one node is designated as the root of the tree while the remaining nodes are called as the children of the root. The nodes other than the root node are partitioned into the non empty sets where each one of them is to be called sub-tree. Nodes of a tree either maintain a parent-child relationship between them or they are sister nodes.
