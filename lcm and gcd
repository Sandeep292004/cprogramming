#include<stdio.h>
int lcm(int a,int b)
{
	int c,d,e,f,g,h;
	d=a*b;
	for(c=1;c<d;c++)
	{
		for(e=1;e<d;e++)
		{
			f=a*c;
			g=b*e;
			if(f==g)
			{
				break;
			}
		}
		if(f==g)
		{
			return f;
			break;
		}
	}
}
int gcd(int a,int b)
{
	int c,d,e,f,g,h;
	d=a*b;
	for(c=1;c<d;c++)
	{
	    f=a%c;
		e=b%c;
		if(f==0 && e==0)
		{
			g=c;
		}
	}
	return g;
}
main()
{
	int a[100];
	int b,c,d,e,f,g;
	printf("Enter The N Value:");
	scanf("%d",&b);
	for(c=1;c<=b;c++)
	{
		printf("Number %d:",c);
		scanf("%d",&a[c-1]);
	}
	d=a[0];
	e=a[0];
	for(c=0;c<(b-1);c++)
	{
		d=lcm(d,a[c+1]);
		e=gcd(e,a[c+1]);
	}
	printf("The lcm is %d\n",d);
	printf("The gcd is %d",e);
}
