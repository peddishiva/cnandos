#include<stdio.h>
main()
{
int n,m[20],i,j,sb[20],b[20][20],x;
printf("\nEnter no. of files:");
scanf("%d",&n);
for(i=0;i<n;i++)
{
printf("\nEnter index block of file%d:",i+1);
scanf("%d",&sb[i]);
printf("\nEnter length of file%d:",i+1);
scanf("%d",&m[i]);
printf("enter blocks of file%d:",i+1);
for(j=0;j<m[i];j++)
scanf("%d",&b[i][j]);
}
printf("\nFile\t Index\tLength\n");
for(i=0;i<n;i++)
{
printf("%d\t%d\t%d\n",i+1,sb[i],m[i]);
}
printf("\nEnter file name:");
scanf("%d",&x);
printf("\nfile name is:%d",x);
printf("\nIndex is:%d",sb[x-1]);
printf("\nBlocks occupied are:");
for(j=0;j<m[x-1];j++)
printf("%4d",b[x-1][j]);
}