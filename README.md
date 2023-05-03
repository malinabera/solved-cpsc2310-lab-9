Download Link: https://assignmentchef.com/product/solved-cpsc2310-lab-9
<br>
Your task for this lab is to create a functions.c file you use to implement the 8 functions listed in functions .h

You will also need to write a driver.c file that will test each of the functions.  You are to use the <strong>C </strong>macro <strong>assert</strong> to test your functions. Assertions are statements used to test assumptions made by programmers. The syntax for assertions are as follows:

<strong>void assert(int expression);  </strong>

The expression should evaluate to true. If the assertion fails, a message will print that will list the file name and line the failure occurred on.




Example.  assert(5 &lt; 6); will pass so the program continues. However, assert(5 == 6); will fail, the program will stop and list the file name and line the assert failed.




Each of the functions you are going to implement has a short description of what the function is designed to do. It also lists the operations allowed when implementing the function.   Ex. int binaryAnd(int, int); this function basically implements the “&amp;” bit manipulator for integers. The legal ops represent the only operators you can use to implement the function. This means no other conditional or bit wise operators are allowed to be used.




Unless explicitly listed under legal ops, you <strong>cannot</strong> use any of the following:

Control constructs such as if, do, while, for, switch, etc.

Do not define any additional functions.

Do not call any functions within your function implementation.

Do not do any form of casting.

No arrays, structs, or unions allowed.




With respect to this lab, all of the functions you are implementing, can be implemented using the operations listed under legal ops.


