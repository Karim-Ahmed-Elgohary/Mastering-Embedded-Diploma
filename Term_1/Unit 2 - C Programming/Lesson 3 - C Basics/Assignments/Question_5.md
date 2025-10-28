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
