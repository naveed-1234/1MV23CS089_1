
#include<stdio.h>
int main()
{
   int a,b;
   printf("Enter a value:\n");
   scanf("%d",&a);
   printf("Enter b value:\n");
   scanf("%d",&b);
   if(a>b)
   {
     printf("A is greater");
   }
   else if(a==b)
   {
     printf("Both are equal ");
   }
   else
   {
     printf("B is greater");
    }
    return 0;
  }
