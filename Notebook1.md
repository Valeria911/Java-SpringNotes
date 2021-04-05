### API
Applicattion Programming Interface. Conjunto de definiciones y protocolos que se utiliza para desarrollar e integrar el software de las aplicaciones

### POO
Cualquier elemento del lenguaje Java es un objeto. Dentro de los objetos se encapsulan los datos que luego son accedidos mediante métodos. 
Un objeto es un elemento de software que intenta representar un objeto del mundo real. De esta forma, un objeto tendrá sus propiedades o atributos y las acciones o métodos a realizar con el objeto. Estas propiedades y acciones están encapsuladas dentro del objeto.

### Encapsulación de datos
La interacción con los objetos se realiza mediante métodos. Si se quiere conocer información del estado del objeto se debe llamar a uno de sus métodos y no directamente a la propiedad. Esta encapsulación permite cambiar los atributos del objeto sin que los consumidores se vean afectados, siempre y cuando se le siga retornando el mismo resultado.

### Beneficios del uso de objetos
- Modularidad: el objeto y sus propiedades pueden ser pasados por distintas estructuras del código fuente y seguir siendo el mismo objeto
- Encapsulamiento de datos: se puede ocultar la implementación de propiedades del objeto ya que se accede mediante los métodos
- Reutilización de código: se puedes tener diferentes instancias de un objeto y que compartan el mismo código
- Reemplazo: se puede reemplazar un objeto por otro siempre y cuando tengan el mismo comportamiento

* Las clases representan los prototipos de los objetos. Son una generalización de un conjunto de objetos. A su vez, un objeto es una instancia de una determinada clase.

- DAO: Data Access Object
- public Class{}
- private atributo;
- private metodo();

* No se importa una clase desde otra clase que se encuentra dentro del mismo paquete

- List<> es una colección de objetos
- ArrayList<> es un arreglo, dinámico. Se importan desde java.util
Declarar ArrayList:
ArrayList <tipo_objeto> variable;
Crear ArrayList:
variable = new ArrayList <tipo_objeto>();

* Método constructor existe por defecto, constructor vacío es importante que exista.

- Instanciar un objeto es crear un nuevo objeto a partir de una misma clase
- toString es un método para "traducir" un objeto, para definir cómo se tiene que ver la información. Sin toString lo que aparece es la ubicación en memoria del objeto
- Una clase objeto no tiene método main, más bien permite generar métodos que luego pueden ser llamados desde una clase principal o desde otros métodos
- Un método con punto sirve para acceder a los elementos que están dentro, cuando son métodos que vienen desde otros archivos
- Si un método es static sólo se puede llamar, no cambiar su comportamiento
- Si un método no es static se puede cambiar su comportamiento mediante la creación de objetos. Se pueden instanciar y modificar
- Sobrecargar un método es tener el mismo método constructor con diferentes parámetros cada vez

Calculator calc = new Calculator(); esto es instanciar un objeto. La clase es Calculator, calc es el nuevo objeto de esa clase.

Los métodos de tipo void no devuelven ningún valor

#### ¿Cómo conseguir que un método devuelva un valor?
- Declarar el método, no debe ser void
- Utilizar la clave return seguida de un valor
- El método debe retornar datos que coincidan con el tipo de retorno


## Clase String
- Viene de java.lang
- No se debe instanciar
- Método length() calcula la longitud de una cadena. Siempre el primer caracter está en posición 0. La coma y el espacio también son caracteres
- Método indexOf() muestra la incidencia de un caracter señalado entre paréntesis
- Método charAt() devuelve el caracter ubicado en el índice entregado como parámetro
- Método subString() puede extraer una subcadena de una cadena determinada. Utiliza begin hasta end, sin incluirlos
- Método replace() sustituye incidencias de caracteres coincidentes
- Método replaceFirst() sustituye sólo la primera incidencia de un patrón de caracteres coincidentes en una cadena
- Operador concatenar "+" convierte todo en cadena, en cambio método concat() sólo une cadenas, ayuda a comprobar compatibilidad

## Clase Random
- Viene de java.util
- Se debe instanciar
  
## Clase Math
- Viene de java.lang
- No se debe instanciar
- Métodos para buscar máximos y mínimos, redondear valores, funciones logarítmicas, funciones trigonométricas, raíz cuadrada

Casting: transformar un número a caracter

DTO: Data Transfer Object. Aquí van las clases con sus objetos, métodos constructores, getter y setter.
DAO: Contiene los métodos y la funcionalidad
Util: lleva el método main
