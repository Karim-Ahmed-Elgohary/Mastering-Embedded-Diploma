#include "stdio.h"
#include "string.h"

void StringRev(char str[], int i) {

	if (i<0)
		return;
	else
	{
		printf("%c",str[i]);
		StringRev(str,i-1);
	}
}


int main() {

	char sen[100];
	int len;
	printf("Enter a sentence: ");
	fflush(stdout);
	gets(sen);

	len = strlen(sen)-1;
	StringRev(sen,len);

	return 0;
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/9429cf45-8df1-448a-baf5-25f0334b0bd2)
