#include "stdio.h"

void main(){

	int k,count=0;
	char str[100],i;
	printf("Enter a string: ");
	fflush(stdout);
	gets(str);

	printf("Enter character to find its frequency: ");
	fflush(stdout);
	scanf("%c",&i);

	for (k=0 ; k<strlen(str); k++)
	{
		if(str[k]==i)
			count++;
	}
	printf("Frequency of %c = %d",i,count);

}

### Output 🎥

![Image](https://github.com/user-attachments/assets/a70adb81-7c83-4a50-b262-dace9b81f425)
