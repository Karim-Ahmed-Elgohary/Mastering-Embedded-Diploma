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



# Output


https://github.com/user-attachments/assets/c6fb023a-ddd1-49d0-b093-45f2c1c343b2



