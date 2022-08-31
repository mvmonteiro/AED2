# Implementação do algoritmo Dijkstra (Caminho de Custo Mínimo)

## Contexto
 - O Algoritmo de Dijkstra (E.W. Dijkstra) é um dos algoritmos que calcula o caminho de custo mínimo entre vértices de um grafo. Escolhido um vértice como raiz da busca, este algoritmo calcula o custo mínimo deste vértice para todos os demais vértices do grafo.
 - Bom nível de performance.
 - Parte-se de uma estimativa inicial para o custo mínimo, o que é ajustado sucessivamente. Ele considera que um vértice estará fechado quando já tiver sido obtido um caminho de custo mínimo do vértice tomado como raiz da busca até ele. Caso contrário ele dito estar aberto. 

 ## Implementação
  - Permitir o armazenamento de até 20 vértices.
  - Fazer a leitura dos pesos das arestas de cada vértice.
  - Considerar sempre vértices positivos.
  - Mostrar o caminho mínimo entre dois vértices solicitados.

  ## Execução
  - Os arquivos .c podem ser clonados através deste mesmo repositório.
  - Primeiro é necessário compilar através de: gcc dijkstra.c -o "nome do seu program" -lm
  - Depois vem a execução a partir de: ./"nome do seu programa"