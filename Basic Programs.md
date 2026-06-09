## Addition of Two Nums
```C
#include <stdio.h>

int main()
{
    int a, b, sum;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    sum = a + b;

    printf("Sum = %d", sum);

    return 0;
}
```
## Swap of Two Nums
```C
#include<stdio.h>
int main()
{
   int a, b, temp;

    printf("Enter a and b: ");
    scanf("%d %d", &a, &b);

    temp = a;
    a = b;
    b = temp;

    printf("a = %d\n", a);
    printf("b = %d\n", b);

    return 0;
}
```
## Check Even or Add
```C
#include <stdio.h>

int main()
{
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    if(num % 2 == 0)
        printf("Even");
    else
        printf("Odd");

    return 0;
}
```
## Largest Three nums
```c
#include <stdio.h>

int main()
{
    int a, b, c;

    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);

    if(a >= b && a >= c)
        printf("%d is largest", a);
    else if(b >= c)
        printf("%d is largest", b);
    else
        printf("%d is largest", c);

    return 0;
}
```
