#include <stdio.h>
int main()
{
int y;
printf("enter year for checking leap year or not\n");
scanf("%d",&y);
(((y%100!=0)&&(y%4==0))||(y%400==0))?printf("%d is leap year",y):printf("%d is not a leap year",y);
return 0;
}
