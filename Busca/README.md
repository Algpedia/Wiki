# Busca

Para avaliação de desenpenho será utilizada a [Notação Big O](../Conceitos#notação-big-o).

## Index
<!-- TOC -->
- [Algoritmos de Busca](#algoritmos-de-busca)
    - [Linear](#linear)
    - [Binária](#binária)
<!-- /TOC -->

## Linear
Busca linear é a busca mais simples de todas. Apenas percorre todos os elementos, um por vez. Caso o alvo seja encontrado, retorna o índice.

Desempenho:

Tempo: O(n)

Espaço: O(1)

## Binária

Busca binária é um método para encontrar rapidamente elementos em uma lista de elementos **ordenados**. O algoritmo recursivamente olha o elemento no meio da lista e compara ele com alvo. Caso ele seja o alvo buscado, retorna o índice. Caso ele seja menor que o alvo, busca novamente usando apenas a metade superior da lista. Caso for maior, busca utilizando a metade inferior. No momento em que esta metade for uma lista vazia, significa que o valor não existe na lista.

[Khan Academy](https://pt.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)

Desempenho:

Tempo: O(Logn)

Espaço: O(1)