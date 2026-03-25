#include <stdio.h>

int main()
{

	char z = 'A';
	char *ptr = &z;



	printf("The Alphabets are: \n");

	while(*ptr<='Z'){
		printf("%c ", *ptr);
		(*ptr)++;
	}



	return 0;
}


### Output 📸

<img width="1073" height="813" alt="Image" src="https://github.com/user-attachments/assets/3ca1becd-e44d-497f-9a71-5e652fb0ae5c" />
