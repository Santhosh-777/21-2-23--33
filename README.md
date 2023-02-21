#include<stdio.h>
main()
{
    int n,r,s=0;
    scanf("%d",&n);
    while(n>0)
    {
        r=n%10;
        s=s*10+r;
        n=n/10;
    }
    printf("reverse of the given number=%d",s);
    
}
