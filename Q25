#include <stdio.h>
void main()
{
float units, bill = 0.0;
printf("Enter the total units consumed: "); // electricity bill calculation based on units consumed.
scanf("%f", &units);
if (units < 0) 
    printf("Invalid units consumed. Please enter a non-negative value.\n");
else if (units <= 50) 
    bill = units * 3.50; 
else if (units <= 150)
    bill = (50 * 3.50) + ((units - 50) * 4.00); 
else if (units <= 250)  
    bill = (50 * 3.50) + (100 * 4.00) + ((units - 150) * 5.20); 
else  
    bill = (50 * 3.50) + (100 * 4.00) + (100 * 5.20) + ((units - 250) * 6.50); 

printf("Electricity Bill: %.2f Rupees\n", bill);
getch();
}
