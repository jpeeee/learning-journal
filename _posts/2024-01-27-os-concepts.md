# Operating Systems Concepts

# Processes
A process is an instance of a program in execution.
Process memory is divided into four sections:
* Text section is the compiled program code that has been read from non-volatile memory when the program was launched.
* Data sction contains the global static variables allocated and initialised before entering main().
* Heap is a region of memory used for dynamic memory allocation (malloc, new)
* Stack is used for local variables. It is also used for function return values and to pass arguments to functions.

Typically, stack and heap start at opposite ends of the process memory space and grow towards each other. 
If they meet, it causes either a stack overflow error or a call to malloc or new will fail.

On Linux, a process is a thread.

https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/3_Processes.html
