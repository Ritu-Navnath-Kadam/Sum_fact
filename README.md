# Sum_fact
#include<stdio.h>

int fact(int);
int fact(int n)
{
int product=1,sum=0;

for(int i=1;i<=n;i++)
{
product=product*i;
sum=product+sum;
}
printf("the factorial of is %d  \n", sum);

}
void main()
{
int n;
printf("enter a number : ");
scanf("%d",&n);
fact(n);
}




