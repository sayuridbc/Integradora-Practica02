# Integradora-Practica02
Practica de clase para comenzar a utilizar GithHub como herramienta para el desarrollo colaborativo, control de versiones y documentación del Proyecto Integrador de la asignatura 

### comados Basicos para el Maquetado 

###Encabezados (Headings)
Para poder dar enfasis a los contenidos de la documentacion podemos utilizar los encabezados (Headings),
para marcar alguna seccion o subseccion estos se marcan utilizando el simbolo # , entre menos repeticiones tenga mayor tamaño e  importancia tendra el texto. 

Ejemplo:

# Encabezado de Nivel 1
## Encabezado de nivel 2
### Encabezado para el nivel 3
#### Encabezado para el nivel 4 
##### Encabezado para el nivel 5 
###### Encabezado para el nivel 6 
####### Encabezado para el nivel 7 (solo se toma en cuenta los primeros 6 niveles) 

### 2. Separadores (SEPARATORS) -PRACTICA 03

##### Si se desea marcar una separacion más visual de contenidos de podremos utilizarlos indicando tres caracteres de "-" continuos, en el maquetado.


EJEMPLO
---
Esto es similar a un tag de HTML <HR> en HTML

### 3. Párrafos (PARAGRAGRPAHS)

##### Son utilizados para presentar grandes seccions de texto que descrben detalladamente las secciones de la documtacion del proyecto.

Ejemplo

La función del monitor es que puedas interactuar con el computador, con la ayuda del ratón y el teclado.
Hay varios tipos de monitores. Algunos son muy grandes, como una caja. Estos pueden tener tecnología de tubos de rayos catódicos (CRT, por sus siglas en inglés), que permiten visualizar imágenes mediante un haz de rayos catódicos. 
Existen otros que son bastante delgados y pueden usar una pantalla de cristal líquido (LCD), un diodo emisor de luz (LED) o pantallas de plasma.
Las pantallas muestran las imágenes a través de pixeles, que son las unidades básicas de una imagen. La resolución de los monitores depende de la cantidad de píxeles que estos tengan.  
Es decir, entre más pixeles tenga una pantalla, su calidad será mayor porque tendrá más resolución.
parrafo 1.

ESTE TEXTO PERTENECE AL PARRAFO 2

El término software es un vocablo inglés que fue tomado por otros idiomas y designa a todo componente intangible (y no físico) que forma parte de dispositivos como computadoras, teléfonos móviles o tabletas y que permite su funcionamiento.
El software está compuesto por un conjunto de aplicaciones y programas diseñados para cumplir diversas funciones dentro de un sistema. Además, está formado por la información del usuario y los datos procesados.
Los programas que forman parte del software le indican al hardware (parte física de un dispositivo), por medio de instrucciones.

<p align="right"> PARRAFO CON ALINEACION A LA DERECHA

Programas que dan al usuario la capacidad de relacionarse con el sistema, para ejercer control sobre el hardware. El software de sistema también se ofrece como soporte para otros programas. Por ejemplo: sistemas operativos o servidores
</p>

<p align="center"> PARRAFO CON CENTRADO 

Software de edición de imágenes. Por ejemplo: Adobe Photoshop, Paintshop, GIMP.
Software de procesador de texto. Por ejemplo: Microsoft Word, Word Pad, Block de notas.
Software de audio. Por ejemplo: Adobe Audition, Abelton, Pro Tools.
PARRAFO CON CENTRADO.
</p>


<p align="justify"> PRACTICA CON JUSTIFICADO
Todo dispositivo está formado tanto por la parte intangible, el software, como por la parte tangible, el hardware. El hardware es el conjunto de elementos materiales que forman parte de un dispositivo electrónico. Por ejemplo: en el caso de una computadora, el hardware está formado por el monitor, el teclado, el ratón, entre otros.
PRACTICA CON JUSTIFICADO
</p>

#### 4. TEXTO ENFATIZADO (BOLD,ITALIC,BOLD/ITALICT)
Si el texto que deseamos enfatizar se encuentra de un parrafo podemos utilizar algunos trucos para ubicarlos en la documentacion

##### TEXTO EN NEGRITA 
Para poder poner el texto en negrita esta debera ser encerrado entre dobles " "

Ejemplo

**Abre la pestaña Pull requests en tu repositorio.**
**Haz clic en New pull request.**
**En el cuadro Compare changes, selecciona la rama que has creado para compararla con la rama Main.**
**Asegúrate de revisar tus cambios antes de enviar y haz clic en Create pull request.**
**En la nueva página, escribe el título de tu solicitud y agrega una breve descripción de los cambios que ofreces.**
**Confirma el envío presionando Create pull request."**

#### TEXTO EN CURSIVA (ITALICT)
Se añade poniendo dos asteriscos donde se quiere reslatar la palabra 
Fusiona los cambios
Después de revisar y aprobar la *solicitud*, el paso final será incorporar los cambios a la rama principal. Sigue estos pasos para fusionar tus cambios con el proyecto:

