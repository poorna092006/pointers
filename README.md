#include<stdio.h>
int main()
{
int a=10,b=20,sum;
int *pa,*pb;
pa=&a;
pb=&b;
sum=*pa+*pb;
printf("%d\n",sum);
return 0;
}
