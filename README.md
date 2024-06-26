#include <stdio.h>
void fun(int a,int b)
{
    int c,d,e,f;
    c=a+b;
    d=a-b;
    e=a*b;
    f=a/b;
    printf("%d\t",c);
    printf("%d\t",d);
    printf("%d\t",e);
    printf("%d",f);
}
int main()
{
   fun(10,20);
   fun(20,40);
    return 0;
}