*Si en algún momento quieres hacer más cambios en tu *proyecto*, siempre puedes crear una rama nueva y repetir el proceso*.

#### texto en negrita y cursiva (bold  y italict) 
se utiliza un triple asterizco
**GitHub** 
***Software*** ***El término software es un vocablo inglés que fue tomado por otros idiomas y designa a todo componente intangible (y no físico) que forma parte de dispositivos como computadoras, teléfonos móviles o tabletas y que permite su funcionamiento***. 

##### TEXTO SUBRAYADO (UNDERLINE)
**Ejemplo**

<ins>     El término software es un vocablo inglés que fue tomado por otros idiomas y designa a todo componente intangible (y no físico) que forma parte de dispositivos como computadoras, teléfonos móviles o tabletas y que permite su funcionamiento.</ins>

### 5.Cuadros para Código o reselas (BLOCKQUOTES)

Estos elementos son utilizados oara realizar instrucciones específicas para la instalación, 
configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un simbolo de mayor que (/>)

**ejemplo**
Para listar las carpetas y archivos en desde una terminal de sistema operativo Windows debemos ingresar el comando

> C:/dir
Despué oprimimos la tecla "Enter".

También podemos imgresar tectos multinllinea

**Ejemplo**
**Pasos para Instalar la Base de Datos:**

>-Descargar MySQL server del sitio oficial
>-Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y contraseña para el usuario
***root***
>-Descargamos el archivo del respaldo de la base de datos (.sql)
>-Restauramos la Base de Datos usando el comando "mysql >



>> C:/Program Files/MySQL/MySQL Server 8.8/bin/mysql -u root -p password < respaldo.sql

## 6.Listas ordensdas y listas desordenadas ##

**EJEMPLO:**



Para crear tu primer repositorio en GitHub deberás:

5. Contar con cuenta de GitHub.


1. Dar click en el boton: **Nuevo Repositorio**


2. Asignarle un Nombre a tu repositorio, por ejemplo: *practica03-38*

8. Asignarle un nivel de privacidad entre

-**Público:** Si quieres que esté disponible para todos los usuarios.

-**Privado:** Si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto.


5. Definir si incluye un archivo de descripción llamado README.md


50. Definir si habrá exclusiones de archivo a través del archivo: .gitignore

3. Guardar los cambios.

Si queremos usar un orden que comientce en número especifico debemos utilizar código HTML, usando los tags \<ol> y \<li>:

**Ejemplo**
<ol start="5">
 <li>quinto</li>
 <li>sexto</li>
 <li>Séptimo</li>
</ol>

#### 7.Ligas ( Hipervínculos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando los corchetes \[\], inmediatamente despues pondrémos la liga de referencia entre parentesis \( \)

**Ejemplo**
mi biscador favorito es: [Google](https://google.com).

Pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizar los simbolos \ < \>

**Ejemplo**

Documentación creada por ***Sayurid Bautista Cruz***
<230770@utxicotepec.edu.mx>

##### 8.Tablas (tables)

Si la documentación lo requiere podemos presentar información en formato de tablas con filas y columnas , para maquetarlas podemos utilizar el carácter \| para delifitar las columnas y \- oara delimitar las filas .

**ejemplo**
|Encabezado 1|Encabezado2|Encabezado 3|Encabezado 4|
|-----------|-----------|-----------|-----------|
|Fila 1 Celda 1|Fila 1 Celda 2|Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 1|Fila 2 Celda 2|Fila 2 Celda 3|Fila 2 Celda 4|
|Fila 3 Celda 1|Fila 3 Celda 2|Fila 3 Celda 3|Fila 3 Celda 4|

En caso de necesitar la fusión de celdas en columnas usaremos oa propiedad *colspan* del tag \<td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad *Rowspan*.

**Ejemplo**


## Imagenes 
![]()

![]()

**EJEMPLO:**

|Encabezado 1 |Encabezado 2 |Encabezado 3 |Encabezado 4|
|-------------|-------------|-------------|------------|
|Fila 1 Celda 1|Fila 1 Celda 2|Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 1|              |Fila 2 Celda 2|              |
|Fila 3 Celda 1|Fila 3 Celda 2|Fila 3 Celda 3|Fila 3 Celda 4|
|              |Fila 4 Celda 2|Fila 4 Celda 3|Fila 4 Celda 4|
|              |Fila 5 Celda 2|Fila 5 Celda 3|Fila 5 Celda 4|
|Fila 5 Celda 1|Fila 5 Celda 2|Fila 5 Celda 3|Fila 5 Celda 4|



<tr>
<td>Fila 2 celda 1</td>
<td colspan=3 align="center">Fila 2 Celda 2</td>
</tr>

<tr>
<td rowspan=3>|Fila 3 Celda 1| </td>
<td>|Fila 3 Celda 2|</td>
<td>|Fila 3 Celda 3|</td>
<td>|Fila 3 Celda 4|</td>
</tr>




