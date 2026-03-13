#include <stdio.h>

struct Student{
	
	char name[20];
	int roll;
	float marks;
};



int main(){

	struct Student a[10];
	int i,j;

	printf("Enter information of students:\n");

	for(i=0 ; i<10 ; i++){

		printf("For roll number ");
		fflush(stdout);
		scanf("%d",&a[i].roll);

		printf("Enter name: ");
		fflush(stdout);
		scanf("%s",a[i].name);

		printf("Enter marks: ");
		fflush(stdout);
		scanf("%f",&a[i].marks);

	}

	printf("Displaying information of students:\n");

	for(j=0 ; j<10 ; j++){

		printf("Information for roll number %d\n",a[j].roll);
		printf("Name: %s\n",a[j].name);
		printf("Marks: %f\n",a[j].marks);
	}
  
	return 0;
}


###Output 🎥

![Image](https://github.com/user-attachments/assets/db3cfc7d-08c4-4650-9169-11b68b88e0c4)
