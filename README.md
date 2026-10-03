#Check-whether-a-number-is-odd-or-even, Using only ' if ' condition.
 
#include <stdio.h>

int main()
{
    int n;
    printf("enter the value of n: ");
    scanf("%d",&n);
    
     if(n%2==0){
         printf("n is even number");
     }
     if(n%2!=0){
         printf("n is odd number");
     }

    return 0;
}