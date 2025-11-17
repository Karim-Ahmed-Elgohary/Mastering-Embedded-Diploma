#include "stdio.h"

long pow(int b,int p){

	int result;
	if (p==0)
		result = 1;
	else
	{
		result = b*pow(b,p-1);
	}
	return result;
}

int main (){

	int a,b;

	printf("Enter base number: ");
	fflush(stdout);
	scanf("%d",&a);

	printf("Enter power number(positive integer): ");
	fflush(stdout);
	scanf("%d",&b);

	printf("%d ^ %d = %ld", a,b,pow(a,b));
	return 0;
  
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/ce746942-98e0-42c0-bba2-3cacd0d9dee9)
