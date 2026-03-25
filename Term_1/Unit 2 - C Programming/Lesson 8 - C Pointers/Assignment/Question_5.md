#include <stdio.h>

struct SEmployee 
{

	char name[20];
	int ID;
	
};



int main()
{

	int i;
	struct SEmployee e1 = {"Alex",1002};
	struct SEmployee e2 = {"Albert",1005};

	struct SEmployee *arr[2];

	struct SEmployee *p1 = &e1;
	struct SEmployee *p2 = &e2;

	struct SEmployee **ptr = arr;

	arr[0] = p1;
	arr[1] = p2;

	for (i = 0; i < 2 ; i++)
	{
		printf("Employee name: %s\n",ptr[i] -> name);
		printf("Employee name: %d\n",ptr[i] -> ID);
		printf("\n");
	}


	return 0;
}

### Output 📸

<img width="593" height="682" alt="Image" src="https://github.com/user-attachments/assets/a98c46a4-a277-46cd-9cbd-763d1e227e25" />
