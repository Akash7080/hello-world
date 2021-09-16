#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{
    
    char s[100]="welcome to C programming";
       scanf("%[^\n]%*c", &s);
      
    printf("Hello, World!\n%s",s);
    //printf("welcome to c programming"); 
    return 0;
}
  
  
  
  
