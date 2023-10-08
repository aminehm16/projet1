#projet
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
srand(time(NULL));
  int nombreMystere = rand() % 10 + 1;
  int supposition;
  int i= 0;
  printf("bienvenue dans le jeu !\n");
  printf("Devinez le nombre entre 1 et 10.\n");
    
    do {
        printf("Entrez votre réponse : ");
        scanf("%d", & supposition);
        i++;
if (supposition < nombreAleatoire) {
    printf("Le nombre à deviner est plus grand.\n");
   }else if (supposition> nombreAleatoire) {
          printf("Le nombre à deviner est plus petit.\n");
 } else {
         printf("Bravo ! Vous avez deviné le nombre en %d essais.\n", i);
        }
    } 
    
    return 0;
}