#include "stdio.h"

void main()
{

	int n;

	printf("Enter an integer you want to check:");
	fflush(stdout);
	scanf("%d",&n);

	while (n<0)
	{
		printf("Enter a positive integer you want to check:");
		fflush(stdout);
		scanf("%d",&n);
	}
	if (n%2 == 0)
	{
		printf("%d is even.", n);
	}
	else
		printf("%d is odd.", n);


}


### Output 🎥
[](https://github.com/f6823308-6d83-4912-8ddd-f2a3469f5825)













