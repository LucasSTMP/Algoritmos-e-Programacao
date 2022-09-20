#include <stdio.h>
#include <math.h>
int main(){
    int numero1,numero2;
    int soma,subtracao,multiplicacao,divisao;
    int num;
    int potencia;
    float numero;
    float raiz;
   
    printf("Nome: Lucas Stempozeskas Antony \n");
    printf("Curso: Análise e Desenvolvimento de Sistemas \n");
    printf("Universidade: La Salle \n");
    printf("Matricula: 202213052 \n");
   
    printf("Digite um número para elevar ele à potência: ");
    scanf( "%d",&num);
   
    printf("Digite um número para saber a raiz dele: ");
    scanf( "%f",&numero);
   
    potencia=pow(num,2);
    raiz=sqrt(numero);
   
    printf("O resultado da potenciação é: %d\n",potencia);
    printf("O valor da raiz é: %.2f\n",raiz);
   
    printf("<< Operações aritméticas de soma, subtração, multiplicação e divisão >>\n");
    printf("Digite o primeiro número: ");
    scanf("%d",&numero1);
   
    printf("Digite o segundo número: ");
    scanf("%d",&numero2);
   
    soma=numero1+numero2;
    subtracao=numero1-numero2;
    multiplicacao=numero1*numero2;
    divisao=numero1/numero2;
   
    printf("numero1: %d\n",numero1);
    printf("numero2: %d\n",numero2);
    printf("soma: %d\n",soma);
    printf("subtracao: %d\n",subtracao);
    printf("Multiplicaçao: %d\n",multiplicacao);
    printf("divisao: %d\n",divisao);
   
   
   

    printf("<< OBS >>\n");
         printf("código adaptado do ebook");
             
    return 0;
}
