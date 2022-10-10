##### ASIX1_M4UF1_Apuntes_Markdown_SergiRafael
# Apuntes de GITHUB, Markdown y HTML

### Los pasos para empezar són los siguientes:

Para comenzar hemos tenido que seguir unos primeros pasos que en nuestro lugar han sido empezando por la instalación de GITHUB junto a la app GIT, seguidamente por la instalación de Visual Studio Code y finalmente la creación de nuestro perfil de GITHUB para crear repositorios alli.

### 1. GITHUB

>Esta página web nos permitirá crear y guardar los repositorios que vayamos haciendo. Tambien con el CMD (Simbolo del Sistema) de nuestro equipo podemos hacer una cópia local para trabajar desde tu qeuipo y no desde el navegador. Una vez acabado lo que tenemos que hacer es resubirlo otra vez en el GITHUB. Hay diferentes comandos para ejecutar en la CMD, pero algunos de los que utilizaremos son los siguientes: [Comandos CMD GITHUB](https://gist.github.com/dasdo/9ff71c5c0efa037441b6 "Lista de comandos")


### 2. GIT

>Para poder descargarlo hemos ido a la página web oficial de GIT, y a continuación hemos descargado la version x64 bits. 
[Pagina oficial de GIT](https://git-scm.com/ "Pagina de GIT")


### 3. Visual Studio Code

>Para descargarlo hemos accedido a la página web de Visual Studio code, y nos hemos descargado la versión de 64 bits.
[Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")


### 4. MARKDOWN

>Nuestro primer lenguaje de marcas que hemos visto y tocado en ASIX 1 es el lenguaje Markdown.

Lo que hemos de Markdown en clase ha sido:

1) encabezados

En Markdown hay 6 diferentes encabezados, que son de tamaño de mas grande a mas pequeño (directo, indirecto, noticias ...).
Para poner un encabezado lo que tenemos que hacer es poner un hashtag (#) al principio de cada linia. Segun cuantos hashtags pongas al inicio, el tamaño del encabezado será mas grande o mas pequeño.

Muestra de todos los tipos de encabezados:
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

2) negrita o cursiva:

Para poner una palabra o una frase en negrita, cursiva o las dos juntas. Para poner negrita lo que tenemos que hacer es poner dos barras bajas al principio y final de la frase o palabra, como por ejemplo en nuestro caso de ahora __SERGI__.
Por otra parte tambien tenemos la cursiva que en este caso se pone con un asterico al principio y al final de la frase o palabra, por ejemplo *SERGI*. 
Por ultimo tenemos la combinación de estas dos que estas dos que es poniendo primero las barras bajas y seguidamente el astérisco, por ejemplo __*SERGI*__.

3) imágenes:

Tambien podemos introducir poniendo un signo de exclamación al principio y seguidamente entre claudators ponemos el texto de la imagen y por ultimo ponemos los paréntesis y alli es donde tenemos que poner la URL de la imagen que queremos poner.

EJEMPLO:


![Markdown](https://th.bing.com/th/id/OIP.ZUAhLxV2uq0V5zIxUN3qtgE-DE?w=294&h=181&c=7&r=0&o=5&dpr=1.25&pid=1.7)

4) listas:

Tenemos dos tipos de listas la ordenada y la desordenada.
Para crear la lista ordenada lo que tenemos que poner es el numero delante, por ejemplo asi:
1. Sergi 
2. Sergi Rafael
3. Sergi Rafael Sanchez

Por otra parte la lista desordenada se hace poniendo el astérisco al principio de todo, por ejemplo asi:
* Sergi 
* Sergi Rafael
* Sergi Rafael Sanchez


5) tablas:

Por ultimo para crear una tabla tenemos que poner la barra recta | al principio y final del texto. La segunda linia de la tabla lo que debemos de poner es como queremos tener el texto alineado, hay tres tipos de alineado que son:
1. centrado: :----:
2. alineado a la derecha: ----:
3. alineado a la izquierda: :-----

Por ejemplo aqui veis los diferentes alineado de la tabla:

| Encabezado 1  | Encabezado 2 | Encabezado 3 |
| :-----------  | :----------: | -----------: |
| Producto 1        | Lápices      | 50 €           |
| Producto 2        | Gomas de borra      | 100 €          |
| Producto 3        | Boligrafos   | 150 €          |


6) hipervínculos:

Para crearlo solo tenemos que poner entre claudators el nombre que quieres que te salga para que sepan a donde se van a ir si clican ahi, entre parentesis pones la URL de la página web y por ultimo dentro del parentesis dejando un espacio pones unas comillas y ahi pones un mensaje que se vera cuando tengan el cursor encima del hipervínculo. 

Aqui puedes ver el ejemplo que he hecho:
[Pagina oficial de Markdown](https://markdown.es/ "Haz click y vas a la pagina oficial")


### HTML

Este es el segundo lenjuage de marcado que hemos visto en ASIX 1.

Nuestro primer paso siempre en HTML sera ejecutar el html5 que sera una base para empezar a trabajar.

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


A partir del <body> podremos editar nuestro archivo HTML.
Hay varias cosas que le podemos meter en nuestro archivo como ya puede ser:
1. Para introducir párrafos es: ´´´<p> texto </p>´´´
2. Para crear hipervínculos es: ´´´<a href="https://es.wikipedia.org/wiki/HTML" </a>´´´
3. Para crear listas ordenadas es: ´´´<ol> y seguidamente pones <li>´´´
4. Para crear listas desordenadas es: ´´´<ul> y seguidamente pones <li>´´´
5. Para meter imagenes es: ´´´<img src="https://ru.w3docs.com/uploads/media/book_gallery/0001/02/849d4286475e04155fd5f21861f16f53db95ac72.png"> alt="...">´´´
