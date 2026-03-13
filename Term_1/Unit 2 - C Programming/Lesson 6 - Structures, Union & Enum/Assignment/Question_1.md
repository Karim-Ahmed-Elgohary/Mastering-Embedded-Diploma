#include <stdio.h>

struct Student{

	char name[20];
	int roll;
	float marks;
  
};




int main(){

	struct Student S1;

	printf("Enter information of students: \n\n");

	printf("Enter name: ");
	fflush(stdout);
	scanf("%s",S1.name);

	printf("Enter roll number: ");
	fflush(stdout);
	scanf("%d",&S1.roll);

	printf("Enter marks: ");
	fflush(stdout);
	scanf("%f",&S1.marks);

	printf("\nDisplaying information: \n");

	printf("\nName: %s",S1.name);
	printf("\nRoll: %d",S1.roll);
	printf("\nMarks: %f",S1.marks);



### Output
	return 0;
}
