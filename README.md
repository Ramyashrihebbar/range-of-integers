# range-of-integers
#include <stdio.h>
 
int main(void) {
 
	// Define the two integer variables
	int L,R,num;
 
	// Get L and R from the user
	scanf("%d", &L);
	scanf("%d", &R);
    
	// Write here the logic to print all integers between L and R
 
  for (num = L; num <= R; num++)

             {

                printf("%d ", num);

             }
	return 0;
}
