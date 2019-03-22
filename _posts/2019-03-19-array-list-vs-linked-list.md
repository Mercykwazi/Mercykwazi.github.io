---
Layout:
Title: "Linked-list vs Array-list"
date: 2019-03-19 09:40
categories:
---

# Array-List vs Linked-List

In Java array list and linked list are very similar the only difference is implementation which causes different performance for different operations.
ArrayList is implemented as a seizable array which means that you can edit the size of this array by adding and removing things.
LinkedList is implemented as a double linked list.It performs adding and removing things on the array much better than the array list but its get and set is worse than the arrayList.
Linked list implements a queue interface which adds more methods than ArrayList.

The arrayList capacity is small,it is there for important to construct the ArrayList with a higher initial capacity,in this way you avoid resizing costs.
If your program is thread-safe it is better to use an ArrayList.LinkedList if faster in add and remove but slower in get method
