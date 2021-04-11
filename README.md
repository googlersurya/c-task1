#include<stdio.h>
int main()
{
    int a=1,b=2;
    printf("Actual values a=%d b=%d",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("\nAfter swapping a=%d b=%d",a,b);
}
