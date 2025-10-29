#include "stdio.h"

void main()
{

	float x,y,z;
	printf("Enter three numbers: ");
	fflush(stdout);
	scanf("%f %f %f", &x, &y, &z);

	if (x>=y && x>=z)
	{
		printf("largest number = %f",x);
	}
	else if (y>=x && y>=z)
	{
		printf("largest number = %f",y);
	}
	else
		printf("largest number = %f",z);
    
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/b5fd053b-14c6-416f-8104-bd2ddbd97730)
