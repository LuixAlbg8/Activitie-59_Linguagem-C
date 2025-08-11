# Activitie-59_Linguagem-C
#include <stdio.h>

int main() {
   int num[5], i;
   
   num[0] = 10;
   num[1] = 20;
   num[2] = 30;
   num[3] = 40;
   num[4] = 50;
   
   for(i = 0; i < 5; i++){
       printf("Valor do vetor na posição %d: %d\n", i,  num[i]);
   }

    return 0;
}


