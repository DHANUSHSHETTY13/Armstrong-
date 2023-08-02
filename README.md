#include<stdio.h>
int main()
{
int n;
printf("enter the numebr =");
scanf("%d",&n);
int x=fun(n);
printf("%d\n",x);
if
    (x==n)
printf("yes\n");
else
printf("no\n");
}


//armstrong logic
int fun(n)
{
    int r,c,temp=0,sum=0;
temp=n;
while(n>0)
{

r=n%10;
c=r*r*r;
sum=sum+c;
n=n/10;
}
n=temp;

return sum;
}

