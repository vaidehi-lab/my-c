#include <stdio.h>
void main() 
{
int n, first = 0, second = 1, next, i; // print fibonacci series upto N terms
printf("Enter the number of terms: ");
scanf("%d", &n);
printf("Fibonacci Series: ");
for (i = 0; i < n; i++) 
{
    if (i <= 1) 
      next = i;
    else 
    {
        next = first + second;
        first = second;
        second = next;
    }
        printf("%d ", next);
}
printf("\n"); 
getch();
}
