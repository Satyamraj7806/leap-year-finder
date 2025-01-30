# leap-year-finder
#include<stdio.h>
int main()
{
    int a;
     printf("enter the year");
     scanf("%d",&a);
     if(a%100==0)
     {
        if(a%400==0)
        {
            printf("the year %d is a leap year",a);
        }
        else
        {
            printf("the year %d is not a lwap year",a);
        }
     }
     else
     {
        if(a%4==0)
        {
            printf("the year %d is a leap year",a);
        }
        else 
        {
            printf(" the year %d is not a leap year",a);        }
     }
}

![image](https://github.com/user-attachments/assets/8636e8ed-5a1f-48c4-8568-0cf2c9d25773)

