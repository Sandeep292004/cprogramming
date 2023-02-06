#include <stdio.h>
main()
{
	int a[100][100];
	int b,c,d,e=0,f;
	printf("Enter The order Of The Matrix:");
	scanf("%dx%d",&b,&c);
	printf("Enter The Elements of the matrix:\n");
	for(c=0;c<b;c++)
	{
		for(d=0;d<b;d++)
		{
			scanf("%d",&a[c][d]);
		}
	}
	printf("The Diagonal Elements are:\n");
	for(c=0;c<b;c++)
	{
		for(d=0;d<b;d++)
		{
			if(c==d)
			{
				printf("%d\n",a[c][d]);
				e+=a[c][d];
			}
		}
	}
	printf("The Sum Of Diagonal Elements is %d",e);
}
