# c-program
write a program in c language to table.?
#include <stdio.h>
int main()
{
   int a,x,i;
   printf("Table 1 to ");
   scanf("%d",&x);
   for(a=1;a<=10;a++)
   {
       for(i=1;i<=x;i++)
       {
           if(a*i <10)
           printf("  0%d",a*i);
           else
           printf("  %d",a*i);
       }
       printf(" \n");
   }
}
