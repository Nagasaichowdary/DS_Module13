# EX3 Implementation of Tower of Hanoi
## DATE:
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1.Start the program.
2.Define the priority() function to return the priority of operators.
3.Initialize the string containing operators and operands.
4.Loop through each character in the string.
5.For each operator, call the priority() function to determine its priority.
6.Print the operator and its corresponding priority level. 7.End

## Program:
```
Program to implement Tower of Hanoi
Developed by:P.ADITYA NAGA SAI 
RegisterNumber:212223110036  
#include <stdio.h>

void TOH(int n, char source, char dest, char aux) {
    if (n == 1) {
        printf("%c to %c\n", source, dest);
        return;
    }
    TOH(n - 1, source, aux, dest);
    printf("%c to %c\n", source, dest);
    TOH(n - 1, aux, dest, source);
}
```

## Output:

![Screenshot 2025-04-29 182958](https://github.com/user-attachments/assets/2999a803-bdbe-49c2-9952-3b30c4cfa6b0)



## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
