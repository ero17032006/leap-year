#include <stdio.h>

int main()
{
 int year = 0;
 printf("Enter an Year:");
 scanf("%d", &year);

 if(year % 4 == 0){
   printf("Leap Year");
 }else{
    printf("Normal Year");
 }

}
