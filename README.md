#include<stdio.h>
void toh(int n, char src, char des,char aux)
{if (n ==0) return;
toh(n-1,s,a,d);
printf("Move disc %d from %c to %c\n",n, src,des);
toh(n-1, aux, des, src);}
void main()
{
int n;
printf("Enter the number of discs:\n");
scanf("%d" ,&n);
toh(n ,'S','D','A');
}
