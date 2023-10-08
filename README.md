#include <stdio.h>

int main() {
    int tableau[]={1,8,4,3,2};
    int i ;
    int somme=0;
    i=0;
    while (i<5){
    somme= somme + tableau [i];
    i=i+1 ;
    }

    printf("La somme des éléments du tableau est : %d\n", somme);

    return 0;
}