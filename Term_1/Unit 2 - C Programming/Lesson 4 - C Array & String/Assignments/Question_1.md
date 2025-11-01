#include "stdio.h"

void main(){

	int i,j;
	float M[2][2], P[2][2];

	printf("Enter the elements of the 1st matrix \n");
	for (i=0 ; i<2 ; i++)
	{
		for(j=0 ; j<2 ; j++)
		{
			printf("Enter a%d%d: ",i+1,j+1);
			fflush(stdout);
			scanf("%f",&M[i][j]);
		}
	}


	printf("\n Enter the elements of the 2nd matrix \n");

	for (i=0 ; i<2 ; i++)
	{
		for(j=0 ; j<2 ; j++)
		{
			printf("Enter b%d%d: ",i+1,j+1);
			fflush(stdout);
			scanf("%f",&P[i][j]);
		}
	}

	printf("Sum of matrices is:\n");

	for (i=0 ; i<2 ; i++)
	{
		for(j=0 ; j<2 ; j++)
		{
			printf("%f ",M[i][j]+P[i][j]);
		}
		printf("\n");
	}



}


### Output 🎥

![Image](https://github.com/user-attachments/assets/943fc151-b80d-41d4-8b24-2afdb7fcf970)

