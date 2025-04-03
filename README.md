#include <stdio.h>

int main()
{
    
    // Cadastro de cartas
    // carta 01
    char estado1;
    char codigocarta1[2];
    char nomedacidade1[50]
    int populacao1, pontosturisticos1;
    float pib1;
    float areakm1;

    //carta 02
    char estado2;
    char codigocarta2[2]
    char nomedacidade2[50]
    int populacao2, pontosturisticos2;
    float pib2;
    float areakm2

    //Entrada e saida de dados
    //carta 01
    printf("Primeiramente precisamos das informações da carta 01! \n")

    printf("Digite uma letra entre A e H (ela irá representar a carta 01): \n")
    scanf("%c", &estado1);
    
    printf("Digite o código da carta (o código sera correspondente a letra inserida anteriormente + um número de 01 a 04): \n");
    scanf("%s", &codigocarta1);

     printf("Digite o nome da cidade que a carta representará: \n");
     scanf("%s", &nomedacidade1);

     printf("Digite a população da cidade: \n");
     scanf("%i", &populacao1);

     printf("Digite a área em km² da cidade: \n");
     scanf("%f", &areakm1);

     printf("Digite o pib da cidade: \n");
     scanf("%f", &pib1);

     printf("Digite o número de pontos turísticos da cidade: \n");
     scanf("%i", \ &pontosturisticos1);

     printf("OK, Você já inseriu os dados da carta 01.");

     //carta 02
     printf("Agora precisamos das informações da carta 02! \n")

    printf("Digite uma letra entre A e H (ela irá representar a carta 02): \n")
    scanf("%c", &estado2);
    
    printf("Digite o código da carta (o código sera correspondente a letra inserida anteriormente + um número de 01 a 04): \n");
    scanf("%s", &codigocarta2);

     printf("Digite o nome da cidade que a carta representará: \n");
     scanf("%s", &nomedacidade2);

     printf("Digite a população da cidade: \n");
     scanf("%i", &populacao2);

     printf("Digite a área em km² da cidade: \n");
     scanf("%f", &areakm2);

     printf("Digite o pib da cidade: \n");
     scanf("%f", &pib2);

     printf("Digite o número de pontos turísticos da cidade: \n");
     scanf("%i", \ &pontosturisticos2);

     printf("Ótimo, Você inseriu os dados das cartas!! São eles: \n");

     //carta 01
     printf("Carta 01: \n");
     printf("Estado: %c \n, estado1");
     printf("Código da carta: %s \n", codigocarta1);
     printf("Nome da cidade: %s \n", nomedacidade1);
     printf("População da cidade: %i \n", populacao1);
     printf("Área em km²: %f \n", areakm1);
     printf("Pib da cidade: %f \n", pib1);
     printf("Pontos turísticos: %i \n", pontosturisticos1);
     
     //carta 02
     printf("Carta 02: \n");
     printf("Estado: %c \n, estado2");
     printf("Código da carta: %s \n", codigocarta2);
     printf("Nome da cidade: %s \n", nomedacidade2);
     printf("População da cidade: %i \n", populacao2);
     printf("Área em km²: %f \n", areakm2);
     printf("Pib da cidade: %f \n", pib2);
     printf("Pontos turísticos: %i \n", pontosturisticos2);
}