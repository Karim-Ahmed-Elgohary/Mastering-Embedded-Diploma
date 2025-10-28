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


### Output 
![Image](https://github.com/user-attachments/assets/b02f5e80-96c2-425c-94e3-59752cc62a0f)














