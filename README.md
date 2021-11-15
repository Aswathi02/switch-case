
#include <stdio.h>
void main()
{
     int food;
     printf("Enter a value:");
     scanf("%d",&food);
     switch(food)
     {
         case 1:
           printf("Food:pasta");
           printf("\nprice:Rs280");
                  break;
         case 2:
           printf("Food: pizza");
           printf("\nprice:Rs220");
           break;
         case 3:
           printf("Food: burger");
           printf("\nprice:Rs180");
           break;
         case 4:
           printf("Food:French fries");
           printf("\nprice:Rs90");
           break;
         case 5:
           printf("Food:sandwich");
           printf("\nprice:Rs99");
           break;
         default:
             printf ("not in the menu");
             break;
    }
    return 0;
}
