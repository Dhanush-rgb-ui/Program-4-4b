# Module-4 Day-2 SEB
## AIM:
To write a C program to input amount from user and print minimum number of notes (Rs. 500, 100, 50, 20, 10, 5, 2, 1) required for the amount.

## For example
<img width="122" height="227" alt="image" src="https://github.com/user-attachments/assets/0d123722-feae-409d-aba2-d0617c2263eb" />

## Program:
```c
#include<stdio.h>
int main(){
    int n,rem;
    scanf("%d",&n);
    int n500,n100,n50,n20,n10,n5,n2,n1;
    rem=n;
    n500=rem/500;
    rem=rem%500;
    printf("500 = %d\n",n500);
    n100=rem/100;
    rem = rem%;
    printf("100 = %d\n",n100);
    n50=rem/50;
    rem=rem%50;
    printf("50 = %d\n",n50);
    n20=rem/20;
    rem=rem%20;
    printf("20 = %d\n",n20);
    n10=rem/10;
    rem=rem%10;
    printf("10 = %d\n",n10);
    n5=rem/5;
    rem=rem%5;
    printf("5 = %d\n",n5);
    n2=rem/2;
    rem=rem%2;
    printf("2 = %d\n",n2);
    n1=rem;
    printf("1 = %d",n1);
    return 0;
}
```

## Result:
<img width="297" height="612" alt="image" src="https://github.com/user-attachments/assets/ede9cdb3-e016-4c94-93ca-75c6c5246cda" />
