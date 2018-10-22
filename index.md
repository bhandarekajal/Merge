#include <stdio.h>

int main()
{
   char a1[20]={1,2,3};
   char a2[20]={'a','b','c','s'};
   int i,n=0,a3[20]={0},len;
   for(i=0;i<7;i++)
   {
       if(len<=2)
       {
       a3[n]=a1[i];
       printf(",%d",a3[n]);
       
       }
       a3[n+1]=a2[i];
       printf(",'%c'",a3[n+1]);
       n++;
       
   }
   /*for(i=0;i<5;i++);
   printf("%s",a3[i]);*/
    return 0;
}
