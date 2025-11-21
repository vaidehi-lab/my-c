#include<stdio.h>
void main()
{
int num,orignum,digit,rev=0; // check whether a number is palindrome or not.
printf("Enter a number:");
scanf("%d",&num);
orignum = num;
while(num>0)
{
  digit=num%10;
  rev=rev*10+digit;
  num=num/10;
}
if (orignum==rev)
   printf("The number %d is a palindrome number",num);
else
   printf("The number %d is not a palindrome number",num);
getch();
} 
