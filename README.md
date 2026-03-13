# c-doubly-linked-list

This project demonstrates a simple implementation of a **c-doubly-linked-list**.  
It includes functionality for creating elements, appending nodes, deleting nodes, printing the list (forward and reverse), and finding the maximum value.

## Features

- Create a new list element
- Append elements to the end of the list
- Print the list in forward order
- Print the list in reverse order
- Delete the head node
- Delete a node by value
- Find the maximum value in the list

## Data Structure

The program uses the following doubly linked list structure:

```c
struct List {
    struct List *nextp;
    struct List *prevp;
    int data;
};
