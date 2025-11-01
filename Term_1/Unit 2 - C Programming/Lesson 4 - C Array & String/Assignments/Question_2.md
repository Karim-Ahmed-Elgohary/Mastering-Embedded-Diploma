#include "stdio.h"


void main(){

	int n,i;
	float data[50],t=0;

	printf("Enter number of data: ");
	fflush(stdout);
	scanf("%d",&n);

	for (i=0 ; i<n ; i++)
	{
		printf("%d. Enter number:",i+1);
		fflush(stdout);
		scanf("%f",&data[i]);
		t+=data[i];

	}

	printf("Average = %f",t/n);



}

### Output 

![Image](https://github.com/user-attachments/assets/1a861556-1ff5-4015-8d7a-8d441095fa5e)
