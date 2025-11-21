#include <stdio.h>
void main() 
{
char ch;
int type;
printf("Enter a character: "); // check whether character is alphabet,digit or a special symbol.
scanf("%c", &ch);
if ((ch >= 'a' && ch <= 'z') || (ch >= 'A' && ch <= 'Z')) 
        type = 1; 
else if (ch >= '0' && ch <= '9') 
        type = 2; 
else 
        type = 3; 
switch (type) {
        case 1:
            printf("'%c' is an Alphabet.\n", ch);
            break;
        case 2:
            printf("'%c' is a Digit.\n", ch);
            break;
        case 3:
            printf("'%c' is a Special Symbol.\n", ch);
            break;
        default:
            printf("Error: Unknown character type.\n");
            break;
    }
getch();
}
