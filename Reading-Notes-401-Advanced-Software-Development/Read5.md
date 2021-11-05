# Linked Lists

![Image of linked list](https://miro.medium.com/max/953/1*iiEWrP2IznA6HbmuIdK0lQ.png)
![Image of linked list 2](https://image.slidesharecdn.com/singlelinkedlist-100513043540-phpapp01/95/single-linked-list-1-728.jpg?cb=1564668339)

## purpose f linked lists:

- A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

- There are two types of Linked List - Singly and Doubly. We will be implementing a Singly Linked List in this implementation.

- Linked List - A data structure that contains nodes that links/points to the next node in the list.

- Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.

- Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.

- Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.

- Next - Each node contains a property called Next. This property contains the reference to the next node.

- Head - The Head is a reference type of type Node to the first node in a linked list.

- Current - The Current reference is a reference type of type Node that is currently being looked at. This node is traditionally used when traversing through a full linked list. When traversing, you typically reset the current to the head to guarantee you are starting from the beginning of the linked list.

### Memory management
- The biggest differentiator between arrays and linked lists is the way that they use memory in our machines. Those of us who work with dynamically typed languages like Ruby, JavaScript, or Python donâ€™t have to think about how much memory an array uses when we write our code on a day to day basis because there are several layers of abstraction that end up with us not having to worry about memory allocation at all.
![Memory management](https://miro.medium.com/max/700/1*G43FVT5xJ1n1QDKVNZUxXQ.jpeg)



## Linked List?
- O(1) : means i need a constant time & and same space, and doesn't matter how much the elements we have or how huge our input is.
- O(n) : means that as our input grows, the space and time that we need to run that algorithm grows linearly.
- a linked list is usually efficient when it comes to adding and removing most elements, but can be very slow to search and find a single element.
 data structures : ways of organizing our data.
- linked lists are a linear data structure, that means we traversed over the data sequentially.
- arrays and linked lists are linear data structure.



### When constructing your code, a few things to keep in mind.

- When making your Node class, consider requiring a value to be passed in to require that each node has a value.

- When making a Linked List, you may want to require that at least one node gets passed in upon instantiation. This first node is what your Head and Current will point too.

## types of linked lists:

- doubly linked lists: those contain an addetional refrence that points to the previous node.
- singly linked lists: those contain only one refrence that points to the next node in sequence.

## diferences between linked lists and arrays:

- arrays are stored in contigious block of data whereas linked lists nodes can be stored seperatly.
- arrays can be faster in finding particular elements inside it whereas linked lists needs time to find a particular element.
- linked lists are faster in adding and deleting nodes and array are slower in deleting one of its elements.

## the BigO:

the bigO or the big order notation focuses on how fast our code run in relation to the input when the input reaches infinity.  
it concerns itself with 2 main parts which are:

- the time complexity: which means how many times does the cpu run a specific algorithm.
- the space complecity: how much do we store in our memory in during that algorithm.