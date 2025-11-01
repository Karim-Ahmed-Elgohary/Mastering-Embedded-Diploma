#include "stdio.h"

void main(){

	char str[100];
	int i,n;

	printf("Enter a string: ");
	fflush(stdout);
	gets(str);

	n = strlen(str);

	printf("Reversed string is: ");
	for (i=n-1 ; i>=0 ; i--)
	{
		printf("%c" ,str[i]);
	}

}

### Output 🎥

![Image](https://github.com/user-attachments/assets/c2193952-073d-4c30-aa52-37875e397d2f)
