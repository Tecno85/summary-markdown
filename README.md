# Aprendiendo _Markdown_

### Qué es Markdown

Markdown es un lenguaje de marcado ligero que se utiliza para dar formato a texto de manera sencilla y legible. Fue creado por John Gruber y Aaron Swartz en 2004 con el propósito de facilitar la escritura de documentos de texto plano que puedan convertirse fácilmente en HTML para la web.

Principales características de Markdown:

Simplicidad: Markdown utiliza una sintaxis simple y fácil de leer. Por ejemplo, para hacer un texto en negrita, simplemente se coloca entre dos asteriscos (**negrita**).

Legibilidad: El texto en Markdown es legible incluso sin formato. Es decir, si lees un archivo en Markdown, es fácil entender el contenido sin necesidad de procesamiento adicional.

Conversión a HTML: Markdown está diseñado para ser convertido a HTML de manera sencilla. Esto es útil para la creación de documentos web, blogs y otros contenidos en línea.

Esto es un Párrafo

Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore autem atque id dolorum eaque molestias. Reiciendis perspiciatis incidunt facilis doloremque consectetur, laboriosam cum eius numquam, voluptatibus, quis impedit nemo fugiat.

Aplicando _Cursiva_ y **Negrita**, **_Cursiva y Negrita_**

# Encabezando Nivel 1

## Encabezando Nivel 2

### Encabezando Nivel 3

#### Encabezando Nivel 4

##### Encabezando Nivel 5

###### Encabezando Nivel 6

## Otro encabezado de Ejemplo

## Enlace externo

Ejemplo: [Youtube](https://youtube.com/jonmircha)

## Enlaces o Anclas Internas

Los enlaces o anclas internas solo funcionan con los emcabezados

Ejemplo 1: [Aprendiendo _Markdown_](#aprendiendo-markdown)

Ejemplo 2: [Otro Encabezado](#otro-encabezado-de-ejemplo)

## Imagenes

![This is JavaScript](img/javascript.svg)

## Agregar divisiones o Líneas Horizontales

Este es un texto

---

Y este es otro

---

## Listas Ordenadas y Desordenadas

1. Primavera
1. Verano
1. Otoño

- Primavera
  - Abril
    - Primero :smile:
  - Mayo
  - Junio
- Verano

* Primavera
* Verano

## Citas en Linea

> Siempre tiene opción de no tener opinion. - Marco Aurelio.

## Citas en BLoque

> Todo lo que escuchamos es una opinión, no un hecho.
>
> Todo lo que vemos es la perspectiva, no la realidad.
>
> Marco Aurelio.

## Tablas

| Nombre | Edad | Correo              |
| ------ | ---- | ------------------- |
| Jhon   | 38   | jonmircha@gmail.com |
| Ivan   | 38   | tecno85@gmail.com   |
| Kate   | 36   | keytrin@gmail.com   |

## Presentación de Código

### Código en Línea

Para colocar código de programación junto a un texto y que este se resalte como código. Se utiliza las comillas de acento grave. Un ejemplo seria la palabra reservada (`let`)

### Código en Bloque

En este caso se usa el acento grave tres veces al inicio y tres veces al final. Esta caracteristica permite reconocer si el texto que se quiere representar pertenece a un lenguaje en particular. Solo se coloca las iniciales del lenguaje. Un ejemplo seria:

```js
function sumar(a, b) {
  return a + b;
}
```

En este ejemplo vemos la capacidad que tiene Markdown de detectar HTML de forma nativa.

<form>
    <label for="q"> Buscar: </label>
    <input type="search" name="q" id="q">
</form>

## Comentarios

Se comenta de la misma forma que en HTML

<!--Esto es un comentario -->

### Para ver el código de Markdown

Para poder visualizar el código como se escribe en Markdown, utilizamos la barra invertida ( \ ) anteponiendola a los caracteres especiales para que se muestre en código en su totalidad.

\*\*Negrita\*\* y \_Cursiva\_
