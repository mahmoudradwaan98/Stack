# Stack
Stack implementation using  C
** Stack Data structure based on Array: **

	1- in which all additions and deletions are restricted to one end and called the TOP

	2- LIFO structure --> last in first out, EX: Data IP: 5,10,15,20   Data  OP: 20,15,10,5

	3- if you insert data series into the stack and then remove it, Data order is reversed


** Basic Stack operations **

	1- Push data to the stack: insert data into the stack

	2- Pop data from the stack: remove data from the stack and return data to the calling module

	3- Stack top: returns data at the top of the stack without deleting data from the stack 


** Non-Mandatory Stack operations **

	1- Stack Init: initialize stack data types and pointers 

	2- Get stack size: get stack size ( no .of elements / no .of elements * size of one element)

	3- Display stack elements: Display stack content


** Push data to the stack **

	1- push adds an item at the top of the stack

	2- after the push, the new item becomes the top

	3- The only potential problem to be considered is that we must ensure that there is room for new items, here we create a helper function to check if the stack is full or not 

	4- if there is not enough room, the stack is in an overflow state and the item can not be added

	** Push data to the stacking procedure **

		1- check if the stack is not full, if the stack is full return an error to prevent stack overflow
		2- increment stack pointer by one
		3- update new location by data provided by the user

** Pop data from the stack **

	1- we remove the item from the top of the stack and return the value to the user 

	2- after removing the top item, the next older item in the stack becomes top 

	3- when the last item in the stack is deleted, the stack must be set to its empty state

	4- if pop is called when the stack is empty, it is an underflow state, here we can create a helper function to check if the state is empty or not 

	** Pop data from the stack **

		1- check if the stack is not empty, if the stack is empty return an error to prevent stack underflow
		2- set the value to data in the top node
		3- decrement stack pointer by one

** Stack top procedure **

1- check if the stack is not empty, if the stack is empty return an error to prevent stack underflow 

2- set the value to data in the top node
 




