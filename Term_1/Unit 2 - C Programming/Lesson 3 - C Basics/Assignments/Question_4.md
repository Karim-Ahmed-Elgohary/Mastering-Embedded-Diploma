#include "stdio.h"

void main()
{

	float n;
	printf("Enter a number: ");
	fflush(stdout);
	scanf("%f",&n);

	if (n==0)
		printf("You entered zero.");

	else if (n>0)
		printf("%f is positive.",n);

	else
		printf("%f is negative.",n);
    
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/8b5db64e-c52a-47d5-a9c3-c128cd18646e)
