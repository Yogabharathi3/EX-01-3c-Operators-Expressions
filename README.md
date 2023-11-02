# EX-01-1c-Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.
## ALGORITHM:
1. Declare variables to store the two fraction numbers and the result.
   
2. Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
 
3.Use the scanf function to read the numerator and denominator of the first fraction.

4. Repeat steps 2 and 3 to get the second fraction from the user.

5.Calculate the decimal values of both fractions by dividing the numerators by the denominators.

6.Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.

7.Print the minimum value.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b,min;
    scanf("%f %f",&a,&b);
    min = (a < b) ? a : b;
    printf("Minimum between %.3f and %.3f is %.3f",a,b,min);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-01-3c-Operators-Expressions/assets/118899387/c549721e-b56e-45f4-bac4-87d07d04d87c)

## RESULT:
Thus the program  to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.
