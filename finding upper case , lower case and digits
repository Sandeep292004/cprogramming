#include<stdio.h>
#include<string.h>
main()
{
	char a[100];
	int b,c=0,d=0,e=0;
	printf("enter the string:");
	scanf("%[^\n]s",&a);
	for(b=0;b<strlen(a);b++)
	{
		if(a[b]>='A' && a[b]<='Z')
		{
			c+=1;
		}
		else if(a[b]>='a' && a[b]<='z')
		{
			d+=1;
		}
		else if(a[b]>='0' && a[b]<='9')
		{
			e+=1;
		}
	}
	printf("there are %d upper cases \n",c);
	printf("there are %d lower cases \n",d);
	printf("there are %d digits",e);
		}
