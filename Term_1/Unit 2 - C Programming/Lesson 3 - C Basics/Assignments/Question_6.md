#include "stdio.h"

void main()
{

	int n,i,result=0;
	printf("Enter an integer: ");
	fflush(stdout);
	scanf("%d",&n);

	while (n<0)
	{
		printf("Enter a positive integer: ");
		fflush(stdout);
		scanf("%d",&n);
	}

	for (i=0;i<=n;i++)
	{
		result +=i;
	}

	printf("Sum = %d",result);

}
