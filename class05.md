# **Linked List**

#### Linked list: is a linear collection of data elements whose order is not given by their physical placement in memory. Instead, each element points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence. In its most basic form, each node contains: data, and a reference (in other words, a link) to the next node in the sequence. This structure allows for efficient insertion or removal of elements from any position in the sequence during iteration. More complex variants add additional links, allowing more efficient insertion or removal of nodes at arbitrary positions. A drawback of linked lists is that access time is linear (and difficult to pipeline). Faster access, such as random access, is not feasible. Arrays have better cache locality compared to linked lists.
from(Wikipedia) 

### Types of Linked List:
#### * Simple Linked List: Item navigation is forward only.
#### * Doubly Linked List: Items can be navigated forward and backward.
#### * Circular Linked List: Last item contains link of the first element as next and the first element has a link to the last element as previous.

#### The first and last node of a linked list are called the head and tail of the list, we can traverse the list starting at the head and ending at the tail. The tail node is a special node, where the next pointer is always pointing or linking to a null reference, indicating the end of the list.

#### When traversing a linked list,  we can't use forEach or for loop. 
#### The best way is to use a while() loop, so we can check the next node in the list is not null. If it is null, a NullReferenceException gets thrown and the program will crash.

#### The current node tells us where we are in the linked list and it allows us to traverse forward until we hit the end.