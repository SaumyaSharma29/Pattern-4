# Pattern-4
#include<stdio.h>
int main()
{
int i,j,n;
for(i=0;i<n;i++)
{
for(j=n-1-i;j>0;j--)
{
printf(" ");
}
for(j=0;j<=i;j++)
{
printf("*");
}
for(j=i;j>0;j--)
{
printf("*");
}
}
}
