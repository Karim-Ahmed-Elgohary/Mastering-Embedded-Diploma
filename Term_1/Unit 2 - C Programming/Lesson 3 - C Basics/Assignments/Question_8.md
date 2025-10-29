#include "stdio.h"

void main()
{

	float a,b;
	char z;
	printf("Enter operator either + or - or * or divide: ");
	fflush(stdout);
	scanf("%c",&z);

	printf("Enter two operands: ");
	fflush(stdout);
	scanf("%f %f",&a ,&b);

	switch (z)
	{

	case '+':
		printf("%f + %f = %f", a,b,a+b);
		break;

	case '-':
		printf("%f - %f = %f", a,b,a-b);
		break;

	case '*':
		printf("%f * %f = %f", a,b,a*b);
		break;

	case '/':
		printf("%f / %f = %f", a,b,a/b);
		break;
	default:
		printf("Invalid operator.");
		break;

	}
  
}


### Output 🎥

![Image](https://github.com/user-attachments/assets/b16f5ca4-4b0d-4ba3-a8a3-a167ad0e264a)
