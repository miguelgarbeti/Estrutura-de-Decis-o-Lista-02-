#include <stdio.h>
#include <stdlib.h>[
#include <math.h>

void exercicio27(){
    float N1, N2, D;
    printf("Insira dois valores numericos inteiros\n");
    scanf("%f", &N1);
    scanf("%f", &N2);
    if (N1 != N2){
        D= N1-N2;
    }
    else {
        D= N2-N2;

    }
   printf("%.0f Diferemca", D);
    return 0;
}

void exercicio28(){
    float N;
    printf("Insira um valor numerico inteiro\n");
    scanf("%f", &N);
    if (N > 0) {
        printf("Positivo");
    }

    else if (N < 0){
        printf("Negativo");

    }
    else
        printf("Neutro");
  return 0;
}

void exercicio29(){
    float N1, N2, N3, N4, M;
    printf("Insira os valores das quatro notas bimestrais\n");
    scanf("%f", &N1);
    scanf("%f", &N2);
    scanf("%f", &N3);
    scanf("%f", &N4);
    M = (N1+N2+N3+N4) /4;
    if (M >= 5){
        printf("Media, %.2f , aprovado ", M);
    }
    else{
        printf("Media, %.2f , Reprovado", M);
    }

return 0;
}

void exercicio30(){
    float N1, N2, N3, N4, M;
    printf("Insira os valores das quatro notas bimestrais\n");
    scanf("%f", &N1);
    scanf("%f", &N2);
    scanf("%f", &N3);
    scanf("%f", &N4);
    M = (N1+N2+N3+N4) /4;
    if (M > 7) {
        printf("Media, %.1f , Aprovado ", M);

    }
    else if (M >= 5) {
        printf("Media, %.1f , Exame"), M;
    }
    else
        printf("Media , %.1f , Reprovado", M);
return 0;
}

void exercicio31(){
        float a, b, c, x1, x2, D;
    printf("Insira o valor do coeficiente a:");
    scanf("%f", &a);
    printf("Insira o valor do coeficiente b:");
    scanf("%f", &b);
    printf("Insira o valor do coeficiente c:");
    scanf("%f", &c);
    D=(b*b) - (4*a*c);
        if (D>= 0 ){
            x1= (-b + sqrt(D))  / (2 * a);
            x2= (-b - sqrt(D))  / (2 * a);
        printf("X1 = %.1f, X2 = %.1f sao as raizes da equacao\n", x1, x2);
        }
        else { printf("Nao existem raizes reais");
        }

return 0;
}

void exercicio32(){
        float N1, N2, N3, T;
    printf("Insira tres valores inteiros");
    scanf("%f", &N1);
    scanf("%f", &N2);
    scanf("%f", &N3);

        if (N1 > N2) {
         T = N1;
         N1 = N2;
         N2 = T;
        }
        if (N1 > N3) {
         T = N1;
         N1 = N3;
         N3 = T;
        }
        if (N2 > N3) {
         T = N2;
         N2 = N3;
         N3 = T;
        }

        printf("Aqui esta numero 1, %.0f, numero 2, %.0f,numero 3, %.0f ", N1, N2, N3);

return 0;
}

void exercicio33(){
float D, N1, N2, N3, N4;
    printf("Insira quatro valores inteiros\n");
        scanf("%f", &N1);
        scanf("%f", &N2);
        scanf("%f", &N3);
        scanf("%f", &N4);

        if (N1 / 2 && N1 / 3 ){ printf("Aqui esta o valor: %f", N1);    }
        if (N2 / 2 && N2 / 3 ){ printf("Aqui esta o valor: %f", N2);    }
        if (N3 / 2 && N3 / 3 ){ printf("Aqui esta o valor: %f", N3);    }
        if (N4 / 2 && N4 / 3 ){ printf("Aqui esta o valor: %f", N4);    }
return 0;
}

void exercicio34(){
float D, N1, N2, N3, N4;
    printf("Insira quatro valores inteiros\n");
        scanf("%f", &N1);
        scanf("%f", &N2);
        scanf("%f", &N3);
        scanf("%f", &N4);

        if (N1 / 2 || N1 / 3)    { printf("Aqui esta por 2: %f", N1);    }
        if (N2 / 2 || N2 / 3)    { printf("Aqui esta por 2: %f", N2);    }
        if (N3 / 2 || N3 / 3)    { printf("Aqui esta por 2: %f", N3);    }
        if (N4 / 2 || N4 / 3)    { printf("Aqui esta por 2: %f", N4);    }


return 0;
}

