#include "stdio.h"

void main()
{

	char s;
	printf("Enter an alphabet: ");
	fflush(stdout);
	scanf("%c",&s);

	if (s == 'a' ||s == 'e' || s == 'i' || s == 'o' || s == 'u' || s == 'A' || s == 'E' || s == 'I' || s == 'O' || s == 'U')
	{
		printf("%c is a vowel.", s);
	}
	else
		printf("%c is a consonant.", s);
    
}
