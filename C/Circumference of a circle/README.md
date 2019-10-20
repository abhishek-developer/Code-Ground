Write a program to find out circumference of a circle

Input : radius
Output : circumference
#include<stdio.h>

int main()
{
  int radius;
  float cir;
  
  printf("Enter Radius of the Circle");
  scanf("%d",&radius);
  
  cir=2*3.14*radius;
  
  printf("Circumference of the Circle:%.2f",cir);
  return 0;
}  


