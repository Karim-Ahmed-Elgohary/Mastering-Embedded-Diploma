#include "stdio.h"

void main(){

	int n,i,x,l;

	printf("Enter number of elements: ");
	fflush(stdout);
	scanf("%d",&n);

	int data[n];

	for (i=0 ; i<n ; i++)
	{
		fflush(stdout);
		scanf("%d",&data[i]);
	}
	printf("Enter element to be inserted: ");
	fflush(stdout);
	scanf("%d",&x);

	printf("Enter the location: ");
	fflush(stdout);
	scanf("%d",&l);

	if (l>n+1 || l<0)
	{
		printf("Invalid index.");
	}

	else
	{
		for (i=n ; i>=l ; i--)
		{
			data[i]=data[i-1];
		}
		data[l] = x;
		n++;

		for (i=0 ; i<n ; i++){
			printf("%d ",data[i]);
		}
	}

}



### Output 🎥

![Image](https://github.com/user-attachments/assets/dc8dfd42-6199-4083-bdec-100bf3a02af4)
