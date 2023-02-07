#include <stdio.h>
main()
{
	int a,b,c,d;
	int e[100];
	printf("Enter The Number Of Elements You are entering:");
	scanf("%d",&a);
	printf("Enter the elements: ");
	for(b=0;b<a;b++)
	{
		scanf("%d",&e[b]);
	}
	for(b=0;b<a/2;b++)
	{
		c=e[b];
		e[b]=e[a-1-b];
		e[a-1-b]=c;
	}
	printf("The Reversed array is: ");
	for(b=0;b<a;b++)
	{
		printf("%d",e[b]);
		if(b<a-1)
		{
			printf(",");
		}
	}
}
