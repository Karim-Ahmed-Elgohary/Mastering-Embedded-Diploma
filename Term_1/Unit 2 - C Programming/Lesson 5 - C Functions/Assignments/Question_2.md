#include "stdio.h"

long fact(int n) {

		if (n==0 || n==1){
			return 1;
		}
		else
			return n*fact(n-1);
}

int main() {

	int x;

	printf("Enter a positive integer: ");
	fflush(stdout);
	scanf("%d",&x);

	printf("Factorial of %d = %ld",x,fact(x));

	return 0;
  
}

### Output 🎥

![Image](https://github.com/user-attachments/assets/81443149-2ad0-4a80-a924-8fa581faf485)
