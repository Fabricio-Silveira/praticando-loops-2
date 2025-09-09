# praticando-loops-2
dessa vez com o segundo loop no meio do primeiro
- - - - - - - - - - - - - - - - - - - - - - - - - -

#include <stdio.h>
#include <stdlib.h>

int main()
{

    int v1 = 11;
    int v2 = 20;

    while (v1 <= v2)
    {  printf ("ainda nao no v1\n");
        printf ("%d",v1);
        printf ("---\n");

    if (v1 == 16)
         {
            int v3 = 6;
            while (v3 >= 2){
                printf ("ainda nao e o suficiente no v2\n");
                printf ("%d",v3);
                printf ("---\n");
                    v3 --;}
        }
                v1 ++;
    }

    return 0;

}
