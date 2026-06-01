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

#### 4- Enfatizado de Texto 

- Texto en negritas: Para resaltar el texto importante que no sea un titulo por que esto inicialmente están en negrita, deberemos encerrar el texto deseado entre dobles asteriscos (**)

Ejemplo:  ste texto esta en **negrita**

- Texto en Cursiva (Itálico): Para hacer refernecia a texto utilizado el formato inclinado o itálico bastará con encerrar el texto entre dos asteriscos simples (*)

Ejemplo:  Este *texto* estará *inclinado*

- Texto en Cursiva y negrita: Para lograr esta estilización en la documentación basta con juntar todas las configuraciones, es decir, encerramos eñ texto en un triple asterisco (***)

Ejemplo:  ***Este texto esta en Negrita e itálico***  

- Texto Tachado: En algunas ocacsiones es necesario dar formato al texto con un efecto de como es incorrecto, generalmete esta idea se transmite por que el texto esta tachado, es decir, con una línea que lo marac por la mitad.Para lgrar este efecto, tenemos que encerrar el texto entre una doble tilde (~). 

Ejemplo: Se dice haya no ~~haiga~~

- Texto subrayado: En este tipo de formato el texto queda sobre una línea inferior para denotar su revelancia, este formato n tiene un versión rapida en el westandár MARKDOWN, pero dado su similaridad a HTML podemos utlizar las etiquetas ``` <u> ``` y ```</u>```. 

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto en Super Índice: En algunas ocasiones se reauiere dar formto a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag de HTML ``` <up>``` y ```</sup>``` para delimitar el formato. 

Ejemplo:  Para elevar x al cuadrao tendriamos lo siguiente x<sup>2</sup>.

- Texto en Subíndice: En el caso de la Química se utilizan subíndices para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ```<sub>``` y ```</sub>```

Ejemplo: La formula del Agua es H<sub>2</sub>O


### 5.- Listas 

Cuando realizamos documentación utilizando el estandár de MARKDOWN, es compún que tengamos que enlistar elemetos, requisitos de hardware, requisitos de software o enmuerar pasos del como el software debe es estar instalado paso a paso. por eso debemos de crear listas de las cuales hay 3 tipos: **Ordenadas (Números)***, **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**. 

1.- Listas ordenadas 

Estas deberán estar enumeradas con un numero seguido por un punto y un espacio en blanco para comenzar el listado 

1. PC 
2. Wifi
3. Modém 
4. Smartphone
6. Smart TV 
5. Tablet

2.- Listas Desordenas 

Estas listas no llevan un número, si njo una viñeta (Simbolo) y suele listar elementos que no requieren un orden específico 

- pan 
- Leche 
- Huevos 
- Azucar 

3.- Lista mixta 
Son aquellas que mezcla ambos elementos 

- 3° A DSM 
  1. Juan 
  2. Pedro 
  3. Alejandra 
- 3° B DSM 
  1. Romina 
  2. Daniel 
- 3° C DSM 
  1. Yair 
  2. Liseth
  3. Jeovanny
  4. Erick  

 ### 6.- Bloque de Código (CODE) o Citas (BLOCK QUOTES)

Estos estilos de texto se utiiozan para llamar la atención del lector, en pasos que son importantes, realizar alguna reseña o segmentar líneas de codígo que se deberán ingresar en una terminal de comnados o líneas de ejecución. 

- Cuadrp de Citas (Block Quotes)

Son cajas estilizadas en colores grises por defecto con un margen más claro 

Ejemplo: 

Para luistar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windows debemos usar el comando: 

>C:/dir 

DEspues oprimios la tecla *Enter* 

Tambien podemos usar texto miltilinea 

EJEMPLO:

Pasos para instalar MySQL 

> - Descargar el archivo instalador desde la página oficial www.mysql.com
> - instalar el Servidor de Base de Datos 
> - Definir el puertoy contraseña para el usuario **root**
> - Inicializar el servidor de base de datos 
> - Conectarnos a la base de datos para verificar que se instaló correctamente 

