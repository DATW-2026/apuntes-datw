# POSIBLES PREGUNTAS EXAMEN

## ¿Cuáles son los tipos de datos en JS?

8 --> PRIMITIVOS (7) Y OBJETOS (1). Las **funciones** son un tipo algo especial, pero es un tipo de **OBJETO**.

### Tipo de datos PRIMITIVOS (7)

- 'Hola mundo 🌍' // string
- 4; // number
- true, false // boolean

- undefined // undefined
- null // null

- 5n // bigint
- Symbol() // symbol

### Tipos de datos REFERENCIADOS u OBJETOS (1)

- {} // object
- [] // object (array)

- () => {} // function (son un tipo especial de objetos)

## ¿Qué son las funciones en JS y cuáles son las partes de una función?

Las funciones son _bloques de código_ con un _nombre_ específico y un conjunto de instrucciones que _realiza una tarea_ o calcula un valor, debe tomar alguna entrada (_parámetros_ = variables) y devolver una salida (_return_) o un efecto (si es _void_) donde hay alguna relación obvia entre la entrada y la salida. Para usar una función, primero se define y luego se invoca cuando se necesita.

Las partes de la función son:

- **Palabra clave:** _function_ define la función
- **Nombre:** en _camelCase_
- **Parámetros:** entre paréntesis. Son un tipo de **VARIABLES**, ya que permiten almacenar valores
- **Argumentos:** valores que se pasan a la función al llamarla. Son **VALORES**, que se almacenan en los parámetros (variables)
- **Cuerpo:** código entre llaves _{}_ de la función

Ejemplo:

```js
//Definición --> nombreFuncion(parámetros)
function addNum(a, b) {
  return a + b; // Cuerpo
}
addNum(2, 4); // Argumentos
```
