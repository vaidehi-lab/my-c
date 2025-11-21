#include <stdio.h> 
long int balance = 10000; // Initial balance
int choice;
long int amount;
char continueTransaction = 'y'; 

int main() { // Exit controlled ATM menu
    do {
        printf("\n********Welcome to ATM Service**************\n");
        printf("1. Check Balance\n");
        printf("2. Withdraw Cash\n");
        printf("3. Deposit Cash\n");
        printf("4. Exit\n");
        printf("********************************************\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                printf("\nYour current balance is: %ld\n", balance);
                break;
            case 2:
                printf("\nEnter amount to withdraw: ");
                scanf("%ld", &amount);
                if (amount % 100 != 0) {
                    printf("\nPlease enter amount in multiples of 100.\n");
                } else if (amount > balance) {
                    printf("\nInsufficient Balance.\n");
                } else {
                    balance -= amount;
                    printf("\nTransaction successful. Remaining balance: %ld\n", balance);
                }
                break;
            case 3:
                printf("\nEnter amount to deposit: ");
                scanf("%ld", &amount);
                balance += amount;
                printf("\nAmount deposited successfully. New balance: %ld\n", balance);
                break;
            case 4:
                printf("\nThank you for using our ATM services!\n");
                continueTransaction = 'n'; // Set to 'n' to exit the loop
                break;
            default:
                printf("\nInvalid choice. Please try again.\n");
        }

        if (continueTransaction == 'y') { // Only ask to continue if not exiting
            printf("\nDo you want to perform another transaction? (y/n): ");
            // Clear the input buffer before reading a character
            while (getchar() != '\n'); // Consume remaining newline character
            scanf("%c", &continueTransaction);
        }

    } while (continueTransaction == 'y' || continueTransaction == 'Y');

    return 0;
}
