# linked-list
Linked list Data Structure
In this tutorial, you will learn about linked list data structure and it's implementation in Python, Java, C, and C++.

A linked list is a linear data structure that includes a series of connected nodes. Here, each node stores the data and the address of the next node. For example,
![image](https://user-images.githubusercontent.com/125942960/234378586-0e1c65ee-2cc7-4f85-a4ec-5f2f7991775c.png)
Representation of Linked List
Let's see how each node of the linked list is represented. Each node consists:

A data item
An address of another node
We wrap both the data item and the next node reference in a struct as:
struct node
{
  int data;
  struct node *next;
};
