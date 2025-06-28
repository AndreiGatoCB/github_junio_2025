Ejercicio para la publicación de información dentro de GitHub utilizando Markdown.
# Tabla de contenidos

- [Tituos / Encabezados](#encabezados)
- [Tipo de textos](#tipografías)
- [Listas](#listas)
- [Enlaces](#enlaces)
- [Imágenes](#imágenes)
- [Resaltado de Código y Sintaxis](#resaltado-de-código-y-sintaxis)
- [Notas al pie](#notas-al-pie)
- [Tablas](#tablas)
- [Citas en bloques](#citas-en-bloque)
- [Líneas](#línea-horizontal)
- [Saltos de línea](#saltos-de-línea)
- [Colaboradores](#colaboradores)

## Encabezados
Aquí hago una pequeña muestra de los tipos de encabezados. Útil para diferenciar textos o llamadas.
# _Título_ Título H1
## Título H2
### Título H3
#### Título H4
##### Título H5
###### Título H6
```
El principal es **H1** para resaltar puntos más importantes, a partir de eso el tamaño de cada uno de los títulos
disminuye en tamaño.
```
- [Volver al inicio](#tabla-de-contenidos)
## Tipografías
Aquí se detalla diferentes formas para resaltar textos.

#### Énfasis o cursiva
Para este método se utiliza la palabra entre dos asterístcos "* *" o entre dos guiones bajos "_ _". *asteríscos* o _guiones bajos_.
#### Negrita
Para este método se utiliza la palabra entre cuatro asteríscos "** **" o entre cuatro guiones bajos "__ __" **asteriscos** o __guiones bajos__
#### Tachado
Para el tachado se utiliza cuatro tildes o virgulillas "~~ ~~" ~~tilde~~
```
También se pueden utilizar los diferentes métodos mezclados.
```
**LOS _METODOS_ ~~MEZCLADOS~~**
- [Volver al inicio](#tabla-de-contenidos)
## Listas

Esto se utiliza para enumerar o enlistar ítems dentro del texto.

Lista ordenada:

1. Ítem uno
2. Ítem dos
3. Ítem 3

Dentro de la lista ordenada puedes también tener listas sin ordenar

1. Ítem uno
2. Ítem dos
   * Ítem sin orden
   * Otro ítem sin orden
   * Otro más
3. Ítem tres
- [Volver al inicio](#tabla-de-contenidos)
## Enlaces

Se utiliza para realizar la conexión con sitios. Para indicar que es un hipervínculo, se debe poner entre corchetes una palabra clave o un texto [Palabra Clave] [Esto es un hipervínculo], esto le indica al sistema que estamos por realizar un salto a otra parte o sitio, seguido de los corchetes, sin espacios, entre paréntesis se coloca la URL o la palabra a la cual se hace mención. Es el mismo sistema que se utilizó en el principio en la Tabla de contenidos de arriba.
- [Hipervínculo con Instagram](https://www.instagram.com/)
- [Hipervínculo con Google](https://www.google.com/)
- [Hipervínculo con Facebook](https://www.facebook.com/)
```
Nota: Al hacer clic en los Hipervínculos la página se abre en la misma solapa, bajo una advertencia que estamos
abandonando el sitio GitHub, por lo que para abrir los otros sitios en otra página lo recomendable es
hacer Ctrl+clic sobre el Hipervínculo para abrirlo en una nueva pestaña.
```
- [Volver al inicio](#tabla-de-contenidos)
## Imágenes

La función es igual que en los enlaces, la única diferencia es que en Marcdown con el signo de exlamación "!" se le indica que lo que sigue es un enlace a una **imagen** no a un sitio.

Este sería el formato: **"![Texto alternativo] (URL-de-la-imagen)"**

![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```
Si queremos agregarle un texto para que sea visible al pasar el cursor por encima de la imagen debemos hacerlo
del siguiente modo, agregando luego de la URL de la imagen entre **Comillas** " " el texto deseado.
```
![Logo de GitHub](https://github.com/marzelo1970/prueba-repo/blob/main/icons8-github-480.png "Acá estoy agregando el TEXTO para el mouse")
- [Volver al inicio](#tabla-de-contenidos)
## Resaltado de Código y Sintaxis

Se utilizan tres "`" consecutivos y se indica que tipo de lenguaje es el que sigue, **_Python_** o ***Javascript***

```javascript
var s = "Ejemplo de sintaxis en JavaScript";
alert(s);
```
```python
s = "Ejemplo de sintaxis en Python"
print(s)
```
```
Texto sin un lenguaje determinado
Añadiremos una etiqueta <b>Etiqueta</b>
```
- [Volver al inicio](#tabla-de-contenidos)
## Notas al pie

Se utiliza para hacer referencias. Las referencias pueden estar en varias líneas, pero cada vez que se inicia una nueva línea, el texto debe estar precedido de dos espacios. Los enlaces a notas pueden estar enumerados como los dos primeros casos, o pueden tener palabras claves como Nota, Ejemplo, etc.

- Este es un ejemplo de referencia [^1][¹]
- Este es otro ejemplo de referencia [^2][²]
- Este es un ejemplo de nota [^note]

[¹] Referencia 1
[²] Referencia 2
[^note] Nota.
- [Volver al inicio](#tabla-de-contenidos)
## Tablas
Se pueden utilizar para marcar la evolución de proyectos.
```
| Descripción proyecto | Fecha inicio | Fecha finalización |
|----------------------|:-----------------:|:-----------------:|
| Trabajo 1            | 12 de mayo 2025 | 15 de mayo 2025 |
| Trabajo 2            | 13 de mayo 2025 | En desrrollo |
```
| Proyecto    |	Inicio                | Finalizado | Operador |
|-------------|:---------------------:|:----------:|:--------:|
|Trabajo 1   	| 15 de mayo de 2025   	| Si         |Juan      |
|Trabajo 2  	| 20 de mayo de 2025    | Si         |Carlos    |
|Trabajo 3    | 03 de junio de 2025   | No         | Carlos y Juan |
- [Volver al inicio](#tabla-de-contenidos)
## Citas en Bloques
La "Cita en bloque" (o Blockquote) en Markdown es una forma de resaltar un texto como si estuvieras citando a alguien o haciendo referencia a una idea o fuente externa. Se utiliza con el símbolo mayor que (>) al comienzo de la línea.

> Estoy haciendo una referencia a un texto externo.

> La cita puede estar detallada en varios renglones.
> No es necesario que realices tarea alguna para que la cita aparezca en la misma llamada.

- [Volver al inicio](#tabla-de-contenidos)
## Línea Horizontal

Sirve para dividir ideas o partes del texto. Se alternando guiones o asterizcos y espacios.
```
- - - -
* * * *
```
- - - - 
* * * *
- [Volver al inicio](#tabla-de-contenidos)
## Saltos de Línea

Los saltos de líneas se hacen presionando dos veces la tecla "< Enter >"

Se puede utilizar para separar dos párrafos.
- [Volver al inicio](#tabla-de-contenidos)
## Colaboradores
Marzelo1970
- [Volver al inicio](#tabla-de-contenidos)
