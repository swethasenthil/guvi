#include <stdio.h>
#include<conio.h>
void main() {
	int n;
  printf("Enter the number:");
  scanf("%d",&n);
  if(n>=1)
  {
  printf("positive");
  }
  else if(n==0)
  {
  printf("zero");
  }
  else
  {
  printf("negative");
  }
	getch();
}
