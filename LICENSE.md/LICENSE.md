#include<stdio.h>
#include <string.h>
 
int main()
{
   char a[100], b[100];
 
   printf("Enter a string ");
   gets(a);
 
   strcpy(b,a);
   
   strrev(b);
 
   if (strcmp(a,b) == 0)
   
      printf( "string is a palindrome");
      
   else
   
      printf(" string is not a palindrome");
 
   return 0;
   
   
}
