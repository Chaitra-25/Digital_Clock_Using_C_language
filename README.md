# Digital_Clock_Using_C_language
#include<stdio.h>
#include<windows.h>
int main()
{
int h,m,s;
int d=1;
printf("set time:\n");
scanf("%d 5d %d", &h,&m,&s);
if(h<12||m>60||s>60)
{
printf("error\n");
exit(0);
}
while(1)
{
s++;
if(s>59)
{
m++;
s=0;
}
if(m>59)
{
n++;
m=0;
}
if(h>12)
{
h=1;
}
printf("\n clock:");
printf("0.2d: %0.2d :%0.2d",h,m,s);
sleep(d);
system("cls");
}
}
