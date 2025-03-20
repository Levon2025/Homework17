# Homework17

#include <stdio.h>
	int main(){
	int num = 0;
	int fact = 1;
 	printf("Input the  value");
	scanf("%d",&num);
	for(int i = 1; i <= num ; i++){
		 fact *= i;
}
	printf(" factorial of %d is  %d\n",num,fact);

	return 0;
} 
