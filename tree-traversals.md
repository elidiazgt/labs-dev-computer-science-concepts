                                                                                      Tree traversals \( all of these inorder, preorder, postorder, level order\)

Árboles binarios.

El recorrido de árboles se refiere al proceso de visitar de una manera sistemática, exactamente una vez, cada nodo en una estructura de datos de árbol. Tales recorridos están clasificados por el orden en el cual son visitados los nodos. Los siguientes algoritmos son descritos para un árbol binario, pero también pueden ser generalizados a otros árboles.

Preorden: (raíz, izquierdo, derecho). Para recorrer un árbol binario no vacío en preorden, hay que realizar las siguientes operaciones recursivamente en cada nodo, comenzando con el nodo de raíz:
Visite la raíz
Atraviese el sub-árbol izquierdo
Atraviese el sub-árbol derecho

Inorden:
(izquierdo, raíz, derecho). Para recorrer un árbol binario no vacío en inorden (simétrico), hay que realizar las siguientes operaciones recursivamente en cada nodo:
Atraviese el sub-árbol izquierdo
Visite la raíz
Atraviese el sub-árbol derecho

Postorden:
(izquierdo, derecho, raíz). Para recorrer un árbol binario no vacío en postorden, hay que realizar las siguientes operaciones recursivamente en cada nodo:
Atraviese el sub-árbol izquierdo
Atraviese el sub-árbol derecho
Visite la raíz

Diferencias
-En general, la diferencia entre preorden, inorden y postorden es cuándo se recorre la raíz. En los tres, se recorre primero el sub-árbol izquierdo y luego el derecho.
-En preorden, la raíz se recorre antes que los recorridos de los subárboles izquierdo y derecho
-En inorden, la raíz se recorre entre los recorridos de los árboles izquierdo y derecho, y
-En postorden, la raíz se recorre después de los recorridos por el subárbol izquierdo y el derecho
Preorden (antes), inorden (en medio), postorden (después).
