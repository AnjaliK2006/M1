
# EX-01-Datatypes-Operators
## AIM:
Write a C program to find the ASCII value of a given character.

## ALGORITHM:
1.Start the program and declare a variable to store a character.
2.Read a character input from the user.
3.Convert the character to its ASCII value using typecasting or by printing it as an integer.
4.Display the ASCII value and end the program.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    char a;
    scanf("%c",&a);
    printf("ASCII value of %c is %d",a,a);
    return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/8ffee53c-6736-4bd1-a1db-01a232ba1e1a)

## RESULT:
Thus the program to  find the ASCII value of a given character has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether the value is greater than and equal to 50. 

# ALGORITHM:
1.Start the program and declare an integer variable a.
2.Read the value of a from the user using scanf.
3.Check if a is greater than or equal to 50 using an if condition.
4.Display a message if the condition is true; otherwise, display nothing. End the program.

# PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a>=50){
        printf("The Value is greater than or equal to 50");
    }else{
        printf(" ");
    }
    
    return 0;   
}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/17761b34-4755-47e2-96a3-c97b39ec3d0e)

# RESULT:
Thus the program to read A values and check whether the value is greater than and equal to 50 has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b;
    scanf("%f%f",&a,&b);
    (a>b)? printf("Minimum between %.3f and %.3f is %.3f",a,b,b): printf("Minimum between %.3f and %.3f is %.3f",a,b,a);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/86aaea9f-34b3-42c9-ade5-060e728150a7)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to read a, b values and check whether  a equal to b. 

## ALGORITHM:
1.Start the program and declare two integer variables a and b.
2.Read the values of a and b from the user using scanf.
3.Compare whether a is equal to b using an if condition.
4.Display "a is equal to b" if the condition is true; otherwise, print nothing. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    if(a==b){
        printf("a is equal to b");
    }else{
        printf(" ");
    }
    
 return 0;   
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/47ecb89f-f7f9-4ccb-8b2a-5faecbbede27)
## RESULT:
Thus the program to read a, b values and check whether a equal to b has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
int main() {
    int m1, m2, m3;
    int total;
    float percentage;
    printf("Enter marks of three subjects: ");
    scanf("%d %d %d", &m1, &m2, &m3);
    if (m1 < 35 || m2 < 35 || m3 < 35) {
        printf("Result: Fail (One or more subjects below pass marks)\n");
    } else {
        total = m1 + m2 + m3;
        percentage = total / 3.0;
        printf("Total Marks = %d\n", total);
        printf("Percentage = %.2f%%\n", percentage);
        if (percentage >= 60) {
            printf("Division: First\n");
        } else if (percentage >= 50) {
            printf("Division: Second\n");
        } else {
            printf("Division: Pass\n");
        }
    }

    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/4bca5575-3f68-43d6-b6bf-2b479c704b3d)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

