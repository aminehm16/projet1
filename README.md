#include <stdio.h>
#include <stdlib.h>
#include <math.h>
int main() {
    int t[5];
    int i ,s ;
    printf("donner des valeurs pour le tableau\n ");
    for ( i=0 ; i<5 ; i++ ){
    s=s+t [i] ;
    scanf("%d ,&t[i]");
    }
    s=0 ;
    for ( i=0 ; i<5 ; i++ ){
    s=s+t [i] ;
    printf("la somme des éléments de tableau est %d",s);
    }
    
    return 0 ;
    }