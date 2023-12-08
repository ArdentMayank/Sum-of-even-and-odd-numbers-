#include<stdio.h>
#include<conio.h>
void main()
{
clrscr();
int a;
printf(" Enter any integer \n");
for(;;)
{
scanf(" %d ",&a);
if(a==0)
{
break;


}
if(a%2==0)
{
Sum_of_even=0;
Sum_of_even=Sum_of_even + a;
else 
{
Sum_of_odd=0;
Sum_of_odd= Sum_of_odd + a;

}

}
printf("Sum of even integer= %d \n ",Sum_of_even);
printf("Sum of odd integer = %d \n ",Sum_of_odd);
getch();



}







}
