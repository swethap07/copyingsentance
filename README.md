# copyingsentance
#include<stdio.h>
#include<string.h>

void main()
{
    int i = 0;
    char a[50], b[50];

    printf("enter the string1");
    scanf("%[^\n]s", a);

    do
    {
        b[i] = a[i];
        i++;
    }
    while(a[i] != '\0');

    b[i] = '\0';

    printf("copied string is %s", b);
}
