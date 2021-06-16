#include<stdio.h
int main()
{
printf("Enter marks:");
int marks=0;
scanf("%d",&marks);
if(marks<0||marks>100)
{
printf("wrong entry");
}
else if(marks<40)
{
printf("grade=E");
}
else if(marks>=40&&marks<54)
{
printf("grade=D");
}
else if(marks>=55&&marks<69)
{
printf("grade=C");
}
else if(marks>=70&&marks<84)
{
printf("grade=B");
}
else if(marks>=85&&marks<100)
{
printf("grade=A");
}
else
{
printf("grade=A+");
}
return (0);
}
