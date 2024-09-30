# Aprende html

## Buenas practicas
### Tratamiento de imagenes
Hacer que pesen menos para que no carguen tan lento
Formatos
Eliminar los metadatos

## Etiquetas <"algo">
Esto indica que es una etiqueta, las etiquetas se cierran repitiendolo al final </"algo", pero algunas se autocierran
Estas sirven para separar los diferentes elementos de nuestra pagina
Hay etiquetas padres e hijos
Hay etiquetas contenedoras, que crean contenedores, no tienen restriccion más allá del significado que le demos, pero por buena practica si quiero 
hacer el header mejor usar la etiqueta \<header\>, el creador de contenedores comodin es el \<div\>
### \<!doctype html\>
Esto es para indicar que lo que sigue es un documento html, esta etiqueta se autocierra

### \<html\>  \</html\>
Aqui va todo el contenido del proyecto

**¿que pasa si pongo algo fuera de esto?**

### \<head\> \</head\>
Aqui va todo lo que le indica al navegador sobre como cargar cosas de nuestra pagina

### \<body\>  \</body\>
Aquí va todo el contenido visible de la pagina

### \<meta\>
Aporta metainformacion del archivo
Se le tiene que añadir atributos y se auto cierra

### \<a\> \</a\>
Sirve para poner links
Ver href y target

### \<figure\> \</figure\>
Contenedor para imagenes?

### \<img/\>
Para imagenes
Atributos:
    *src 
    *alt

### \<video\> \</video\>
Para videos
Atributos:
    *src
    *controls
    *preload

### \<source/\>
Permite que el navegador tenga varias fuentes y formatos para los videos (fotos?)
Cuando se usa hay que quitar el *src* y ponerlo dentro de esta etiqueta
Atributos:
    *src

###  \<figcapture\>  \</figcapture\>
Pone descripcion de la imagen pero a diferencia de *alt* lo muestra en el pie de la imagen sin que la imagen este rota
Se usa dentro de  \<figure\>

## Atributos
Las etiquetas pueden tener atributos y que van dentro de ellas 
> Ejemplo \<html lang="es"\> \</html\>
Los atributos pueden tener valores como en el ejemplo "es"
o solo ser el atributo como "controls"

### lang="idioma"
Esto es un atributo que generalmente se pone dentro de la

### href 
Atributo para señalar el link al que se direcciona \<a\>

### target
Sirve para indicar como abrir un link 
Por defecto cambia nuestra pestaña actual al link
_blank sirve para abrirla en una pestaña nueva
etc

### src
sirve para indicar el origen de una imagen o video
en video, si añadimos "#t=numero,numero" podemos decidir desde donde comienza y acaba el video

### alt
La descripcion que pongamos aparece cuando la imagen esta rota y para temas de accesibilidad(tmb ayuda en el seo)

### controls
En videos, permite que hayan los controles play y otros