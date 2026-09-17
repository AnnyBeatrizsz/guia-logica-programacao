# Conflito Resolvido

## Contexto

Durante o desenvolvimento do guia, duas branches modificaram simultaneamente a seção de objetivo do arquivo `README.md`.

A branch `main` possuía uma versão do objetivo e a branch `feature/conflito-readme` possuía outra versão.

## Conflito

O Git identificou alterações diferentes na mesma parte do arquivo `README.md` durante a tentativa de merge.

Foram utilizadas as marcações de conflito:

- `<<<<<<< HEAD`
- `=======`
- `>>>>>>> feature/conflito-readme`

## Decisão

As duas versões foram analisadas e uma nova frase foi criada combinando as informações relevantes das alterações. A versão final foi escolhida por apresentar de forma mais clara o objetivo do guia e manter o foco em lógica de programação, exemplos e exercícios.

## Resolução

As marcações de conflito foram removidas manualmente e o arquivo foi revisado antes de concluir o merge.

## Aprendizado

O conflito mostrou que o Git não decide automaticamente qual alteração representa a melhor solução quando duas branches modificam a mesma parte de um arquivo. Nesse caso, foi necessário analisar as alterações e escolher manualmente o conteúdo final.