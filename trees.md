# Trees \(Tree, Binary Tree, Binary Search Tree, Red-Black Tree, etc. Learn as many as you can\)
* Arbol
Un árbol es una estructura de datos que imita la forma de un árbol como un conjunto de nodos conectados. Un nodo es la unidad sobre la que se construye el árbol y puede tener cero o más nodos hijos conectados a él. Sólo puede haber un único nodo sin padres, que llamaremos raíz. Un nodo que no tiene hijos se conoce como hoja. Los demás nodos se les conoce como rama.

 - Arbol Binario
un árbol binario es una estructura de datos en la cual cada nodo puede tener un hijo izquierdo y un hijo derecho. No pueden tener más de dos hijos (de ahí el nombre "binario"). Si algún hijo tiene como referencia a null, es decir que no almacena ningún dato, entonces este es llamado un nodo externo. En el caso contrario el hijo es llamado un nodo interno.

- Arboles Binario de Busqueda
La búsqueda en un arbol binario de búsqueda consiste en acceder a la raíz del árbol, si el elemento a localizar coincide con éste la búsqueda ha concluido con éxito, si el elemento es menor se busca en el subárbol izquierdo y si es mayor en el derecho. Si se alcanza un nodo hoja y el elemento no ha sido encontrado es que no existe en el árbol.

Para una fácil comprensión queda resumido en que es un árbol binario que cumple que el subárbol izquierdo de cualquier nodo (si no está vacío) contiene valores menores que el que contiene dicho nodo, y el subárbol derecho (si no está vacío) contiene valores mayores.

Para estas definiciones se considera que hay una relación de orden establecida entre los elementos de los nodos. Que cierta relación esté definida, o no, depende de cada lenguaje de programación. De aquí se deduce que puede haber distintos árboles binarios de búsqueda para un mismo conjunto de elementos.

-Árbol rojo-negro
es un tipo especial de árbol binario para organizar información compuesta por datos comparables (por ejemplo, números). En los árboles rojo-negro las hojas no son relevantes y no contienen datos.

En los árboles rojo-negro, como en todos los árboles binarios de búsqueda, es posible moverse ordenadamente a través de los elementos de forma eficiente si hay forma de localizar el padre de cualquier nodo. El tiempo de desplazarse desde la raíz hasta una hoja a través de un árbol equilibrado.

Al implementar esta estructura es posible utilizar un único nodo centinela. Este cumple la función de hoja para todas las ramas del árbol. Así, todos los nodos internos que finalicen en una hoja tienen referencia a este único nodo centinela. Esto no es necesario, ya que puede hacerse una referencia nula (NIL) en el final de cada rama.
