# _Markdown_

_Markdown_ es un lenguaje de marcado que sirve para definir contenido. Es muy usado para documentar proyectos de _software_, es el estándar en el que se redacta la documentación. También es utilizado para crear contenido estático que posterirmente se pueda compilar a código _HTML_.

## Índice de Contenido

- [Introducción](#markdown).
- [Párrafos](#párrafos).
- [Encabezados](#encabezados).
- [Imágenes](#imágenes).
- [Enlaces](#enlaces).
- [Divisiones](#divisiones).
- [Listas](#listas).
- [Citas](#citas).
- [Tablas](#tablas).
- [Código](#código).
- [Comentarios](#comentarios).

---

## Párrafos

Un párrafo es una extensión de texto que finaliza cuando hay un salto de línea (enter) en el documento.

Este sería otro párrafo.

En Markdown podemos escribir con **negritas** para escribir en _cursiva_.

_**Este texto esta en cursiva y en negrita**_.

[☝🏻 Regresar](#markdown)

---

## Encabezados

# Encabezado de nivel 1

## Encabezado de nivel 2

### Encabezado de nivel 3

#### Encabezado de nivel 4

##### Encabezado de nivel 5

###### Encabezado de nivel 6

[☝🏻 Regresar](#markdown)

---

# Imágenes

![Dino DEV](./img/dino-dev.jpg)

![Flujo básico de Git](https://jonmircha.com/img/blog/git-flow.png)

[☝🏻 Regresar](#markdown)

---

## Enlaces

[YouTube](https://youtube.com/@jonmircha)

[Ir al encabezado 1](#encabezado-de-nivel-1)

[Ir al archivo comandos.txt](./comandos.txt)

[☝🏻 Regresar](#markdown)

[![Flujo básico de Git](https://jonmircha.com/img/blog/git-flow.png)](https://jonmircha.com/git)

[☝🏻 Regresar](#markdown)

---

## Divisiones

Esta es otra sección, la línea de arriba se llama **división**.

[☝🏻 Regresar](#markdown)

---

## Listas

### Listas Desordenadas

- Primavera
- Verano
- Otoño
- Invierno

### Listas Ordenadas

1. Primavera
1. Verano
1. Otoño
1. Invierno

### Listas Anidadas

- Primavera
  - Abril
  - Mayo
    - Batalla de Puebla
    - Día de las Madres
    - Día de Maestro
  - Junio
- Verano
  - Julio
  - Agosto
  - Septiembre
- Otoño
- Invierno

1. Primavera
1. Verano
1. Otoño
   1. Octubre
   1. Noviembre
      1. Día de Muertos
      1. Aniversario Revolución Mexicana
      1. Diciembre
1. Invierno
   1. Enero
   1. Febrero
   1. Marzo

[☝🏻 Regresar](#markdown)

---

## Citas

### Cita en línea

> Yo sólo sé, que no se nada

### Cita en bloque

> Todo lo que escuchamos es una opinión, no un hecho.
> Todo lo que vemos es una perspectiva, no la verdad.
>
> Marco Aurelio

[☝🏻 Regresar](#markdown)

---

## Tablas

| País    | Ciudad | Continente |
| ------- | ------ | ---------- |
| México  | CDMX   | América    |
| Japón   | Tokyo  | Asía       |
| Francia | París  | Europa     |

[☝🏻 Regresar](#markdown)

---

## Código

### Bloques de Código

```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }

  let c = a + b;
  return c;
}
```

```html
<html>
  <head></head>
  <body></body>
</html>
```

### Código _HTML_

<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q" required />
  <input type="submit" value="🔍" />
</form>

[☝🏻 Regresar](#markdown)

---

## Comentarios

<!-- Esto es un comentario -->

<!-- odfownfoiwenfoiwenfowenfowencowencoi -->

### Escape de caracteres

\_cursiva\_
\*\*negrita\*\*
\\

[☝🏻 Regresar](#markdown)

---