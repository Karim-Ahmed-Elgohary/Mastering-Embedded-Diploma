#include "stdio.h"

void main()
{

	char s;
	printf("Enter a character: ");
	fflush(stdout);
	scanf("%c",&s);

	if (s>=65 && s<=90 || s>=97 && s<=122)
	{
		printf("%c is an alphabet.",s);
	}
	else
		printf("%c is not an alphabet.",s);
    
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/928f5492-9f20-43a5-9e97-53b9237fbfd3)
