#include <stdio.h>
#include <conio.h>

int main() 
{ 
    int i, sn; 
    int st[20]; 
    char op; 

    printf("\n How many stations: "); 
    scanf("%d", &sn); 

    do 
    { 
        printf("\n Enter status of stations\n"); 
        for (i = 0; i < sn; i++) 
        { 
            printf(" Enter status of station %d: ", i + 1); 
            scanf("%d", &st[i]); 
        } 

        // Print ready stations 
        for (i = 0; i < sn; i++) 
        { 
            if (st[i] == 1) 
            { 
                printf(" Station %d is ready to transmit\n", i + 1); 
            } 
        } 

        printf(" Repeat? Press Y :"); 
        scanf(" %c", &op); 
    } 
    while (op == 'y' || op == 'Y'); 

    getch(); 

    return 0; 
}