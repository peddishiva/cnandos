#include<stdio.h>
#include<conio.h>
#include<string.h>
int main()
{
    char a[100],b[100],c[100];
    int i,j=0,n,k=0;
    printf("Enter the Data:");
    gets(a);
    n=strlen(a);

    for(i=0;i<n;i++)
    {



        if((a[i] == 'd' && a[i+1]=='l' && a[i+2]=='e')||
(a[i] == 'E' && a[i+1]=='S' && a[i+2]=='C'))
        {
            c[k++] = 'E';
            c[k++] = 'S';
            c[k++] = 'C';

        }
        c[k++] = a[i];
    }



    c[k++] = '\0';

    b[j++]='\0';
    printf("%s\n",b);
    printf("DLESTX \t");
    printf("%s",c);
     printf("\t DLEETX ");
    return 0;
}