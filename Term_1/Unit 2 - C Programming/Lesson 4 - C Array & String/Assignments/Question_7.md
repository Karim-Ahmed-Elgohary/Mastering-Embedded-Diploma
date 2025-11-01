#include "stdio.h"

void main(){

	char str[100];
	int count=0,j=0;
	printf("Enter a string: ");
	fflush(stdout);
	gets(str);

	while (str[j]!=0)
	{
		count++;
		j++;
	}

	printf("Length of string: %d",count);
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/4bece1d5-63e8-4217-9aec-8fffd9098de7)
