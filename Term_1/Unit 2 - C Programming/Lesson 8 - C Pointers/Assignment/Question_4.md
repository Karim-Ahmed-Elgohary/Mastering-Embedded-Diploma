#include <stdio.h>

int main(){

	int n,i;


	printf("Enter number of elements to store in array (max 15): ");
	fflush(stdout);
	scanf("%d",&n);

	int arr[n];
	int *ptr = arr;


	for (i = 0; i < n ; i++)
	{
		printf("Enter element - %d: ",i+1);
		fflush(stdout);
		scanf("%d",(ptr+i));
	}

	printf("The elements of array in reverse order: \n");

	for (i = n - 1 ; i>=0 ; i--)
	{
		printf("element - %d: %d\n",i+1,*(ptr + i));
	}



	return 0;
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/721474ef-dca1-4000-b93d-03892813d74a)
