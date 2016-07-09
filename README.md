# nd
#include<stdio.h>
#include<conio.h>
main() 
{

int x,i=0;
printf("Press 1 By For Loop:\nPress 2 By While Loop:\nPress 3 By Do while loop:\n");
scanf("%d",&x);
switch(x)
{
case 1:
printf("\nPrinting of Hello World by using For Loop\n");

for(i=0;i<5;i++)
{
printf("Hello World\n");
}
break;
case 2:
printf("\nPrinting of Hello World by using While Loop\n");

while(i<5)
{
printf("Hello World\n");
i++;
}
break;
case 3:
printf("\nPrinting of Hello World by using Do While Loop\n");

do
{
printf("Hello World\n");
i++;
}while(i<5);
break;
default:
printf("Wrong Input");
}
getch();
}
