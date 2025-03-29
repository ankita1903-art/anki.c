# anki.c
//want to try this//
#include <stdio.h>
int main() {
    int a[]={1,2,3};

    printf("Size of (a) = %d\n",sizeof(a));
    printf("Size of (a)/sizeof(a[0]) = %d\n",sizeof(a)/sizeof(a[0]));
    for(int i=0; i<3;i++)
    {
        printf("%d\n",i[a]);
    }

}
