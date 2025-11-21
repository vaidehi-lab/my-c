#include <stdio.h>
// Function to calculate factorial
long long factorial(int n) {
    long long fact = 1;
    int i;
    for (i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}
// Function to print Fibonacci series up to n terms
void fibonacci(int n) {
    int t1 = 0, t2 = 1, nextTerm;
    int i;
    if (n >= 1) {
        printf("%d ", t1);
    }
    if (n >= 2) {
        printf("%d ", t2);
    }
    for (i = 3; i <= n; i++) {
        nextTerm = t1 + t2;
        printf("%d ", nextTerm);
        t1 = t2;
        t2 = nextTerm;
    }
    printf("\n");
}

// Function to check if a number is prime
int isPrime(int n) {
    int i;
    if (n <= 1) {
        return 0; // Not prime
    }
    for (i = 2; i * i <= n; i++) {
        if (n % i == 0) {
            return 0; // Not prime
        }
    }
    return 1; // Prime
}

int main() {  // MENU DRIVEN PROGRAM - factorial, fibonacci series and prime check.
    int choice, num, running = 1;

        printf("\n--- Menu ---\n");
        printf("1. Calculate Factorial\n");
        printf("2. Generate Fibonacci Series\n");
        printf("3. Check Prime Number\n");
        printf("4. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                printf("Enter a non-negative integer: ");
                scanf("%d", &num);
                if (num < 0) {
                    printf("Factorial is not defined for negative numbers.\n");
                } else {
                    printf("Factorial of %d = %lld\n", num, factorial(num));
                }
                break;
            case 2:
                printf("Enter the number of terms for Fibonacci series: ");
                scanf("%d", &num);
                if (num <= 0) {
                    printf("Number of terms must be positive.\n");
                } else {
                    printf("Fibonacci Series: ");
                    fibonacci(num);
                }
                break;
            case 3:
                printf("Enter a positive integer to check for primality: ");
                scanf("%d", &num);
                if (isPrime(num)) {
                    printf("%d is a prime number.\n", num);
                } else {
                    printf("%d is not a prime number.\n", num);
                }
                break;
            case 4:
                printf("Exit!\n");
                break;
            default:
                printf("Invalid choice. Please try again.\n");
        }
    return 0;
}
