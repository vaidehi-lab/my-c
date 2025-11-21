#include <stdio.h>
void main() 
{
int n, first = 0, second = 1, next, sum = 0; // Print sum of fibonacci series.
printf("Enter the number of terms for the Fibonacci series: ");
scanf("%d", &n);
printf("Fibonacci Series: ");
if (n <= 0) 
   printf("Please enter a positive number of terms.\n");
else if (n == 1) 
{
    printf("%d ", first);
    sum = first;
}
else 
{
    printf("%d %d ", first, second);
    sum = first + second;
    for (int i = 2; i < n; i++) 
    {
            next = first + second;
            printf("%d ", next);
            sum += next;
            first = second;
            second = next;
     }
}
printf("\nThe sum of the Fibonacci series is: %d\n", sum);
getch();
}
