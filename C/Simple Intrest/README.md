Write a program to calculate simple interest
Input : Principal amount, Rate, Time Period
Output : Simple interest
#include<stdio.h>

int main()
{
    
    int p,n;
    float r,s;
    
    
    p=1000;
    n=4;
    r=8.5;
    /*formula for the simple interest*/
    si=p*n*r/100;
    printf("%f\n",si);
    return 0;
 }   
