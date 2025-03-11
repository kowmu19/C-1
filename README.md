# C-1

#include <stdio.h>
int main()
{
    for(int i=0;i<=5;i++){
        for(int j=0;j<=5;j++){
            printf("%d*%d=%d\t",j,i,i*j);
        }
        printf("\n");
    }
    return 0;
}

