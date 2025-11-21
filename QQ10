#include <stdio.h>
void main() 
{
int num1, num2; // find max of two numbers using switch.
printf("Enter the first number: ");
scanf("%d", &num1);
printf("Enter the second number: ");
scanf("%d", &num2);

  // The expression (num1 > num2) evaluates to 1 if true, 0 if false
switch (num1 > num2) {
        case 1: 
            printf("Maximum number is: %d\n", num1);
            break;
        case 0:
            if (num1 == num2) 
                printf("Both numbers are equal: %d\n", num1);
            else 
                printf("Maximum number is: %d\n", num2);
            break;
        default: 
            printf("An unexpected error occurred.\n");
            break;
    }
getch();
}
