---
description: MDC. Equações Diofantinas.
---

# Grafos 4 Dummies (Cheat Sheet)

[[toc]]

## Grafo

Um grafo é um par $g = (V,E)$, onde:

- $V$ é um conjunto de vértices finito e não vazio
- $E$ é o conjunto dos dos pares de vértices que estão ligados por uma **aresta**

- `Ordem do grafo`, $p$, é o número de vértices do grafo.
- `Tamanho do grafo`, $q$, é o número de arestas do grafo

Seja $g = (V,E)$,

$$
p = \#V\\
q = \#E
$$

#### Grau de um vértice

$g = (V,E)$. Para um vértice $v\in V$, o seu grau **em $g$** corresponde ao número de arestas de $g$ que incidem em $v$.  
$$\operatorname{deg}_g(v)$$

## Teoremas

### Teorema Fundamental da Teoria dos Grafos

Num grafo $g=(V,E)$, a soma dos graus dos seus vértices é igual ao **dobro** do Tamanho do grafo.

### Teorema 2

Num grafo $g = (V,E)$, o número dos seus vértices ímpares é par.

## Definições

#### Grafo Regular

Um grafo diz-se regular se todos os seus **vértices têm o mesmo** grau.

#### Grafo Completo

Um grafo diz-se completo quando cada par de vértices constitui uma aresta (está tudo ligado).

- Todo o grafo completo de $k$ vértices é $k$-1 regular
- $\binom{p}{2} = \frac{p(p-1)}{2}$ é o número máximo de arestas que um grafo pode ter
- $K_n \rightarrow$ grafo completo de $n$ vértices

#### Rede

Uma Rede é um grafo onde as arestas têm valores reais associados.

#### Multigrafo

É uma rede com arestas com apenas números naturais.

#### Caminho

Caminho é uma seguimento alternado de vértices e arestas.

#### Atalho

Caminho que não repete arestas.

#### Trajetória

Caminho que não repete vértices. (Aberta)\
Se o vértice inicial for igual ao final, a trajetória é fechada.

#### Vértice Conectados

2 vértices em que existe um caminho entre eles.\
Também se considera se os vértices forem iguais.

#### Grafo Conexo

É conexo se quaisquer dois vértices do grafo estiverem conectados.

#### Componente

$h$ é uma componente de um grafo $g$, se $h$ for um grafo conexo de $g$ e\
 **não for** subgrafo de nenhum outro subgrafo conexo de $g$.

<img src="./imgs/1006-euc.png" alt="ponteeuclidiana" class="invert-dark2">
