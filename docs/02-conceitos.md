# 2. Conceitos Fundamentais

## Variáveis

Uma variável é um espaço utilizado para armazenar uma informação que pode ser utilizada durante a execução de um programa. Por exemplo, podemos armazenar a idade de uma pessoa:

    int idade = 20;

Nesse exemplo, idade é o nome da variável e 20 é o valor armazenado.

## Tipos de dados

Os dados podem possuir diferentes tipos. Alguns exemplos em C são:

    int: números inteiros.
    float: números com casas decimais.
    char: um caractere.
    double: números com maior precisão decimal.

## Entrada e saída

Um programa pode receber informações do usuário e apresentar resultados. Em C, podemos utilizar scanf para receber dados:

    int idade;
    scanf("%d", &idade);

Para apresentar informações, podemos utilizar printf:

    printf("Sua idade é %d", idade);

## Estruturas condicionais

Estruturas condicionais permitem que o programa tome decisões. Por exemplo:

    if (idade >= 18) {
        printf("Maior de idade");
    } else {
        printf("Menor de idade");
    }

Nesse caso, o programa verifica uma condição e executa um bloco diferente dependendo do resultado.

## Estruturas de repetição

As estruturas de repetição permitem executar uma determinada ação várias vezes.

Exemplo com for:

    for (int i = 0; i < 5; i++) {
        printf("%d\n", i);
    }

O código executará o bloco repetidamente enquanto a condição estabelecida for atendida.

## Funções

Funções são blocos de código criados para realizar determinada tarefa. Por exemplo:

    int soma(int a, int b) {
        return a + b;
    }

Podemos utilizar essa função sempre que precisarmos realizar uma soma entre dois valores.

## Exercício

Analise um problema simples e identifique:

Quais informações precisam ser armazenadas?
Quais decisões precisam ser tomadas?
Existe alguma tarefa que precisa ser repetida?
Seria possível dividir a solução em funções?