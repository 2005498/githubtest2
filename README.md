#include <stdio.h>
#include <stdlib.h>

void main()
{
    int n,i ,sum=0;
    float avg=0 ;
    printf("enter the range:\n");
    scanf("%d",&n);
    printf("enteries are:\n");
    for(i=1;i<=n;i++)
    {
        printf("%d\n",i);
    }
    for(i=1;i<=n;i++)
    {
        sum+=i;
    }
    printf("sum=%d",sum);
avg= (float)sum/n;  //type casting
printf("\naverage=%f",avg);
 
}
