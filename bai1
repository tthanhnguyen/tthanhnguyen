- #include <conio.h>
#include <stdio.h>
void main()
{
    int a,b;
    printf("nhap a: ");
    scanf("%d",&a);
    while(a<=1)
    {
        printf("nhap lai a > 1:");
        scanf("%d",&a);
    }
    printf("nhap b: ");
    scanf("%d",&b);
    while(b<=a+100)
    {
        printf("nhap lai b > a+100:");
        scanf("%d",&b);
    }
    int n=a;
    while(n<=b)
    {
        int f=0;
        for(int i=2;i<n;i++)
        {
            if(n%i==0)
            {
            f=1;
            break;
            }
        }
        if(f==0)
        printf("%d ",n);
        n++;
    }
}
