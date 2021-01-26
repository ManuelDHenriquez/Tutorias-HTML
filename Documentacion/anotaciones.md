# Anotaciones
* Comandos **git**
    * git init (inicializar el git)
    * git log (cargar los commit)
    * git status (cargar el estado del git)
    * git add (añadir archivos)
    * git add+path (agregar al repositorio los archivos indicados)
    * git add -A (agregar al repositorio todos los archivos y carpetas que esten el proyecto, los que git no esté siguiendo)
    * git commit [mensaje] + archivos (hace commit o save de todos los que indiquemos, para guardar las modificaciones)
    * git commit -am [mensaje] (hace commit a los archivos modificados y que git esté siguiendo)
    * git checkout -b nombreDeBranch (para crear un nuevo branch <rama> y cambiar automaticamente a esta)
    * git branch (lista de ramas existentes en el proyecto)
    * git checkout nombreDeBranch (para moverse entre las ramas del proyecto)
    * git merge nombreDeBranch (hace un merge <fusión> entre dos ramas, entre la rama que selecionemos y la que estamos ubicados)
    * git clone URL/name.git NombreProyecto (clonar un proyecto de git a la carpeta "NombreProyecto")
    * git push origin nombreDeBranch (luego de hacer git commit, este comando sube el proyecto al repositorio remoto, especificamente la rama que indiquemos)
    * git pull nombreDeBranch (hace una actualización de la rama local desde el repositorio remoto  que indicamos en el comando)

# (investigar el .md)
## Algunos comandos del **MarkDown
* Encabezados 
    * # primer nivel
    * ## segundo nivel
    * ### tercer nivel
    * #### cuarto nivel
    * El primer y segundo nivel de encabezado también se pueden escribir como sigue:
    * Primer nivel de encabezado  
    ==========================
    * Segundo nivel de encabeado  
    --------------------------

* Parrafos y saltos de linea
    * parrafos se separan con un espacio
    * saltos de linea con dos espacios

*Añadir Enfasis 
    * se puede poner en curiva encerrandolo entre los simbolos o -
    * se puede poner en negrita encerrando la palabra entre ** o __

* Listas
    * al poner sangria al (*) permite crear listas anidadas

Ejemplo de listas:  

Lista de compras
---------------
* Frutas
  * Manzanas
  * Naranjas
  * Uvas
* Lácteos
  * Leche
  * Queso

  * Listas ordenadas
    * se escriben ordenando cada linea 

lista ordenada:  

Lista de pendientes
------------------
1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo

color (es para dar color a las letras)

clase se representa por punto (.)
id se representa por numeral (#)

para poner imagenes en css se usa la etiqueta body{}
dentro de ella se coloca lo consecuente de el cuerpo de la pagina 

width para ancho
height para alto
background-color para color de fondo
border-radius para añadir bordes

bootstrap para ahorrar tiempo en código

material-ui.com para otros tipos de css

aprender a hacer todo lo de bootstrap y parecidos

Tipos de selectores en CSS
--------------------------
1. Universal (*), selecciona todos los elementos
2. De tipo (por nombre de elmentos {h1...h6, button, p, etc})
3. Clases (class="nombre-clase")
4. ID (id="nombre-id")
6. Por atributo (nombre-atributo="nombre"), se colocadentro de corchete [nombre-atributo="nombre"]
7. Descendiente (por contenedos, desde el de mayor valor, hasta el menor). h1 p{modificaciones}
8. pseudo-clases (elemento:hover(para cambios del mouse sobre el elemento))