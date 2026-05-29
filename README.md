# int1-Practica02-250850
---
En esta practica aprenderemos a utilizar las herramientas Git y GitHub para el contro de versiones de proyectos de desarrollo de software, aplicando princpios de buenas practicas de Documentación, Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador 

Elaborado por: **Carlos Eduardo Antonio Alvarez**

Materia: **Proyecto Integrador**

Docente: **M.T.I. Marco Antonio Ramírez Hernández**

Periodo: *Mayo - Agosto 2026*


---

## Comandos Básicos para Maquetadi de la Documentación utilizando el estandar de MarkDown (.md) 
---

Markadown es el estándar utilizado por Fit y GitHub, para estelizar (maquetar) la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo 

### 1.- Encabezqadps o Titulos (BHEADERS)

Para poder realizar una buena documentación del proyecto debemos dsitribuir correctamente los contenidos, para poder delimitar o hacer enfasis (enfatizar), es decir, resaltar las secciones más importantes, podemos utilizar los siguientes: 

***EJEMPLOS***

# Encabezado de Nivel 1 
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### Encabezado de Nivel 6
####### Encabezado de Nivel 7 - *El estandar solo permite 6 niveles para titulos, a partir del séptimo serán presentado como texto plano (sin estilo)*

### 2.- Separadores (SEPARATORS)

Si se desea marcar una separación visual de los contenido podemos utilizar una línea horizontal indicano tres carácteres - continuos, en el maquetado 

***EJEMPLO***

### Titulo de la sección 
---
Texto despues del separador 

### 3.- párrafos (PARAGRAPHS)

Son tulizados para presentar grandes secciones que describen detalladamente el contenido de las secciones de la documentación, detallan procesos, explican código o contexto teórico. 

***EJEMPLO***

Párrafo 1: Este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 

Párrafo 2 Este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2, el estándar de Markdown distingue los párrafos con un doble salto de línea de texto, si no se desea alinear, es decir, estará alinieado a la izquierda por defecto. 

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**, **centrado** o **justificado**, deberemos utilizar una etiqueta '''<p>''' con la propiedad align y la dirección deseada. 

<p align="left">Parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda parráfo alineado a la izquierda

<p align="center">Párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro párrafo alineado al centro

<p align="right">Párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha

<p align="justify">Párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado
### 4. Texto Enfatizado  (BOLD, ITALIC, BOLD/ITALIC)
 <p align="justify">Si el texto que deseamos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.</p>

##### Texto en Negrita (BOLD) 
Para poder poner el texto en negrita, este deberá ser encerrado entre dobles **

**EJEMPLO:**

Texto  Texto Texto Texto Texto Texto **Texto Importante**  Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto

##### Texto en Cursiva (ITALIC)
<p align="justify">Algunas veces es necesario resaltar algunas secciones o textos en cursiva para que el lector detecte el texto importante, dentro del maquetado con el estándar Markdown lo podemos realizar ubicando el texto entre  * (asteríscos).</p>

**EJEMPLO:**

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Negrita y Cursiva (BOLD & ITALIC)


De igual manera podemos unir ammbos estilos  **Negrita** y *Cursiva* para resaltar los textos que consideremos importantes dentro de la documentación de nuestros proyectos de software, utilizando un triple * (asterísco).

**EJEMPLO:**

Texto Texto Texto Texto Texto ***Texto en Negrita y Cursiva*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto


##### Subrayado (UNDERLINE)

Algunas veces necesitaremos subraya texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML  usando el tag \<ins> y cerrando con  \</ins>.

**EJEMPLO:**

Texto Texto Texto Texto Texto  Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto Cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto Subrayado</ins> Texto.


# Integradora-Practica03
Continuamos con los comandos básicos de Git y Github para el maquetado de la documentación 

### 5. Cuadros para Código o Reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones específicas para la instalación, configuración y/o inicialzación o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (\>)

**EJEMPLO:**
Para listar las carpetas y archivos en desde una terminal de sistema operativo Windows debemos ingresar el comando: 

> C:/dir

Después oprimimos la tecla  "Enter".

También podemos ingresar textos multilínea

**EJEMPLO:**

>Aquí se ingresan un conjunto de instrucciones
>para explicar al usuario, cómmo instalar el
>software que hemos diseñado.

Y si deseamos inclur viñetas para enlistar pasos podemos utilizar el caracter - dentro del texto a documentar.

**EJEMPLO:**
**Pasos para Instalar la Base de Datos:**
> - Descargar MySQL Server del Sitio Oficial
> - Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y contraseña para el usuario ***root***
> - Descargamos el archivo de respaldo de la base de datos (.sql)
> - Restauramos la Base de Datos usando el comando *mysql *
>> C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password \< respaldo.sql


### 6. Listas Ordenadas y  Listas Desordenadas

Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro podemos hacerlo utilizando  los número con un  punto  decimal si las deseamos ordenadas o un guión medio  -  si solo queremos una viñeta.

