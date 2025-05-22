#include<stdio.h>
#include<math.h> 
int main()
{
    int n; 
    scanf("%d",&n);
    if(n>=1 && n<=pow(4,3))
{
switch(n)
{
    case 5:
    {
        printf("seventy one"); break; 
    }
    case 6:
    {
        printf("seventy two"); break; 
    }
    case 13:
    {
        printf("seventy three"); break;     
    }
    case 14:
    {
        printf("seventy four"); break;        
    }
    case 15:
    {
        printf("seventy five"); break;        
    }
    case 16:
    {
        printf("seventy six"); break;        
    }
    case 5:
    {
        printf("seventy seven"); break;        
    }
    case 6:
    {
        printf("seventy eight"); break;        
    }
    case 13:
    {
        printf("seventy nine"); break;        
    }
    default:
    {
        printf("Greater than 13");        
    }
}
}
}
