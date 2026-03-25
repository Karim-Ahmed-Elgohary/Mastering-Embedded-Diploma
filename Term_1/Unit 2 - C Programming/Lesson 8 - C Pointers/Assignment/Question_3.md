#include <stdio.h>

int main()
{

	char str[50];
	char *ptr = str;
	int i,len = 0;

	printf("Input a string: ");
	fflush(stdout);
	scanf("%s",str);

	for (i = 0; str[i] != '\0' ; i++){
		len++;
	}

	for (i = len-1 ; i >= 0 ; i--){
		printf("%c",*(ptr + i));
	}

	return 0;
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/258ab6b9-6112-485e-94c8-cc01eeedcd1a)
