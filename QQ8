#include <stdio.h>
#include <math.h> 
void main() 
{
int choice;
double side, length, breadth, height, radius, volume; // MENU DRIVEN PROGRAM - Volume of cube,cuboid and sphere.
printf("Choose a shape to calculate its volume:\n");
printf("1. Cube\n");
printf("2. Cuboid\n");
printf("3. Sphere\n");
printf("Enter your choice: ");
scanf("%d", &choice);
switch (choice) {
        case 1: // Cube
            printf("Enter the side length of the cube: ");
            scanf("%lf", &side);
            volume = side * side * side;
            printf("Volume of the Cube = %.2lf\n", volume);
            break;

        case 2: // Cuboid
            printf("Enter the length of the cuboid: ");
            scanf("%lf", &length);
            printf("Enter the breadth of the cuboid: ");
            scanf("%lf", &breadth);
            printf("Enter the height of the cuboid: ");
            scanf("%lf", &height);
            volume = length * breadth * height;
            printf("Volume of the Cuboid = %.2lf\n", volume);
            break;

        case 3: // Sphere
            printf("Enter the radius of the sphere: ");
            scanf("%lf", &radius);
            volume = (4.0 / 3.0) * M_PI * pow(radius, 3); // M_PI is from math.h
            printf("Volume of the Sphere = %.2lf\n", volume);
            break;

        default:
            printf("Invalid choice! Please select 1, 2, or 3.\n");
            break;
    }
getch();
}
