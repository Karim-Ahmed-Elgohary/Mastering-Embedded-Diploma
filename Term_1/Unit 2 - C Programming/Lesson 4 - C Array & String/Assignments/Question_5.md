#include "stdio.h"

void main()
{

	int n,i,y,f=0;
	printf("Enter number of elements: ");
	fflush(stdout);
	scanf("%d",&n);

	int data[n];

	for (i=0 ; i<n ; i++)
	{
		fflush(stdout);
		scanf("%d",&data[i]);
	}
	printf("Enter element to be searched: ");
	fflush(stdout);
	scanf("%d",&y);

	for (i=0 ; i<n ; i++)
	{
		if (data[i]==y)
		{
			printf("Number found at location = %d",i+1);
			f=1;
		}
		else
			continue;
	}
	if (f==0)
	{
		printf("Number not found.");
	}
  
}


### Output 🎥

![Image](https://github.com/user-attachments/assets/468cca56-0947-4d73-a4de-259148559984)

