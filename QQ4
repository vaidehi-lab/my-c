#include <stdio.h>
void main() 
{
int month, year;
printf("Enter month number (1-12): "); // find number ofdays in given month.
scanf("%d", &month);
switch (month) {
        case 1: // January
        case 3: // March
        case 5: // May
        case 7: // July
        case 8: // August
        case 10: // October
        case 12: // December
            printf("31 days\n");
            break;
        case 4: // April
        case 6: // June
        case 9: // September
        case 11: // November
            printf("30 days\n");
            break;
        case 2: // February
            printf("Enter the year: ");
            scanf("%d", &year);// Check for leap year
            if ((year % 400 == 0) || ((year % 4 == 0) && (year % 100 != 0))) 
                printf("29 days (Leap Year)\n");
            else 
                printf("28 days\n");
            break;
        default:
            printf("Invalid month number. Please enter a number between 1 and 12.\n");
            break;
    }
getch();
}
