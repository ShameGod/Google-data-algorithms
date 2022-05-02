# Google-data-algorithms
Following the course Google data &amp; algorithms 

## Maps and Doctionaries
Arrays: allow us to store elements of the same type in memory. It is possible to access each element just by indicating its index.
When creating the array we need to specify its size. 

Linked list: This data structure can grow, since each component contains a value and a pointer to the next value 
![image](https://user-images.githubusercontent.com/42012627/166197844-1f4c34f1-8fee-4b47-9139-98a0dc5837ae.png)

The draw back of having a dynamic size with linked lists is that we lose random access of elements. To find an element it is necessary to go through all the linked list. The worst case scenario is o(n) which isn't efficient. 

Hash tables : 
this data structure is adapted for insert, delete and lookup opertations :
![image](https://user-images.githubusercontent.com/42012627/166198264-43c7e7a6-f0a1-46ac-80f8-f739e99d61e0.png)
A hash table data structure has a key and value. The key is hashed through a consistent hash function. By consistant, I mean that it will always return the same result for the same input key. The hash function indicates where in the hash table the element is. For example the hash function bellow puts elements in the hash table according to their alphabetical order
![image](https://user-images.githubusercontent.com/42012627/166198626-2072c951-f22c-4e2c-b976-e5a8e55040f2.png)
Since we already know where each element should be according to its hashed key, we only need to lookup a single part of the table.

