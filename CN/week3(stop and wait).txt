#include<stdio.h>
#include<stdlib.h>
int main()
{

int i,j,noframes,x,x1=10;
for(i=0;i<200;i++)
rand();
noframes=rand()/200;
i=1;
j=1;
noframes=noframes/8;
printf("\n Number of frames is %d", noframes);
getch();
while(noframes>0)
{
printf("\n Sending frame %d",i);
srand(x1++);
x=rand()%10;
if(x%2==0)
{
printf("\nsending frame %d",i);
srand(x1++);
x=rand()%10;
}
printf("\n Ack for frame %d ",j);
noframes-=1;
i++;
j++;
}
printf("\n End of Stop and wait protocol");
}