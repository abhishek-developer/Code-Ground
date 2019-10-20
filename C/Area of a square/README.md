Write a program to find the area of a square
Input : number of sides
Output : Area
#include<stdio.h>
int main()
{

  int side,area;
  
  printf("\nEnter the length of the side:");
  scanf("%d",&side;);
  
  area=side*side;
  
  printf("\nArea of Square :%d",area);
  
  return 0;
} 
