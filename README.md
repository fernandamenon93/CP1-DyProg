# CP1-DyProg

# Checkpoint 1 – Dynamic Programming
#### (Optamos pelo RA ímpar, já que a maioria dos integrantes do grupo possui essa numeração.)
## Visão Geral
Este projeto explora o uso de Programação Dinâmica para implementar algoritmos de ordenação.O objetivo principal é aplicar diferentes abordagens de ordenação e comparar seus desempenhos em cenários distintos.Os principais desafios abordados no projeto incluem:

Ordenação de pontos com base na distância de Manhattan.
Ordenação de palavras segundo uma ordem personalizada.
Comparação de desempenho entre os algoritmos Merge Sort e Quick Sort.
Os códigos foram desenvolvidos em Python 3.x e executados no Jupyter Notebook para facilitar a visualização e análise.

## Estrutura do Projeto

ordenacao_manhattan.ipynb → Algoritmo para ordenar pontos com base na distância de Manhattan.
ordenacao_palavras.ipynb → Ordenação de palavras conforme uma ordem definida.
comparacao_merge_quick.ipynb → Comparação de desempenho entre os algoritmos Merge Sort e Quick Sort.

## Tecnologias Utilizadas
Python
Bibliotecas:
time → Medição do tempo de execução.
sys → Medição de uso de memória.

## Detalhamento das Soluções
#### 1. Ordenação de Pontos pela Distância de Manhattan
O algoritmo implementado utiliza o método Merge Sort para ordenar uma lista de pontos (x, y) de acordo com a distância de Manhattan.

#### 2. Ordenação de Palavras com Ordem Personalizada
Nesta tarefa, foi implementado um algoritmo de ordenação utilizando Merge Sort para classificar palavras de acordo com uma ordem definida. Para isso, usamos um dicionário de prioridade que mapeia cada caractere para um valor de prioridade.

#### 3. Medição de Desempenho: Merge Sort vs Quick Sort
As tarefas 2.1 e 2.2 compararam os algoritmos Merge Sort e Quick Sort,tanto em termos de tempo de execução quanto de uso de memória.

## Medição de Tempo:
#### Utilizamos o módulo time para medir o tempo de execução dos algoritmos.

import time
start = time.time()
merge_sort(lista)
end = time.time()
print(f"tempo: {en -start}s")
Medição de memória:
Através do módulo sys,foi possível medir o uso de memória dos algoritmos

Este projeto aplica conceitos avançados de programação, com ênfase em Programação Dinâmica, para resolver problemas de ordenação e análise de desempenho.
As implementações foram cuidadosamente organizadas para facilitar a compreensão dos algoritmos e seus impactos no desempenho.

## Integrantes:
### Fernanda Rocha Menon - Rm554673
### Luiza Macena Dantas - Rm556237
### Roger Cardoso Ferreira - Rm557230
