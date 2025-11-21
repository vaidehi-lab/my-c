#include <stdio.h>
#include <math.h> // Required for sqrt()
void main() 
{
int num, i, isPrime = 1;  //check prime number.
printf("Enter a positive integer: ");
scanf("%d", &num);
if (num <= 1) 
    isPrime = 0;
else 
{
    for (i = 2; i <= sqrt(num); i++)
    {
       if (num % i == 0) 
       {
            isPrime = 0; // Found a divisor, so it's not prime
            break;      
        }
    }
}
if (isPrime == 1) 
    printf("%d is a Prime Number.\n", num);
else 
    printf("%d is Not a Prime Number.\n", num);
getch();
}
