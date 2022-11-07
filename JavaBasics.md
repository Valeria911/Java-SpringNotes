### Arreglos
- Arreglo o array en Java es una estructura de datos que permite almacenar un conjunto de datos de un mismo tipo. Para manipular estos datos se utiliza un índice.
- En la declaración del arreglo se debe especificar el tamaño o la cantidad de elementos a almacenar. Es de tamaño fijo, no se puede modificar durante la ejecución del programa.
- Comienzan siempre con la posición cero. Se declaran y luego se crean con el operador new.

### ArrayList
- Son dinámicos. 
- algunas funciones: .get() indicar la posición para encontrar un elemento. .remove() indicar la posición para eliminar un elemento. .clear() limpiar la lista. .indexOf() buscar el elemento por su valor para conocer su índice. .set(x,"algo") modificar el valor en el índice x por el valor "algo". .remove()-1 remover el último dato del arraylist.
- Para recorrer un arraylist se puedem utilizar diferentes métodos: forEach es un contador y se instancia como for(String a: alumnos){sout ("nombre" + a);} Iterator se debe importar, permite recorrer, obtener y eliminar. Métodos hasNext(), next(), remove(). ListIterator se debe importar, permite recorrer en ambas direcciones.

### Paradigma de programación Orientada a Objetos
Es la forma de pensar, diseñar, construir e implementar aplicaciones computacionales mediante el uso de objetos a través de la representación de entidades y de sus estados o atributos y sus comportamientos o funcionalidades representadas a través de los métodos del objeto.

Una clase es un archivo que permite respresentar una entidad mediante la definición de sus atributos o características genéricas y de su comportamiento mediante sus métodos.

Los objetos son una construcción en la memoria RAM de las definiciones realizadas en la clase. A esto se le conoce como instacia de la clase.

### Modificadores de acceso
- public establece un acceso abierto para cualquier código que tenga acceso a la clase.
- protected solamente es visible desde cualquier clase del mismo paquete
- private solamente es visible desde las implementaciones de la misma clase
- default es visible solamente dentro del mismo paquete
