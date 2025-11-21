#include <stdio.h>
#include <math.h> /

int main() {
    int choice;
    float principal, rate, time, simple_interest, compound_interest; // MENU DRIVEN PROGRAM - Simple interest and compound interest

    printf("Choose an option:\n");
    printf("1. Calculate Simple Interest\n");
    printf("2. Calculate Compound Interest\n");
    printf("3. Exit\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    switch (choice) {
        case 1:
            printf("Enter Principal Amount: ");
            scanf("%f", &principal);
            printf("Enter Rate of Interest (in %%): ");
            scanf("%f", &rate);
            printf("Enter Time (in years): ");
            scanf("%f", &time);
            simple_interest = (principal * rate * time) / 100;
            printf("Simple Interest = %.2f\n", simple_interest);
            break;

        case 2:
            printf("Enter Principal Amount: ");
            scanf("%f", &principal);
            printf("Enter Rate of Interest (in %%): ");
            scanf("%f", &rate);
            printf("Enter Time (in years): ");
            scanf("%f", &time);
            compound_interest = principal * pow(1 + (rate / 100), time) - principal;
            printf("Compound Interest = %.2f\n", compound_interest);
            break;

        case 3:
            printf("Exit.\n");
            break;

        default:
            printf("Invalid choice. Please enter 1, 2, or 3.\n");
            break;
    }

    return 0;
}
