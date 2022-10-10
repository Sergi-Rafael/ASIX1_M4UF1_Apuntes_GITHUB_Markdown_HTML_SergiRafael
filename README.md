##### ASIX1_M4UF1_Apuntes_Markdown_SergiRafael
# Apuntes de GITHUB, Markdown y HTML

### Los pasos para empezar són los siguientes:

Para comenzar hemos tenido que seguir unos primeros pasos que en nuestro lugar han sido empezando por la instalación de GITHUB junto a la app GIT, seguidamente por la instalación de Visual Studio Code y finalmente la creación de nuestro perfil de GITHUB para crear repositorios alli.

### 1. GITHUB

>GITHUB es un portal para gestionar las aplicaciones que utilizan el sistema Git. Además de permitirte mirar el código y descargarte las diferentes versiones de una aplicación, la plataforma también hace las veces de red social conectando desarrolladores con usuarios para que estos puedan colaborar mejorando la aplicación.

Esta página web nos permitirá crear y guardar los repositorios que vayamos haciendo. Tambien con el CMD (Simbolo del Sistema) de nuestro equipo podemos hacer una cópia local para trabajar desde tu qeuipo y no desde el navegador. Una vez acabado lo que tenemos que hacer es resubirlo otra vez en el GITHUB. Hay diferentes comandos para ejecutar en la CMD, pero algunos de los que utilizaremos son los siguientes: [Comandos CMD GITHUB](https://gist.github.com/dasdo/9ff71c5c0efa037441b6 "Lista de comandos")

Sobretodo, uno de los grandes problemas que hemos tenido al crear la cuenta ha sido al configurarlo con nuestro PC. Así que recomiendo que se preste mucha atención a los dos primeros puntos del enlace.

![capt 2 - apmd](https://user-images.githubusercontent.com/113420705/193621834-9c9c9615-4b03-42ac-b57d-84d30e6e71dd.png)

### 2. GIT

>GIT es un sistema de control de versiones de código abierto muy popular y eficiente. Rastrea contenido como archivos y directorios.

Para poder descargarlo hemos ido a la página web oficial de GIT, y a continuación hemos descargado la version x64 bits. 
[Pagina oficial de GIT](https://git-scm.com/ "Pagina de GIT")

![capt 1 - apmd](https://user-images.githubusercontent.com/113420705/193620980-203cf5a4-61b5-445f-8c5d-75ff68831667.png)

### 3. Visual Studio Code

>Visual Studio Code es un editor de código fuente desarrollado por Microsoft para Windows, Linux, macOS y Web. Incluye soporte para la depuración, control integrado de Git, resaltado de sintaxis, finalización inteligente de código, fragmentos y refactorización de código.

Para descargarlo hemos accedido a la página web de Visual Studio code, y nos hemos descargado la versión de 64 bits.
[Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")

![capt 3 - apmd](https://user-images.githubusercontent.com/113420705/193621791-a3392f9d-3b37-498b-8779-588fe4213c6b.png)


### 4. MARKDOWN

Nuestro primer lenguaje de marcas que hemos visto y tocado en ASIX 1 es el lenguaje Markdown.

>Markdown es un lenguaje de marcado con el que puedes agregar formato a documentos de texto plano. Tambien, siendo a día de hoy uno de los lenguajes de marcado más famosos. Su popularidad se debe a que es sencillo, ligero y fácil de aprender por parte de aquellas personas que no tienen un perfil técnico. 


Lo que hemos de Markdown en clase ha sido:

1) Los diferentes encabezados

En Markdown hay 6 diferentes encabezados, que son de tamaño de mas grande a mas pequeño (directo, indirecto, noticias ...).
Para poner un encabezado lo que tenemos que hacer es poner un hashtag (#) al principio de cada linia. Segun cuantos hashtags pongas al inicio, el tamaño del encabezado será mas grande o mas pequeño.

Muestra de todos los tipos de encabezados:
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

2) Cómo poner negrita o cursiva:

Para poner una palabra o una frase en negrita, cursiva o las dos juntas. Para poner negrita lo que tenemos que hacer es poner dos barras bajas al principio y final de la frase o palabra, como por ejemplo en nuestro caso de ahora __SERGI__.
Por otra parte tambien tenemos la cursiva que en este caso se pone con un asterico al principio y al final de la frase o palabra, por ejemplo *SERGI*. 
Por ultimo tenemos la combinación de estas dos que estas dos que es poniendo primero las barras bajas y seguidamente el astérisco, por ejemplo __*SERGI*__.


c) Cómo crear listas 

Otra característica del lenguaje Markdown es que podemos crear listas, tanto ordenadas como desordenadas. En primer lugar, para crear una lista ordenada tendremos que introducir un asterísco y un guión. Como por ejemplo:


d) Cómo introducir imágenes

A su vez, Markdown nos permite introducir imágenes. Para introducir una imágen debemos poner un signo de exclamación y escribir el texto alternativo de la imagen entre corchetes y el URL que dirige a la imagen entre paréntesis.

Como por ejemplo:
![google](https://user-images.githubusercontent.com/113420705/191205772-9891401d-f84d-4d89-bf7a-7c4130f8d378.png)

e) Cómo introducir hipervínculos

Para crear un hipervínculo sólo tenemos que poner entre corchetes el texto del enlace seguido de la URL entre paréntesis.

Por ejemplo: [Enlace a wikipedia](https://es.wikipedia.org "Haciendo click vas a la WIKIPEDIA")

f) Cómo crear tablas

Para finalizar, tambien nos permite crear tablas. Para crar una tabla tenemos que introducir "|" el texto y en la segunda línea el como queremos alinear el texto, podemos verlo
- ----------: --> centrado
- :----------- --> alineado a la izquierda 
- -----------: --> alineado a la derecha

La siguiente tabla nos servirá de ejemplo:

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| :----------- | :----------: | -----------: |
| Item1        | Bolígrafos   | 20           |
| Item2        | Lápices      | 50           |
| Item3        | Grapadoras   | 80           |

### HTML
HTML es el segundo lenguaje de marcas que hemos visto. HTML se define como un lenguaje de marcas estándard para crear páginas web y su código es:
Este será siempre el primer paso de nuestro trabajo.

```HTML
  
<!DOCTYPE html>
<html lang= "en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <title>Document</title>
</head>
<body>
  
</body>
</html>

```
El _HEAD_ es la cabecera de nuestro ficero HTML. Esta parte no se ve cuando la carga nuestro navegador y en ella esta la información como el título, que lo ubicaremos dentro del <title>, enlaces al CSS, si queremos aplicar estilo a nuestro código HTML, personalizar el favicon, cambiar el charset, para que nuestro código HTML entienda determinados carácteres, como acentos, podemos activar scripts, como por ejemplo, cuando agregamos el código .js personal que nos otorga *Font Awesome* para introducir diferentes *favicons*.

En el _BODY_ podemos editar el cuerpo de nuestro archivo. En el podemos:
  - Introducir párrafos a través del comando ``<p> texto </p>``
  - Crear hipervínculos de páginas web gracias al comando: ``<a href="https://google.es" Ejemplo de URL </a>``
  - Introducir imágenes gracias al comando: ``<img src="https://user-images.githubusercontent.com/113420705/193840496-f97e6ad7-8d93-470b-8967-9ea393c5f659.png"> alt="Ejemplo de IMG">``
  - Crear listas ordenadas, con el comando ``<ol>``, y poniendo ``<li>``en cada elemento. 
  - Crear listas desordenadas, con el comando ``<ul>``, y poniendo ``<li>`` en cada elemento.
  
  #### Ejemplo de código HTML aplicando todos los conceptos:
  [Ejemplo de código HTML](https://mega.nz/file/aRhyQYTT#nck7OZgis6_b1-4NV4IzjsvBsRW1qhQ58MWm52J55fk "Ejemplo de código HTML")



