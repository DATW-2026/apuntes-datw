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
//Definición --> nombreFunción(parámetros)
function addNum(a, b) {
    return a + b; // Cuerpo
}
addNum(2, 4); // Argumentos
```

## Los básicos de HTML

Los HTML deben tener los elementos básicos del _boiler plate_ según lo genera _emmet_ (!) y validar en el [Validador HTML](https://validator.w3.org/). También deben llevar **favicon** y **descripción**. Si no, **SUSPENDE EL EXAMEN**.

## Diferencias entre HTML y DOM (Document Object Model)

**HTML** -> _Parsing y creación del árbol del DOM por parte del navegador_ -> **DOM**

## ¿Qué son las API Web?

Conjunto de funciones de JS que proporciona el navegador más allá del núcleo de JS

## ¿Qué es un motor de JS?

Es un programa informático que ejecuta código JavaScript, convirtiéndolo o compilando en lenguaje que la CPU puede entender (lenguaje de bajo nivel). Transforma el código de alto nivel en instrucciones que permiten la interactividad y funcionamiento de aplicaciones web.

Ej: V8 (Chrome y Node).

## ¿Cómo funciona un navegador (parsing, render, etc...)?

## Diferencia entre node y el navegador

Node es el motor de renderizado del navegador sin sus API webs

## Transpilador

Convierte de un lenguaje de alto nivel a otro lenguaje de alto nivel