**EJEMPLO:**
Para crear tu primer repositorio en GitHub deberás: 
5. Contar con cuenta de GitHub.
1. Dar click en el boton: **Nuevo Repositorio*
2. Asignarle un Nombre a tu repositorio, por ejemplo:   *practica03-3b*
8. Asignarle un nivel de privacidad  entre
 - **Público:** Si quieres que esté disponible para todos los usuarios.
 - **Privado:** Si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado :  *README.md*
50. Definir si habrá exclusiones de archivo a través del archivo: *.gitignore*
3. Guardar los cambios.

Si queremos usar un orden que comientce en número específico debemos utilizar código HTML,
usando los tags  \<ol> y \<li>:

**EJEMPLO:**

<ol start="5">
 <li>Quinto</li>
 <li>Sexto</li>
 <li>Séptimo</li>
</ol>   


#### 7. Ligas (Hipervínculos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizanlo los corchetes \[ \], inmediatamente despues pondrémos la liga de referencia entre parentesis \( \)

**EJEMPLO:**
Mi buscador favorito es: [Google](https://www.google.com). 

Pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizas los simbolos \< \>

**EJEMPLO:**

Documentación creada por:  ***Carlo Eduardo Antonio Alvarez***  
<250850@utxicotepec.edu.mx>

<http://www.utxicotepec.edu.mx>

#### 8. Tablas (TABLES)

Si la documentación lo requiere podemos presentar información en formato de tablas con filas  y columnas, para maquetarlas podemos utiliziar el carácter  \| para delifitar las columnas y \- para delimitar las filas. 

**EJEMPLO:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4|
|------------|-------------|------------|-------------|
| Fila 1 Celda 1 | Fila 1 Celda 2| Fila 1 Celda 3 | Fila 1 Celda 4 |
| Fila 2 Celda 1 | Fila 2 Celda 2| Fila 2 Celda 3 | Fila 2 Celda 4 |
| Fila 3 Celda 1 | Fila 3 Celda 2| Fila 3 Celda 3 | Fila 3 Celda 4 |


En caso de necesitar la fusión de celdas en columnas usaremos la propiedad *colspan* del tag \<td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad *rowspan* .


**EJEMPLO:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4|
|------------|-------------|------------|-------------|
| Fila 1 Celda 1 | Fila 1 Celda 2| Fila 1 Celda 3 | Fila 1 Celda 4 |
| Fila 2 Celda 1 <td colspan=2> Fila 2 Celda 2| Fila 2 Celda 3 |
| Fila 3 Celda 1 | Fila 3 Celda 2| Fila 3 Celda 3 | Fila 3 Celda 4 |
|                | Fila 4 Celda 2| Fila 4 Celda 3 | Fila 4 Celda 4 |
|                | Fila 5 Celda 2| Fila 5 Celda 3 | Fila 5 Celda 4 |
| Fila 6 Celda 1 | Fila 6 Celda 2| Fila 6 Celda 3 | Fila 6 Celda 4 |

Dado que en el ejemplo pasado usando solo markdown no se puede realizar la fusión de filas debemos utilizar el estandar de HTML, usando los tags: \<th> para los encabezados, \<tr> para las filas y <td> para las celdas, y en  ellos utilizar la propiedad de  *colspan* y *rowspan*

**EJEMPLO:**

<table>
 <tr>
  <th>Encabezado 1</th>
 <th>Encabezado 2</th>
 <th>Encabezado 3</th>
 <th>Encabezado 4</th>
</tr>
 <tr>
   <td>Fila 1 Celda 1</td>
  <td>Fila 1 Celda 2</td>
  <td>Fila 1 Celda 3</td>
  <td>Fila 1 Celda 4</td>
 </tr>
 
 <tr>
   <td>Fila 2 Celda 1</td>
  <td colspan=3 align="center">Fila 2 Celda 2</td>
 </tr>

 <tr>
  <td rowspan=3> Fila 3 Celda 1</td>
  <td> Fila 3 Celda 2</td>
  <td> Fila 3 Celda 3</td>
  <td> Fila 3 Celda 4</td>
 </tr>

<tr>
  <td>Fila 4 Celda 2</td>
 <td>Fila 4 Celda 3</td>
 <td>Fila 4 Celda 4</td>
</tr>
 
<tr>
  <td>Fila 5 Celda 2</td>
 <td>Fila 5 Celda 3</td>
 <td>Fila 5 Celda 4</td>
</tr>

<tr>
 <td>Fila 6 Celda 1</td> 
 <td>Fila 6 Celda 2</td>
 <td>Fila 6 Celda 3</td>
 <td>Fila 6 Celda 4</td>
</tr>

</table>


###imagenes

Si la documentación requiere de incorporar imágenes, equemas , modelos, fotografías, o cualquier representación gráfica, utilizaremos la estuctura de la ligas, maquetanto el nombore de la imagen entre corchetes con  un signo de admiración de cierre y la liga de referencia a la imagen usando parentesis. 