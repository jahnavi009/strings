# strings
reverse vowels
#include<stdio.h>
void main()
{
int a[20]={'a','e','i','o','u'};
int i,index=0,str[50];
printf("enter any string");
scanf("%s",&str);
for(i=0;str[i]!='\0';i++)
if(str[i]=a[i])
{
a[index++]=str[i];
}
else
{
str[i]=a[index--];
}
printf("%s",str[i]);
}
