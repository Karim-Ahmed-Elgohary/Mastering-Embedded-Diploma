#include "stdio.h"

void main()
{

	int n;

	printf("Enter an integer you want to check:");
	fflush(stdout);
	scanf("%d",&n);

	while (n<0)
	{
		printf("Enter a positive integer you want to check:");
		fflush(stdout);
		scanf("%d",&n);
	}
	if (n%2 == 0)
	{
		printf("%d is even.", n);
	}
	else
		printf("%d is odd.", n);


}

### Output 🎥
<video src="https://raw.githubusercontent.com/Karim-Ahmed-Elgohary/Mastering-Embedded-Diploma/refs/heads/main/Term_1/Videos/a1%20o1.mp4" controls width="600">










