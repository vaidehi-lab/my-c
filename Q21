
#include <stdio.h>
#include <math.h> // Required for sqrt() function
void main() 
{
float a, b, c; 
float discriminant,root1,root2,realPart,imagPart; //find the roots of the quadratic equations(real or imaginary)
printf("Enter coefficients a, b, and c for the quadratic equation (ax^2 + bx + c = 0):\n");
scanf("%f %f %f", &a, &b, &c);
// Calculate the discriminant
discriminant = b * b - 4 * a * c;
  
// Determine the nature of the roots based on the discriminant
if (discriminant > 0) 
{
    // Two distinct real roots
    root1 = (-b + sqrt(discriminant)) / (2 * a);
    root2 = (-b - sqrt(discriminant)) / (2 * a);
    printf("Two distinct real roots: root1 = %.2f and root2 = %.2f\n", root1, root2);
}
else if (discriminant == 0)
{
     // One real root (both roots are equal)
     root1 = -b / (2 * a);
}    printf("One real root (equal roots): root1 = root2 = %.2f\n", root1);
else 
{
      // Complex roots (imaginary roots)
      realPart = -b / (2 * a);
      imagPart = sqrt(-discriminant) / (2 * a); // Use -discriminant as it's negative
      printf("Complex roots: root1 = %.2f + %.2fi and root2 = %.2f - %.2fi\n", realPart, imagPart, realPart, imagPart);
}

getch();
}
