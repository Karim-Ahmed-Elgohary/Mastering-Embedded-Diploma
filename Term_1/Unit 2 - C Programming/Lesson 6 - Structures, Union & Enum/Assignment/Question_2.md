#include <stdio.h>

struct FI_Distance{

	float feet;
	float inch;
  
};

void add_distance(struct FI_Distance d1, struct FI_Distance d2){

	float f,i;
	f = d1.feet + d2.feet;
	i = d1.inch + d2.inch;

	while(i>=12){
		f++;
		i-=12;
	}

	printf("Sum of distances: %f'-%f\"",f,i);

}





int main(){

	struct FI_Distance x,y;

	printf("Enter information for 1st distance\n");

	printf("Enter feet: ");
	fflush(stdout);
	scanf("%f",&x.feet);

	printf("Enter inch: ");
	fflush(stdout);
	scanf("%f",&x.inch);

	printf("Enter information for 2nd distance\n");

	printf("Enter feet: ");
	fflush(stdout);
	scanf("%f",&y.feet);

	printf("Enter inch: ");
	fflush(stdout);
	scanf("%f",&y.inch);

	add_distance(x,y);

	return 0;
}


###Ouput 🎥

![Image](https://github.com/user-attachments/assets/c5fa4906-4ba7-4cad-8383-ea46b6e85f00)
