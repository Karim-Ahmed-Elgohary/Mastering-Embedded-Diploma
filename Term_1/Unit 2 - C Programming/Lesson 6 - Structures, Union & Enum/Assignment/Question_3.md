#include <stdio.h>

struct complex_numbers{

	float real;
	float imaginary;
};

void complex_sum (struct complex_numbers n1, struct complex_numbers n2){

	float r,i;
	r = n1.real + n2.real;
	i = n1.imaginary + n2.imaginary;

	printf("Sum = %f + %f i",r,i);
}


int main(){

	struct complex_numbers a,b;

	printf("For 1st complex number\n");

	printf("Enter real and imaginary respectively: ");
	fflush(stdout);
	scanf("%f %f",&a.real,&a.imaginary);

	printf("For 2nd complex number\n");

	printf("Enter real and imaginary respectively: ");
	fflush(stdout);
	scanf("%f %f",&b.real,&b.imaginary);

	complex_sum(a,b);

	return 0;
}


### Output 🎥

![Image](https://github.com/user-attachments/assets/7e2fbd23-9575-4193-9681-95a1840c6cdb)
