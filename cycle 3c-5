#include <stdio.h>
main()
{
	int a,b,c,d,sf;
	printf("Enter The Date:");
	scanf("%d",&a);
	printf("Enter The Month:");
	scanf("%d",&b);
	printf("Enter the Year:");
	scanf("%d",&c);
	if(a>31)
	{
		printf("Date Entered is Incorrect");
	}
	else if(b>12)
	{
		printf("Year Entered is Incorrect");
	}
	else
	{
		if(c%100==0)
		{
			if(c%400==0)
			{
				printf("Given Year is a Leap Year");
			}
			else
			{
				printf("Given Year Is Not a leap Year");
			}
		}
		else
		{
			if(c%4==0)
			{
				printf("Given Year Is a Leap Year");
			}
			else
			{
				printf("Given Year Is Not a Leap Year");
			}
		}
	}
}
