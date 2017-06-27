# PT-Balalaika
Elma Chips - Tudo noob,tudo corno!!

#include<stdio.h>
#include<locale.h>

int main()
{
    int quem;
    char pergunta[255], setaCima = 24, setaBaixo = 25;
    setlocale(LC_ALL,"Portuguese");
    printf(" \n\t ----PT Elma Chips----- \n____________________________________\n\n\t Pau no cu de quem está lendo \n\n");
    printf("\n Voce é o: \n\n1-Doritos\n\n2-Fandangos\n\n3-Sensacões\n\n4-Ruffles\n____________________________________________");
    scanf("%d",&quem);
    while (quem != 1 && quem != 2 && quem != 3 && quem != 4);
    switch(quem)
    {
        case 1:
            printf("\nDrow off\n\n");
        break;
        case 2:
            printf("\nAop\n\n");
        break;
        case 3:
            printf("\nNet xuxera\n\n");
        break;
        case 4:
            printf("\nPorra, Diego!\n\n");
        break;
        default:
            printf("\n\n\nErrrou\n\n\n\n");
    }
    printf("\n__________________________________________________\n\nAgora vc tem direito a uma pergunta! Pergunte com sabedoria!!!\n");
    scanf("%s", pergunta);
    printf("\nBalalaika é a resposta. Tudo noob %c, tudo corno %c\n", setaBaixo, setaCima);
    system("pause");
    return 0;
}
