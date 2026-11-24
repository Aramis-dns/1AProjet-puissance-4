# 1AProjet-puissance-4
#include <stdio.h>
#define LIGNES 6
#define COLONNES 7
#define NB_ALIGNES 4
#define VIDE 0
#define JOUEUR1 1
#define JOUEUR2 2
void initialiser_plateau(int plateau[LIGNES][COLONNES]) {
    for (int i = 0; i < LIGNES; i++) {
        for (int j = 0; j < COLONNES; j++) {
            plateau[i][j] = VIDE;
        }
    }
}

int main(void) {
    int plateau[LIGNES][COLONNES];
    int joueur = JOUEUR1;

    initialiser_plateau(plateau);
    return 0;
