#include <stdio.h>
void main() 
{
char operator_char; // simple calculator
double num1, num2, result;
printf("Enter an operator (+, -, *, /): ");
scanf("%c", &operator_char);
printf("Enter two operands: ");
scanf("%lf %lf", &num1, &num2);
switch (operator_char) {
        case '+':
            result = num1 + num2;
            printf("%.2lf + %.2lf = %.2lf\n", num1, num2, result);
            break;
        case '-':
            result = num1 - num2;
            printf("%.2lf - %.2lf = %.2lf\n", num1, num2, result);
            break;
        case '*':
            result = num1 * num2;
            printf("%.2lf * %.2lf = %.2lf\n", num1, num2, result);
            break;
        case '/':
            if (num2 != 0) { 
                result = num1 / num2;
                printf("%.2lf / %.2lf = %.2lf\n", num1, num2, result);
            } else {
                printf("Error: Division by zero is not allowed.\n");
            }
            break;
        default:
            printf("Error: Invalid operator entered.\n");
}
getch();
}
