# Floyd-s-triangle-in-c-
#include <stdio.h>

int main()
{   
    int x,row,col;
     x=1;
    for(row=1; row<=4; row++)
    {
        for(col=1;col<=row;col++)
         {
             printf("%d",x);
             x++;
         }
        
    
    printf("\n");
    }
    return 0;
}
