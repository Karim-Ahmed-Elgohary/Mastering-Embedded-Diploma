#include "stdio.h"

void main(){

	int r,c,i,j;

	printf("Enter rows and columns of the matrix: ");
	fflush(stdout);
	scanf("%d %d",&r,&c);

	int a[r][c];

	for (i=0 ; i<r ; i++)
	{
		for(j=0 ; j<c ; j++)
		{
			printf("Enter a%d%d: ",i+1,j+1);
			fflush(stdout);
			scanf("%d",&a[i][j]);
		}
	}

	printf("Entered Matrix:\t\n");
	for (i=0 ; i<r ; i++)
	{
		for(j=0 ; j<c ; j++)
		{
			printf("%d",a[i][j]);
		}
		printf("\n");
	}

	printf("Transpose of Matrix:\t\n");
	for (i=0 ; i<c ; i++)
	{
		for(j=0 ; j<r ; j++)
		{
			printf("%d",a[j][i]);
		}
		printf("\n");
	}

}


### Output 🎥

![Image](https://github.com/user-attachments/assets/4076840c-76db-4c22-a66e-0cf7edb9a523)
