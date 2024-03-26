#include <stdio.h>

int main()
{
    int i=1;

    while(i<=5)
    {
        i++;
        printf("%d", i);
    }
    

return 0;
}    

-------------------------------------------------------------------


#include <stdio.h>
int add(int a, int b);
int minus(int a, int b);
int multi(int a, int b);
int div(int a, int b);
int main()
{
    int a,b;
    int result=0;
    scanf("%d %d", &a, &b);
    result = add(a,b),minus(a,b)/multi(a,b)/div(a,b);
    printf("%d + %d = %d\n", a,b,result);
    printf("%d - %d = %d\n", a,b,result);
    printf("%d * %d = %d\n", a,b,result);
    printf("%d / %d = %d\n", a,b,result);
    return 0;
}
int add(int a,int b)
{return a+b;}
int minus(int a, int b)
{return a-b;}
int multi(int a, int b)
{return a*b;}
int div(int a, int b)
{return a/b;}
