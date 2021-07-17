# Bubble_sort_using_dynamic_memory_allocation
This code is written by Visual Studio 2022 (Preview). Hopefully this code will compile in any C++ compiler. If you are not using Microsoft Visual Studio then you will find source code in "Bubble sort using dynamic memory allocation/Bubble sort using dynamic memory allocation.cpp" For more information read "README.md". Thank you.



 Line 1 :
 This is a header file.
 It declares a set of functions for standard Input/Output.
 It also defines I/O stream objects such as cin, cout, clog, etc.

 Line 2 :
 Computer does not know the code of built-in functions.
 namespace std tells the computer "If you find something that is not declared in the current scope go and check std".
 It is because computer needs to know the code for the cout, cin functionalities and it needs to know which namespace they are defined.

 Line 3 :
 Main function starts here.
 Computer will execute every line from below it.

 Line 5 :
 Declaring a variable.
 Variable name is "size" which datatype is an integer.
 It means that size will only contain integer values.

 Line 6 :
 Declaring an array.
 Array name is "array".
 It is not necessary to declare array name by "array".
 An array is a collection of elements of the same type placed in contiguous memory locations that can be individually referenced by using an index to a unique identifier.

 Line 7 :
 "cout" is an object of class ostream.
 It is defined in iostream header file.
 It is used to display the output to the standard output device.
 It will display "Enter size of array : ".

 Line 8 :
 "cin" is an object of class istream.
 It is used to accept the input from the standard input device.
 It accepts a value form user and put it in "size".

 Line 9 :
 "array" is a variable.
 The new operator denotes a request for memory allocation on the Free Store.
 If sufficient memory is available, new operator initializes the memory and returns the address of the newly allocated and initialized memory to the pointer variable.

 Line 10 :
 "for loop" starts at here.
 A "for loop" is a repetition control structure that allows you to efficiently write a loop that needs to execute a specific number of times.
 "int i = 0" means the value of "i" is "0".
 "i < size" means that the value of "i" is smaller than the value of "size".
 "i++" is an increment operator.
 The value of "i" is incremented according to the execution of "for loop".

 Line 12 :
 "cout" is an object of class ostream.
 In this line it will display "Enter element " and the value of "i".

 Line 13 :
 In this line "cin" accepts the values and stored in "array[i]".

 Line 14 :
 For loop ends at here.

 Line 15:
 Declaring a variable and assigning a value in it.
 Variable name is "counter" which datatype is an integer.
 "1" is assigned to the variable name "counter".

 Line 16 :
 This is a "while loop".
 A while loop statement repeatedly executes a target statement as long as a given condition is true.
 If the value of "counter" is smaller than the value of "size" then the "while loop" will execute.

 Line 18 :
 "for loop" starts at here.
 A for loop is a repetition control structure that allows you to efficiently write a loop that needs to execute a specific number of times.
 "int i = 0" means the value of "i" is "0".
 "i < size - counter" means that the value of "i" is smaller than the value of "size - counter".
 "i++" is a increment operator.
 The value of "i" is incremented according to the execution of "for loop".

 Line 20 :
 "if" statements start here.
 "array[i] > array[i + 1]" is true then the "if" statement will be executed.

 Line 22 :
 Here "temp" is a variable.
 Datatype of “temp” is integer.
 In this line the value of "array[i]" is assigned to "temp".

 Line 23 :
 Here the value of "array[i+1]" is assigned to "array[i]".


 Line 24 :
 Here the value of "temp" is assigned to "array[i+1]".

 Line 25 :
 if statement ends at here.

 Line 26 :
 For loop ends at here.

 Line 27 :
 "counter++" is an increment operator.
 The value of "counter" is incremented according to the execution of "while loop"

 Line 28 :
 While loop ends at here.

 Line 29 :
 "for loop" starts at here.
 A "for loop" is a repetition control structure that allows you to efficiently write a loop that needs to execute a specific number of times.
 "int i = 0" means the value of "i" is "0".
 "i < size" means that the value of "i" is smaller than the value of "size".
 "i++" is an increment operator.
 The value of "i" is incremented according to the execution of "for loop".

 Line 31 :
 In this line "cout" display the values stored in array.

 Line 32 :
 For loop ends at here.

 Line 33 :
 "delete[]" deletes the created array and release the memory.

 Line 34 :
 Return statement stops the execution of the program, and 0 or 1 will denote the execution status.
 "return 0" in the main function means that the program executed successfully and if it is defined by a user it means that the user-defined function is returning false.
 "return 1" in the main function means that the program does not execute successfully and there is some error and if it is defined by a user it means that the user-defined function is returning true.

 Line 35 :
 Main function finishes at here.
