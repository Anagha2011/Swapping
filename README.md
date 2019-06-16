#include<stdio.h>
#include<conio.h>
void main()
{
	int a,b,temp;
	printf("Enter any two no:");
	scanf("%d%d",&a,&b);

	temp=a;
	a=b;
	b=temp;

	printf("swapped no are:\n");
	printf("%d\n%d",a,b);
	getch();
}
