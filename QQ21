#include <stdio.h> 

// Function to calculate string length without using strlen()
int my_strlen(char *s) {
    int length = 0;
    while (*s != '\0') {
        length++;
        s++;
    }
    return length;
}

// Function to reverse a string without using string.h functions
void reverse_string(char *str) {
    int length = my_strlen(str);
    int i, j;
    char temp;
    for (i = 0, j = length - 1; i < j; i++, j--) {
        temp = str[i];
        str[i] = str[j];
        str[j] = temp;
    }
}

// Function to reverse a number
long int reverse_number(long int num) {
    long int reversed_num = 0;
    long int remainder;
    while (num != 0) {
        remainder = num % 10;
        reversed_num = reversed_num * 10 + remainder;
        num /= 10;
    }
    return reversed_num;
}

int main() {  // MENU DRIVEN PROGRAM- to reverse number or a string
    int choice;
    char str[100]; 
    long int num;

    do {
        printf("\n--- Menu ---\n");
        printf("1. Reverse a String\n");
        printf("2. Reverse a Number\n");
        printf("3. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        // Consume the newline character left by scanf
        while (getchar() != '\n'); 

        switch (choice) {
            case 1:
                printf("Enter a string: ");
                // Read string including spaces
                int i = 0;
                char c;
                while ((c = getchar()) != '\n' && i < 99) {
                    str[i++] = c;
                }
                str[i] = '\0'; // Null-terminate the string

                reverse_string(str);
                printf("Reversed string: %s\n", str);
                break;
            case 2:
                printf("Enter a number: ");
                scanf("%ld", &num);
                printf("Reversed number: %ld\n", reverse_number(num));
                break;
            case 3:
                printf("Exiting program.\n");
                break;
            default:
                printf("Invalid choice. Please try again.\n");
        }
    } while (choice != 3);

    return 0;
}
