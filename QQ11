#include <stdio.h>
void main() 
{
int num1, num2, num3;
printf("Enter three integers: ");  // find max of three numbers using nested switch.
scanf("%d %d %d", &num1, &num2, &num3);
switch (num1 > num2) {
        case 1: 
            switch (num1 > num3) {
                case 1:
                    printf("%d is the maximum number.\n", num1);
                    break;
                case 0: 
                    printf("%d is the maximum number.\n", num3);
                    break;
            }
            break;
        case 0:
            switch (num2 > num3) {
                case 1: 
                    printf("%d is the maximum number.\n", num2);
                    break;
                case 0: 
                    printf("%d is the maximum number.\n", num3);
                    break;
            }
            break;
    }
getch();
}
