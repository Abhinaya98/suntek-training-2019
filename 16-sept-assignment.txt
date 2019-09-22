//# suntek-training-2019
#include<stdio.h>
void main()
{
char ch[50];
int i,fr[256]={0};
printf("enter a string");
gets(ch);
for(i=0;ch[i];i++)
{
fr[ch[i]]++;
}
for(i=0;ch[i];i++)
{
if(fr[ch[i]]!=0)
{
printf("%c - %d",ch[i],fr[ch[i]]);
fr[i]=0;
}
}
