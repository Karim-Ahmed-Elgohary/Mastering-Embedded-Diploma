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
