# Ordenação

Para avaliação de desenpenho será utilizada a [Notação Big O](../Conceitos#notação-big-o).

## Index
<!-- TOC -->
- [Algoritmos de Ordenação](#algoritmos-de-ordenação)
    - [Bubble Sort](#bubble-sort)
    - [Merge Sort](#merge-sort)
    - [Quick Sort](#quick-sort)
<!-- /TOC -->

## Bubble Sort
![Bubble Sort](https://upload.wikimedia.org/wikipedia/commons/3/37/Bubble_sort_animation.gif)

Bubble Sort é um algoritmo muito simples. Para cada uma das posições da lista é encontrado o menor valor dentre todos os valores que estão à frente. Isto faz com que, posição por posição, a lista vai sendo ordenada.

Desempenho:

Tempo: O(n^2)

Espaço: O(1)

[Wikipedia](https://pt.wikipedia.org/wiki/Bubble_sort)

## Merge Sort
![Merge Sort](https://upload.wikimedia.org/wikipedia/commons/c/c5/Merge_sort_animation2.gif)

Merge sort é um algoritmo de divisão e conquista utilizado para ordenar listas. A lista é recursivamente dividida em duas até que fique de um tamanho mínimo. Estes dois pedaços, já ordenados, são unidos em um vetor maior também ordenado.

Desempenho:

Tempo: O(n Logn)

Espaço: O(n)

[Khan Academy - Visão geral](https://pt.khanacademy.org/computing/computer-science/algorithms/merge-sort/a/overview-of-merge-sort)

[Khan Academy - Análise](https://pt.khanacademy.org/computing/computer-science/algorithms/merge-sort/a/analysis-of-merge-sort)

## Quick Sort
![Quick Sort](https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif)

Quick Sort é um dos algoritmos de ordenação mais populares. A ideia do algoritmo é recursivamente definir um valor aleatório no vetor e separar o vetor entre os valores maiores e menores que este valor definido.

Desempenho:

Tempo: O(n Logn)

Espaço: O(Logn)

[Khan Academy - Visão geral](https://pt.khanacademy.org/computing/computer-science/algorithms/quick-sort/a/overview-of-quicksort)

[Khan Academy - Análise](https://pt.khanacademy.org/computing/computer-science/algorithms/quick-sort/a/analysis-of-quicksort)