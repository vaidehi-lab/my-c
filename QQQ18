#include <stdio.h>
void main()
{
int start, end, num, i, isPrime; // print all prime numbers in a range.
printf("Enter the starting number of the range: ");
scanf("%d", &start);
printf("Enter the ending number of the range: ");
scanf("%d", &end);
printf("Prime numbers between %d and %d are: ", start, end);
for (num = start; num <= end; num++) 
{
    isPrime = 1; // Assume the number is prime initially
    if (num <= 1) 
        isPrime = 0;
    else 
    {
       for (i = 2; i <= num / 2; i++) 
       {
          if (num % i == 0) 
          {
              isPrime = 0; // If divisible, it's not prime
              break;       
          }
       }
    }
 if (isPrime == 1) 
     printf("%d ", num);
getch();
}
