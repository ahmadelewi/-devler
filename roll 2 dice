# -devler




#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{

    srand (time(NULL));

    int dice = 2;
    int roll = 0;
    int sum = 0;
    int point = 0;

   for (int i = 1; i <= dice ; i++){

    roll = rand() %6 + 1;
    sum += roll;
    
    printf("Dice %d: %d\n" , i , roll);


   }

  if (sum == 7 || sum == 11){

    printf("You Won!!!\n");
  }

  if (sum == 1 || sum == 2 || sum == 12){

    printf("You Lost!!!\n");
  }

if (sum == 4 || sum == 5 || sum == 6 || sum == 8 || sum == 9 || sum == 10){

    point==sum;
}


    return 0;
}
