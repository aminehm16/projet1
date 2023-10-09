#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main() {
    int t[5];
    int i, s = 0; // Initialisez 's' à 0

    printf("Donnez des valeurs pour le tableau\n ");
    
    for (i = 0; i < 5; i++) {
        scanf("%d", &t[i]); // Supprimez la virgule et corrigez la syntaxe de scanf
        s = s + t[i];
    }

    printf("La somme des éléments du tableau est %d\n", s); // Déplacez cette ligne en dehors de la boucle for
    
    return 0;
}
