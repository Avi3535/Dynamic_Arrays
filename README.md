# Dynamic_Arrays

One advantage of linked lists over static arrays is that the size of the list is dynamic. That is, its length can be increased or decreased as required. 

But there is one more way of implementing arrays where the size can be dynamically increased and such an array is called a dynamic array.

In this programs a dynamic array is implemented where an input is asked from the user and if the size is full then a new array created using 'malloc' and 'realloc'. In this program calloc is not used as it very similar to malloc except that in calloc then elements will be initialized to zero as opposed to garbage values in malloc.  
