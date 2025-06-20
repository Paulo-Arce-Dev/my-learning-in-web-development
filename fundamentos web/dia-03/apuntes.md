# Sintaxis CSS

La sintaxis de CSS se basa en reglas formadas por un selector y un bloque de declaraciones. El selector indica qué elementos HTML serán afectados, y dentro del bloque (entre llaves {}), se colocan las declaraciones en pares de propiedad y valor, separados por dos puntos y terminados con punto y coma. Por ejemplo: p { color: red; font-size: 16px; } cambia el color y tamaño del texto en todos los párrafos.

## Selectores básicos

Los selectores básicos permiten apuntar a elementos HTML específicos. Los más comunes son: el selector de tipo (p, div, h1) que selecciona todas las etiquetas de ese tipo; el selector de clase (.clase) que apunta a elementos con esa clase; y el selector de ID (#id) que apunta a un único elemento con ese ID. También existe el selector universal (\*) que selecciona todos los elementos del documento.

## Colores en CSS

CSS permite aplicar colores usando nombres predefinidos (red, blue), códigos hexadecimales (#ff0000), valores RGB (rgb(255, 0, 0)), RGBA (igual que RGB pero con transparencia) y HSL (hsl(0, 100%, 50%)). Se pueden aplicar colores al texto (color), al fondo (background-color) y a bordes, entre otros.

## Texto

CSS ofrece muchas propiedades para estilizar texto, como color para el color del texto, font-size para el tamaño, font-family para elegir la fuente, font-weight para el grosor (como bold), y text-align para la alineación (izquierda, centro, derecha). También hay propiedades como line-height para el espaciado entre líneas y text-transform para cambiar mayúsculas/minúsculas.

## Márgenes

Los márgenes (margin) crean espacio alrededor de un elemento, separándolo de otros. Se pueden definir en todos los lados a la vez (margin: 20px;) o individualmente (margin-top, margin-right, etc.). CSS también permite usar valores como auto para centrar elementos horizontalmente dentro de un contenedor.

## Padding

El padding (padding) es el espacio interno entre el contenido de un elemento y su borde. Al igual que los márgenes, se puede aplicar a todos los lados con una sola propiedad o controlar individualmente (padding-top, padding-left, etc.). Aumentar el padding hace que el área clickeable o visual del elemento se expanda hacia adentro.
