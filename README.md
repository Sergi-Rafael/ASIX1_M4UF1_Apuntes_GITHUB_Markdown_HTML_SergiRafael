##### ASIX1_M4UF1_Apuntes_Markdown_SergiRafael
# Apuntes de GITHUB, Markdown y HTML

### Los pasos para empezar són los siguientes:

Para comenzar hemos tenido que seguir unos primeros pasos que en nuestro lugar han sido empezando por la instalación de GITHUB junto a la app GIT, seguidamente por la instalación de Visual Studio Code y finalmente la creación de nuestro perfil de GITHUB para crear repositorios alli.

### 1. GITHUB

>Esta página web nos permitirá crear y guardar los repositorios que vayamos haciendo. Tambien con el CMD (Simbolo del Sistema) de nuestro equipo podemos hacer una cópia local para trabajar desde tu qeuipo y no desde el navegador. Una vez acabado lo que tenemos que hacer es resubirlo otra vez en el GITHUB. Hay diferentes comandos para ejecutar en la CMD, pero algunos de los que utilizaremos son los siguientes:

- __COMO CREAR UN RESPOSITORIO EN GITHUB:__
    - Nos movemos a nuestros repositorios alli veremos que nos sale una opcion donde pone NEW, le damos.
        ![image](https://user-images.githubusercontent.com/113420713/196280893-8cffe295-6e38-4f44-967a-712a24b0dc68.png)
    - Ahora, le tendremos que poner el nombre que queramos que se llame el repositorio
        ![image](https://user-images.githubusercontent.com/113420713/196281252-2d8e7a15-7f9c-4b2c-94d3-b955db24e576.png)
    - Lo dejamos en publico.
    
        ![image](https://user-images.githubusercontent.com/113420713/196281609-4f2cbf03-0877-48db-86b1-3402c8137347.png)
    - Selecionamos la opcion "Add a README file".
    
        ![image](https://user-images.githubusercontent.com/113420713/196281683-fb2bc18e-77cc-4670-b878-7eee0202340c.png)
    - Bajamos a bajo y le damos a crear repositorio
    
        ![image](https://user-images.githubusercontent.com/113420713/196281756-bdbb4ddb-eba9-4fe0-9787-6f528f7381e6.png)


1. Los comandos en CMD para bajar el repositorio de la pagina web a local son:

    - vas a la carpeta donde quieras guardar los repositorios. En mi caso es de la siguiente forma.
       - cd/
       - dir
       - cd "repositorios GITHUB"
       - git clone "URL del GITHUB"
    - Para selecionar la URL tiene que ir a GITHUB, en la pagina principal repositorio que hayas creado. Encima de la lista de archivos, haga clic en Code (Codigo).

      ![image](https://user-images.githubusercontent.com/113420713/196273914-bba032a1-1e7f-4d76-9966-a99c8e7b80fe.png)
    - Una vez tenemos eso y estamos en Clone nos vamos al apartado de HTTPS, alli nos saldra una URL en la cual la tendremos que copiar.
      ![image](https://user-images.githubusercontent.com/113420713/196274367-6d3bf731-1dc3-4b31-abe8-01de724b1bfa.png)
    - Una vez hemos hecho eso nos tiene que salir las siguientes instruciones.
      ![image](https://user-images.githubusercontent.com/113420713/196275320-ccb9b659-f269-4116-bd93-1c5efd205248.png)
    - Finalmente queda listo para trabajar en local.
2. Configurar Nombre que salen en los __commits__ y configurar el __Email__:
    - El comando que hay que ejecutar para que los nombres que salen en los __commits__ es:
        - git config --global user.name "Sergi-Rafael"
    - El comando para configurar el Email es:
        - git config --global user.email "juan23@juan23.j23"
3. Para iniciar (subir) el repositorio es:
     - Iniciamos GIT en la carpeta donde esta el proyecto/respositorio
        - git init
     - Añadimos __todos__ los archivos para el commit
        - git add.
     - Hacemos el primer commit
        - git commit -m "Ponemos el texto que nos identifique con el commit"
     - Subimos el repositorio
        - git push origin main
4. En caso de que nos hayamos equivocado en el repositorio y lo queramos eliminar seria de la siguiente forma:
     - Vamos a la pagina web GITHUB
     - Nos dirigimos a donde esta nuestro repositorio
          ![image](https://user-images.githubusercontent.com/113420713/196279178-9470970d-45a1-417f-b242-1ec2a90ecf03.png)
     - Le damos clic encima del repositorio equivocado
     - Encima nos saldra una barra  con diferentes opciones, buscamos la de Settings (ajuestes)
          ![image](https://user-images.githubusercontent.com/113420713/196278833-dcdcd42c-a3d2-4f1f-9bc3-4b6398b3cac9.png)
     - Nos vamos a bajo del todo donde pone Danger zone (Zona Peligrosa)
     - Le damos a Delete this repository
          ![image](https://user-images.githubusercontent.com/113420713/196279717-0ad384b7-82c7-49c5-aaf0-c1ba9a88b0fd.png)
     - Por ultimo nos saldra una advertencia en la cual tendremos que copiar tu "nombre_de_usuario/nombre_de_repositorio" en el cuadro siguiente
          ![image](https://user-images.githubusercontent.com/113420713/196280085-58ceda70-9d81-4992-9ff1-b0c683bbc85a.png)
     - Finalmente ya no tendremos el repositorio
5. Estos son los 5 seguimientos tan sencillos para clonar, bajar, subir y eliminar de GITHUB.

### 2. GIT

>Para poder descargarlo hemos ido a la página web oficial de GIT, y a continuación hemos descargado la version x64 bits. 

[Pagina oficial de GIT](https://git-scm.com/ "Pagina de GIT")


### 3. Visual Studio Code

>Para descargarlo hemos accedido a la página web de Visual Studio code, y nos hemos descargado la versión de 64 bits.

[Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")

1. Para abrir una hoja de Visual Studio Code se hace de la siguiente forma:
    - Vamos a la parte superior izquierda y le damos archivo, le damos y nos saldra bastantes opciones. Buscamos la opcion de __Nuevo archivo__.
    
        ![image](https://user-images.githubusercontent.com/113420713/196282440-f43a7bf1-9068-45ff-acbc-b52398d2bc6c.png)
    - Le ponemos el nombre del archivo y en que formato lo queremos (*txt ; .html ; .php ; ...)
    
        ![image](https://user-images.githubusercontent.com/113420713/196282669-bfd03683-5d93-4855-8301-9897102fd6a1.png)
    - Por ultimo se nos abre la hoja y ya esta lista para escribir
    
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
1. Para introducir párrafos es: ```<p> texto </p>```
2. Para crear hipervínculos es: ```<a href="https://es.wikipedia.org/wiki/HTML" </a>```
3. Para crear listas ordenadas es: ```<ol> y seguidamente pones <li>```
4. Para crear listas desordenadas es: ```<ul> y seguidamente pones <li>```
5. Para meter imagenes es: ```<img src="https://ru.w3docs.com/uploads/media/book_gallery/0001/02/849d4286475e04155fd5f21861f16f53db95ac72.png"> alt="...">```
