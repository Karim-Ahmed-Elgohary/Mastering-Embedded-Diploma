#include "stdio.h"

void GetPrime (int a,int b){
	int i,j,prime;
	for (i=a;i<=b;i++){

		prime = 1;

		for (j=2;j<i;j++){
			if (i%j==0){
				prime = 0;
				break;
			}
		}

		if (prime == 1){
			printf("%d ",i);
		}

	}

}


int main (){
	int x,y;
	printf("Enter two numbers(intervals): ");
	fflush(stdout);
	scanf("%d %d",&x,&y);

	printf("Prime numbers between %d and %d are: ",x,y);
	GetPrime (x,y);

	return 0;
}


### Output 🎥

![Image](https://github.com/user-attachments/assets/41afc998-08ea-407a-8fe0-b04f5ec1083d)