- Bloques de Código 

Es común que en la documentación del proyecto de software damos al usuario un par de instrucciones de como instalar, configurar, desplegar y testear (pruebas), nuestro producto como desarrollador. Por tal motivo el estandar de markdown nos permite enfatizar estas instrucciones, simulando estar en una terminal de sistema operativo ,para delmimitgar este codigpo basta con encerrarlos con triples caracteres de bacltic (acento o tilde inversa ``` ` ```)

Ejemplo: 
Para clonr el proyecto ingresa la siguiente instruccion 
```
https://github.com/charles-antt/int1-Practica02-250850.git
``` 


A diferencia de los bloques de citas, la tipografía y el siginificado asociado cambian 

### 7.- Tablas 

en caso de que necesitemos estructurra datos o información relevante para ñla documentación podemos utilizar el formtado de tablas, para lo que tenemos que considerar la estructura base de una tabla: 

- Usar | para delimitar las columnas 
- Usa --- para sepaarar las filas del encabezado 

Ejemplo:
|titulo 1 | Titulo 2 | Titulo 3 | Titulo 4 |
|---|---|---|---|
| Fila 1, Columna 1| Fila 1, Columna 2 | Fila 1, Columna 3 | Fila 1, Columna 4|
| Fila 2, Columna 1| Fila 2, Columna 2 | Fila 2, Columna 3 | Fila 1, Columna 4|
| Fila 3, Columna 1| Fila 3, Columna 2 | Fila 3, Columna 3 | Fila 1, Columna 4|
| Fila 3, Columna 1| Fila 4, Columna 2 | Fila 4, Columna 3 | Fila 1, Columna 4|

### 8.- Hipervinculos (Links)

Para poder hacer referencia a documentos internos o externos dentro del repositorio, debemos respetar la siguiente estructura 

``` 
[Texto que el usuario leera](url a donde te dirigira) "texto que aparecera cuando el cursor este sobre la liga"
```

Ejemplo: 

- Ligas externas 
[Google ](http://google.com)

-Ligas internas 
[Acera de Autor](./aboutme.md "Cónoceme más")

### 9.- Imagenes 

El estandar de markdown nos permite incrustar imagenes dentro de nuestra documentacion lo que nos permitira poner logotipos, capturas de pantalla o cualquier archivo fráfico importante. 

La estrucutura varia un poco de las rederencias de hipervinculos, siento:

``` 
![Texto que el usuario leera](url donde se encuentra la imagen ) 
```

Ejemplo:
![Si tu te vas - Charles Ans](./imagenes/image.png)

Es importante enteder que la resolución de la imagen será la original del archivo 

***Tip PRO***

Si el tamaño dle imagen no se justa a lo que deseas para tu documento, lo más recomnendable es ajustar el tamaño del archivo original con algun siftware procesador de imagenes como: PaInt, Illustrator, Int o Photodhop, pero si qyuiere modificarlos desde el codigo, el estandar no tiene parametros definidos por lo que necesitaremos hechar lines de codigo html 

Cambiando la estructura con por la etiqueta ``` <img> ``` 

Ejemplo: 

<img src="./imagenes/image.png" width="350" height="350" >

### 10.- Notal del pie 

### [Footnotes](https://github.com/markdown-it-/markdown-it-footnote)

Si muestra documentación requiere ubicar notas de importancia o relevancia posterior, podemos usar notas al pie de manera dinamica 

Notas al pie 1[^first]

Nota al pie 2[^Second]

Referencua al pie dentro de un parrafo  ^[Nota interna] extenso dentro de nuestra documentación 

Segunda referencia la nota 2 [^Second]

[^first]: Njota al pie **Puede ser formateada**

 y tener múltiples líneas de párrafo 
 [^Second]: Texto de la segunda nota al pie
