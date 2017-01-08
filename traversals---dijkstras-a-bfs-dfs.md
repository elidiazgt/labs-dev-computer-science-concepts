Traversals - Dijkstra's, A\*, BFS, DFS \(know the difference between DFS and BFS when would you use one over the other and why - hint, is usually matters when you don't have to search the whole space.\)

DFS (DFS o Depth First Search)
Una Búsqueda en profundidad  es un algoritmo que permite recorrer todos los nodos de un grafo o árbol de manera ordenada, pero no uniforme. Su funcionamiento consiste en ir expandiendo todos y cada uno de los nodos que va localizando, de forma recurrente, en un camino concreto. Cuando ya no quedan más nodos que visitar en dicho camino, regresa, de modo que repite el mismo proceso con cada uno de los hermanos del nodo ya procesado.

BFS (en inglés BFS - Breadth First Search)
Búsqueda en anchura es un algoritmo para recorrer o buscar elementos en un grafo usado en árboles. Intuitivamente, se comienza en la raíz y se exploran todos los vecinos de este nodo. A continuación para cada uno de los vecinos se exploran sus respectivos vecinos adyacentes, y así hasta que se recorra todo el árbol.

Diferencias entre DFS y BFS
el algoritmo DFS sirve para recorrer una rama completa del arbol que queremos regresando y haciendo lo mismo para las todas las ramas que tenga el árbol, mientras que el BFS recorre todas las ramas simultaneamente sin tener que regresar al nodo principal.
