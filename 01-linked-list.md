# Linked Lists

A link list is a data structure used for storing collections of data. 

group of vertices (nodes) which together represent a sequence. Under the simplest form, each vertex is composed of a data and a reference (link) to the next vertex in the sequence. 

A linear DS
## Properties
* successive elements are connected by pointers
* last element points to `Null`
* Can grow or shrink in size during execution of a program
* Can be made as long as needed (memory limits permitting)
* it does not waste memory space but takes some memory to store the pointers

## Usage
Linked List and its variations are used as underlying data structure to implement List, Stack, Queue, and Deque ADTs

## Methods
### Create
### Insert
For insert(i, v), there are four (legal) possibilities, i.e. item v is added to:
1. The head (before the current first item) of the linked list, i = 0,
2. An empty linked list (which fortunately similar to the previous case),
3. The position beyond the last (the current tail) item of the linked list, i = N,
4. The other positions of the linked list, i = [1..N-1].
### Remove
### Search