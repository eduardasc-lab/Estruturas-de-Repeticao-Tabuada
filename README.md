# Estruturas-de-Repeticao-Tabuada
##CÓDIGO

#include <stdio.h>

//Atividade de tabuada\
int main()\
{\
    int tabuada, i;\
    //solicitação do número pra tabuada\ 
    printf("Qual a tabuada? ");\
    scanf("%d", &tabuada);\
    printf("Tabuada do %d:\t", tabuada);\
    //a contagem do segundo número a ser multiplicado começa do 0 até 10\
    //a variável i acrescenta uma unidade a cada execução do for\
    for(i=0; i<=10; i++){\
        printf("%d*%d = %d\t", tabuada, i, tabuada*i);\
    // \t serve para quebrar o texto horizontalmente\
    }\
    return 0;\
}
