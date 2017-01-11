Trie 2

Los árboles-2-3 son estructuras de datos de árbol que se encuentran comúnmente en las implementaciones de bases de datos y sistemas de archivos. Los árboles 2-3 mantienen los datos ordenados y las inserciones y eliminaciones se realizan en tiempo logarítmico amortizado.

Estos son un tipo de árbol balanceado por altura. Se define como un árbol en dónde todos los nodos no-terminales tienen 2 ó 3 descendientes y todos los nodos hoja tienen la misma longitud o distancia desde la raíz.

Fueron introducidos con el objetivo de mejorar el tiempo de acceso en estructuras de datos manejados en memoria secundaria, donde el número de consultas a un registro influye de manera determinante en el tiempo de respuesta de la operación.

La estructura de árbol 2-3 exige que el crecimiento no se haga a nivel de las hojas (aunque la inserción sigue siendo en las hojas), sino a nivel de la raíz, ya que todas las hojas se deben mantener siempre en el mismo nivel. El proceso global de inserción comienza por localizar la hoja en la cual se debe agregar el elemento.
