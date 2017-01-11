linked hash map

Un LinkedHashMap es una combinación de tabla hash y lista enlazada. Tiene un orden de iteración predecible (una lista enlazada), pero la velocidad de recuperación es la de un HashMap. El orden de la iteración está determinado por el orden de inserción, por lo que obtendrá la clave / los valores de nuevo en el orden en que se agregaron a este mapa. Tienes que ser un poco cuidadoso aquí, ya que volver a insertar una clave no cambia el orden original.

La ventaja es que puedes caminar los elementos existentes en un HashMap en orden de inserción, debido a la naturaleza de LinkedList, y puedes saltar rápidamente al cubo correcto en una búsqueda clave (ahorrando mucho tiempo para una colección grande) si Tienen la clave del elemento.
