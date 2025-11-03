# Assignment-C-programming
1. What do you mean by Arrays? Give
one example of array and how you can declare an array.
Definition:
An array is a collection of similar data types stored at contiguous memory locations.
It helps to store multiple values in a single variable instead of declaring separate variables.
Example:
#include <stdio.h>
int main() f
int marks[5] =[85,90,78,88,92；1/
declaration and initialization of array
printf("First student marks:%d",marks[0]);
return 0;
Explanation:
int marks[5];→ declares an array of 5integers.
marks[0] → represents the first element of the array.
2.What do you mean by Functions?Write the types of functions and give one example in code of each type.
Definition:
A function is a block of code that performs a specific task.
It helps in code reusability and easy debugging.
Types of Functions:
1.Library (Predefined) Function
2.User-defined Function
(a) Library Function Example:
#include <stdio.h>#include <math.h>int main()[
double result = sqrt(25)；1/ using
predefined sqrt() function
printf("Square root:%.2f", result);return 0;
(b) User-defined Function Example:
#include <stdio.h>
void greet()f 1/ function definition
printf("Hello, welcome to C programming!");
人
int main() f
greet();
return 0;
1/ function call
子
3. What do you mean by Pointers?Write a code how you can initialize the pointer.
Definition:
A pointer is a variable that stores the memory address of another variable.
Example Code:
#include <stdio.h>
int main() f
int num = 10;int *ptr;1/ pointer declaration
ptr = &num;pointer initialization
printf("Value of num:%d\n",num);printf("Address of num:%pln", ptr);
printf("Value using pointer:%d\n", *ptr);return 0;
人
Explanation:
*ptr -→ pointer variable.
&num -→ gives address of variable num.
tptr -→ gives value stored at that address.
4.What are the types of Array?Write in code (1D & 2D included).
Types of Arrays:
1.One Dimensional (1D) Array
2.Two Dimensional (2D) Array
3. Multi Dimensional Array
(a) One Dimensional Array
Example:
#include <stdio.h>
int main() f
int numbers[5]=(1，2，3，4，5)；
for(int i= 0;i<5;i++)[
printf("%d "，numbers[i]);
return 0;
子
(b) Two Dimensional Array Example:
#include <stdio.h>
int main()[
int matrix[2][3]=f
11，2，3)，
14，5，60
for(int i=0;i<2；i++)[
for(int j=0;j<3；j++)f
printf("%d",matrixli]lj]);printf("\n")；
return 0;
5.Explain the types of Operators in code.
Operators in C:
Operators are special symbols that perform
operations on operands (variables or values).
Types of Operators:
Type
Example
Descrir
Arithmetic
+
大
/%
Mather
operati
Relational
<=i
<>=<=
Compe
Logical
Assignment
&&
=/=*
Assign
Increment/Decrement
Increas
valuet
十十
へVYく
&
Bitwise
Example Code:
C
0Copy code
#include <stdio.h>
int main()f
int a = 10, b=5;
1/ Arithmetic
printf("Addition:%d\n", a + b);
1/ Relational
printf("Is a > b? %d'n", a >b);
1/ Logical
printf("Logical AND:%d\n", (a >b) && (b>0))；
1/ Assignment
a += b;/l a=a + b
printf("After assignment:%d\n", a);
1/ Increment/Decrement
a++;
printf("After increment:%d\n",a);
return 0;
