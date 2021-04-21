# conditional--statements-2
using switch case

#include <stdio.h>

int main()
{
   printf("choose a number :\n1. zero 0\n2. one 1");
   int a=0;
   scanf("%d",&a);
   switch(a)
   {
       case 0:
          printf("The number is in the list ");
          break;
       case 1:
          printf("The number is in the list ");
          break;
        default : printf("The number is not in the list");
       break;
   }

    return 0;
}
