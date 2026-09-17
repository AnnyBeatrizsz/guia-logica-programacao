# Exemplo Básico

## Problema

Criar um programa que receba dois números e informe a soma deles.

## Análise

Precisamos:

1. Receber o primeiro número.
2. Receber o segundo número.
3. Somar os dois valores.
4. Mostrar o resultado.

## Algoritmo

Início
    Receber primeiro número
    Receber segundo número
    Somar os dois números
    Mostrar o resultado
Fim


## Implementação em C

#include <stdio.h>

int main() {
    int numero1, numero2, resultado;

    printf("Digite o primeiro numero: ");
    scanf("%d", &numero1);

    printf("Digite o segundo numero: ");
    scanf("%d", &numero2);

    resultado = numero1 + numero2;

    printf("Resultado: %d\n", resultado);

    return 0;
}

## O que aprendemos?

Esse exemplo demonstra como transformar um problema em uma sequência de passos e posteriormente, implementar esses passos utilizando uma linguagem de programação.