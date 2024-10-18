PRINTING PATTERN:
****

****

****

****

PREREQUISITE:
Basic knowledge of C language and loops.

ALGORITHM:
Take number of rows as input from the user (length of side of the square) and store it in any variable (‘l ‘ in this case).
Run a loop ‘l ‘ number of times to iterate through the rows . From i=0 to i<l. The loop should be structured as for(i=0;i<l;i++) .
Run a nested loop inside the previous loop to iterate through the columns. From j=0 to j<l. The loop should be structured as for(j=0;j<l;j++) .
Print ‘*’ inside the nested loop to print ‘*’s in all the columns of a row.
Move to the next line by printing a new line. printf(“\n”) .
Code in C:
#include<stdio.h>   
int main()
{
int i,j,l;    //declaring integers i,j for loops and l for number of rows
printf("Enter the number of rows/columns\n");  //Asking user for input
scanf("%d",&l);    //Taking the input for number of rows
for(int i=0;i<l;i++)  //Outer loop for number of rows  
   {
      for(int j=0;j<l;j++)   //Inner loop for number of columns in each row
         {
            printf("*");     //Printing '*' in each column of a row.
         }
      printf("\n");    //Printing a new line after each row has been printed.
   }
}
Taking input:
DISPLAYING OUTPUT:

