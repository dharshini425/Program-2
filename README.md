PROGRAM-2-A
C-MODULE 2
EX_NO-02)a)-Loop
Date: 24-12-2025
Name: dharshini T
Register Number:25018056
AIM:
Write a C Program to print the string "LINUX" n number of times.

ALGORITHM:

Start the program.

Declare an integer variable to store the input value.

Read the integer value from the user using the scanf function.

Use a for loop starting from 1 to the input value:

a. In each iteration, print "LINUX".

End the program.

PROGRAM:
```
#include <stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    for(int i=1;i<=num;i++)
    {
        printf("LINUX\n");
    }
return 0;
}
```
OUTPUT:

 
RESULT:

Thus the program to print the string "LINUX" n number of times has been executed successfully



Program-2-b
C-Module 2
EX_NO-02)b)-Nested Loops
Date: 24-12-2025
Name: DHARSHNI T
Register Number:25018056

AIM:
write a c program to print hollow rectangular pattern

ALGORITHM:
Start the program.

Declare two integer variables to store the number of rows and columns.

Read the values of rows and columns from the user using the scanf function.

Use a for loop from 1 to the number of rows:

a. Inside this loop, use another for loop from 1 to the number of columns:

 i. If the current row or column is the first or last, print "*".

 ii. Otherwise, print a space " ".
b. After the inner loop, move to the next line using printf("\n").

End the program.  
  
  PROGRAM:
  ```
#include<stdio.h>
void mul(float a,float b){
    float c=a*b;
    printf("Multiplication: %.f",c);
}
void div(float a,float b)
{
    float c=a/b;
    printf("\nDivision: %.6f",c);
}
int main()
{
    float a,b;
    scanf("%f\n%f",&a,&b);
    mul(a,b);
    div(a,b);
}
```
OUTPUT:
 
RESULT:
Thus the program to perform multiplication and division of two numbers using functions (With argument and without type) has been executed sucessfully


program-2-C
C-Module 2
EX_NO-02)c)-FUNCTIONS
Date: 24-12-2025
Name: DHARSHINI T 
Register Number:25018056
AIM:
Write a C program to perform multiplication and division of two numbers using functions (With argument and without return type).

ALGORITHM:
Start the program.

Declare two float variables to store the input numbers.

Read the two float numbers from the user using the scanf function.

Define a function to perform multiplication:

a. Take two float arguments.

b. Multiply the two numbers and store the result.

c. Print the multiplication result.

Define a function to perform division:

a. Take two float arguments.

b. Divide the first number by the second and store the result.

c. Print the division result with six decimal places.

In the main function, call the multiplication function with the input numbers.

Call the division function with the input numbers.

End the program.

PROGRAM:
```
#include<stdio.h>
void mul(float a,float b){
    float c=a*b;
    printf("Multiplication: %.f",c);
}
void div(float a,float b)
{
    float c=a/b;
    printf("\nDivision: %.6f",c);
}
int main()
{
    float a,b;
    scanf("%f\n%f",&a,&b);
    mul(a,b);
    div(a,b);
}
```
OUTPUT:

RESULT:
Thus the program to perform multiplication and division of two numbers using functions (With argument and without return type) has been executed successfully


Program-2-d
C-Module 2
EX_NO-02)d)-LOOPS
Date: 24-12-2025
Name: DHARSHINI T
Register Number:25018056
AIM:
Write a c program to find the sum of Odd digits using while loop in a Given range

ALGORITHM:
Start the program.

Declare three integer variables: num1, num2, and sum. Initialize sum to 0.

Read two integer values (num1 and num2) from the user using scanf.

Assign the value of num1 to a variable n.

Use a while loop that runs as long as n is less than or equal to num2:

a. Check if n is an odd number (n % 2 != 0). i. If true, add n to sum.

b. Increment n by 1.

After the loop ends, print the value of sum.

End the program.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,n,sum=0;
    scanf("%d\n%d",&num1,&num2);
    n=num1;
    while(n<=num2){
        if(n%2!=0)
        {
            sum+=n;
        }
        n++;
    }
    printf("%d",sum);
}
```
OUTPUT:

RESULT:
Thus the program to find the sum of Odd digits using while loop in a Given range has been executed successfully

Program-2-e
C-Module 2
EX_NO-02)e)-LOOPS
Date: 24-12-2025
Name: DHARSHINI T
Register Number:25018056
AIM:
Write a C program to print the multiplication table of a given number using do while loop within the certain limit or range

ALGORITHM:
Start the program.

Declare three integer variables: num1, num2, and i. Initialize i to 1.

Read two integer values (num1 and num2) from the user using scanf.

Use a do-while loop that runs as long as i is less than or equal to num2:

a. Multiply num1 by i and store the result in a variable mul.

b. Print the value of mul followed by a space.

c. Increment i by 1.

End the program.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,i=1;
    scanf("%d\n%d",&num1,&num2);
    do{
        int mul=num1*i;
        printf("%d ",mul);
        i++;
    }while(i<=num2);
}
```
OUTPUT:

RESULT:
Thus the program to print the multiplication table of a given number using do while loop within the certain limit or range has been executed successfully



      
