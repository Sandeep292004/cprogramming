#include<stdio.h>
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
		return b;
	}
}
main()
	{
		int a,b,c,d,e[100];
		printf("enter the number of elements u are entering:");
		scanf("%d",&a);
		printf("enter the elements:");
		for(b=0;b<a;b++)
		{
			scanf("%d",&e[b]);
		}
		printf("the largest number of the array is:%d",large(a,e));
}
