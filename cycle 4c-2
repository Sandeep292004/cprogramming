#include <stdio.h>
int large(int a,int e[100])
{
	int b,c,d;
	b=e[0];
	for(c=1;c<a;c++)
	{
		if(b<e[c])
		{
			b=e[c];
		}
	}
	return b;
}
main()
{
	int a,b,c,d;
	int e[100];
	printf("Input The Number Of Elements to be stored in an array:");
	scanf("%d",&a);
	for(b=0;b<a;b++)
	{
		printf("element-%d:",b);
		scanf("%d",&e[b]);
	}
	printf("The Largest Number in array is %d",large(a,e));
}
