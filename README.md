0x18. C - Stacks, Queues - LIFO, FIFO
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language

Table of contents
File  Description
main.c	entry point of the program
monty.h	main header file
lists.h	header file for the lists functions
get_func.c     function that picks the right function for the instruction
handler_funcs1.c	handler functions for the instructions
handler_funcs2.c	handler functions for the instructions
handler_funcs3.c	handler functions for the instructions
list_funcs1.c		doubly linked list functions
list_funcs2.c		doubly linked list functions
strtow.c		string tokenizing functions
free.c			memory handling functions
char.c			handler functions for ascii instructions