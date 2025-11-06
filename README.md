#include <stdio.h>

int main( ) {
    float current;       
    float limit = 5.0;  

    printf("Enter current value (in Amps): ");
    scanf("%f", &current);

    if (current > limit) {
        printf("Short Circuit Detected\n");
    } 

     else if (current < limit){
            printf(“Short Circuit Detected\n”);
           }

   else {
        printf("System Normal\n");
    }

    return 0;
}

