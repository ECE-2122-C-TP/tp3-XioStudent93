# tp3-XioStudent93
tp3-XioStudent93 created by GitHub Classroom

#include <stdio.h>

int main() {
    printf("Hello, World!\n");

//exercice1

    int var1 = 0;
    int var2 = 0;
    printf("saisissez un entier au clavier: \n");
    scanf("%d", &var1);
    printf("saisissez un entier au clavier: \n");
    scanf("%d", &var2);
    if (var1<var2) {
        printf("le plus grand des deux entier est %d. \n", var2);
    }
    else if (var1>var2) {
        printf("le plus grand des deux entier est %d. \n", var1);
    }
    else {
        printf("vous avez saisie le meme entier.: \n");
    }

//exercice2

    int longueur = 0;
    int largeur = 0;
    printf("saisissez au clavier la longueur.: \n");
    printf("saisissez au clavier la largeur.:\n");
    scanf("%d, %d", &longueur, &largeur);
    int per = (largeur+longueur)*2;
    int air = largeur*longueur;
    printf("le périmetre du rectangle vaut %d.\n", per);
    printf("l'air du rectangle vaut %d.\n", air);

//exercice3

    int nomb = 0;
    int entier = 0;
    const multi = 3;
    printf("saisissez un entier au clavier.: \n");
    scanf("%d", &nomb);
    if (nomb>=10) {
        printf("l'entier saisie est superieur ou égal a dix.: \n");
    }
    else if (multi*entier==nomb) {
        printf("l'entier saisie est un multiple de trois.: \n");
    }
    else {
        printf("l'entier saisie n'est ni inferieur ou egal a dix ni un multiple de trois.: \n");
    }

//exercice5

    int numeroBoisson = 0;
    printf("saisissez un nombre sur le distributeur.: \n");
    scanf("%d", numeroBoisson);
    for (numeroBoisson=1; numeroBoisson<4; numeroBoisson++) {
        if (numeroBoisson==1) {
            printf("la boisson est de l'eau fraiche.: \n");
        }
        else if (numeroBoisson==2) {
            printf("la boisson est du thé glacé.: \n");
        }
        else {
            printf("la boisson est du coca.: \n");
        }
    }
    if (numeroBoisson=10) {
        printf("la boisson est du thé.: \n");
    }
    else if (numeroBoisson=11) {
        printf("la boisson est du café.: \n");
    }

//exercice6

    float note1 = 0;
    float note2 = 0;
    float note3 = 0;
    printf("saisir trois notes au clavier.: \n");
    scanf("%f, %f, %f", note1, note2, note3);
    if ((note1, note2, note3)>0 && (note1, note2, note3)<20) {
        printf("la moyenne des trois notes vaut %d.\n", (note1+note2+note3)/3);
    }
    else {

    }

    return 0;
}
