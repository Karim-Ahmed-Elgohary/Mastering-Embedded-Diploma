#include <stdio.h>

int main()
{

	int m =29;
	int *ptr = &m;

	printf("Address of m: %p \n",ptr);
	printf("Value of m: %d \n\n",m);

	int *ab = &m;
	printf("Now ab is assigned with the address of m. \n");

	printf("Address of pointer ab: %p \n",ab);
	printf("Content of pointer ab: %d \n\n",*ab);

	m = 34;

	printf("The value of m is assigned to 34 now.\n");

	printf("Address of pointer ab: %p \n",ab);
	printf("Content of pointer ab: %d \n\n",*ab);

	*ab = 7;

	printf("The pointer variable ab is assigned with value 7 now. \n");

	printf("Address of m: %p \n",ab);
	printf("Value of m: %d \n\n",*ab);



	return 0;
}


### Ouput 📸

<img width="1072" height="760" alt="Image" src="https://github.com/user-attachments/assets/75d0b9d2-f062-4148-b2b4-50078aa4d320" />
