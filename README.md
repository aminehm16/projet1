#projet
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
srand(time(NULL));
  int nombreMystere = rand() % 100 + 1;
   int supposition;
    int i= 0;
  printf("bienvenue dans le jeu de devinette!\n");