void exercicio35() {
    float MA, ME, N1, N2, N3, N4, N5;
        printf("Insira cinco valores numéricos inteiros");
    scanf("%f", &N1);
    scanf("%f", &N2);
    scanf("%f", &N3);
    scanf("%f", &N4);
    scanf("%f", &N5);
        MA= N1;
        ME= N1;
        if (N2 > MA) {MA = N2;}
        if (N2 < ME) {ME = N2;}
        if (N3 > MA) {MA = N3;}
        if (N3 < ME) {ME = N3;}
        if (N4 > MA) {MA = N4;}
        if (N4 < ME) {ME = N4;}
        if (N5 > MA) {MA = N5;}
        if (N5 < ME) {ME = N5;}

printf("Aqui esta o maior valor= %f\n", MA);
printf("Aqui esta o menor valor= %f\n", ME);
return 0;
}

void exercicio36() {
int N;
    printf("Insira um numero inteiro");
    scanf("%d", N);
        if ( N%2==0 ) { printf("Par");  }
        else printf("Impar");

return 0;
}

void exercicio37(){
float N;
    printf("Insira um valor numerico inteiro");
    scanf("%f", &N);
        if (N <9) { printf("Valor esta na faixa permitida");     }
        else printf("Valor nao esta na faixa permitida");
return 0;
}

void exercicio38(){
float N;
   printf("Insira um valor numerico inteiro");
    scanf("%f", &N);
        if (N <=3) { printf("Valor = %f", N);}
        else printf("Nemu, valor apresentado");
return 0;
}

void exercicio39(){
int N;
    printf("Insira um numero");
    scanf("%d", &N);
       if ( N%3==0 && N%5==0 ){ printf("Aqui esta o valor: %d", N);}


return 0;
}

void exercicio40(){
 float N1, N2, N3, S;
    printf("insira tres valores numericos inteiros\n");
    scanf("%f", N1);
    scanf("%f", N2);
    scanf("%f", N3);
    S= N1+N2+N3;
        if (S>100) {printf("Aqui esta a soma: %.0f", S); }
        else printf("Nenhum valor foi aprentado");
return 0;
}

void exercicio41(){
float N, R;
    printf("Insira um numero inteiro");
    scanf("%f", &N);
     R = N*2;
    if (R > 30) { printf("Nenhum valor apresentado"); }

return 0;
}



int main()
{
    int opcao;
    do{
        //Exibição do menu
        printf("\n---MENU PRINCIPAL---\n");
        printf("27 - Calculo da Diferença entre Dois Numeros Inteiros\n");
        printf("28 - Classificacao de Numero Positivo ou Negativo\n");
        printf("29 - Calculo da Media e Verificacao de Aprovacao\n");
        printf("30 - Calculo da Media e Verificação de Aprovacao com Exame\n");
        printf("31 - Resolução de Equação de Segundo Grau\n");
        printf("32 - Ordenação de Tres Números Inteiros\n");
        printf("33 - Valores Divisíveis por 2 e 3\n");
        printf("34 - Valores Divisíveis por 2 ou 3\n");
        printf("35 - Maior e Menor Valor\n");
        printf("36 - Par ou Impar\n");
        printf("37 - Verificação de Faixa de Valor\n");
        printf("38 - Verificacao de Valor Menor ou Igual a 3\n");
        printf("39 - Múltiplo de 3 e 5\n");
        printf("40 - Soma e Verificacao\n");
        printf("41 - Multiplicacao e Verificacao\n");


        //leitura da opcao desejada
        printf("Digite a opcao desejada ");
        scanf("%d",&opcao);

        switch (opcao){
        case 27:
            exercicio27();
            break;

        case 28:
            exercicio28();
            break;

        case 29:
            exercicio29();
            break;

        case 30:
            exercicio30();
            break;

        case 31:
            exercicio31();
            break;

        case 32:
            exercicio32();
            break;

        case 33:
            exercicio33();
            break;

        case 34:
            exercicio34();
            break;

        case 35:
            exercicio35();
            break;

        case 36:
            exercicio36();
            break;

        case 37:
            exercicio37();
            break;

        case 38:
            exercicio38();
            break;
        case 39:
            exercicio39();
            break;

        case 40:
            exercicio40();
            break;
        case 41:
            exercicio41();
            break;



        default:
            printf("Opcao invalida! Tente novamente.\n");
        }
    } while (opcao != 0); //repetir até digitar o zero
    return 0;

}
