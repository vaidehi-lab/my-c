#include <stdio.h>
void main() 
{
int num,isPerfectSquare = 0;
printf("Enter a positive integer: "); // check whether a number is perfect square or not 
scanf("%d", &num);
if (num < 0) 
   printf("%d is not a perfect square (negative numbers are not perfect squares in this context).\n", num);
else if (num == 0) 
   printf("0 is a perfect square (0 * 0 = 0).\n");
else 
{
    for (int i = 1; i * i <= num; i++)
    { 
      if (i * i == num) 
      {
          isPerfectSquare = 1; 
          break;
      }
    }
}
if (isPerfectSquare == 1) 
    printf("%d is a perfect square.\n", num);
else 
    printf("%d is not a perfect square.\n", num);
getch();
}
