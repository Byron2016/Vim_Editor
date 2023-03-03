# Vim_Editor
VIM Editor Command Summary

# Tutor VI

## Movimiento del cursor


| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| :set number | Coloca números en las filas. |
| :set relativenumber | Coloca números relativos a la fila en que se encuentra. |    
|  | . |
|  | . |

## Movimiento del cursor


| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| k | La techa k parece una flecha que apunta hacia arriba. |
| h | La tecla h está a la izquierda y mueve a la izquierda. |    
| l | La tecla l está a la derecha y mueve a la derecha. |
| j | La tecla j parece una flecha que apunta hacia abajo. |

## Entrando y saliendo de VIM

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| :q | Salir si no se han realizado cambios. |
| :q! | Salir forzadamente y perder cualquier cambio. |    
| :wq | Guardar y salir. |


## Edición de texto - borrado

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| x | Borrar caracter bajo el cursor. |
| nx | Borrar n caractéres bajo el cursor y para derecha. |  


## Edición de texto - inserción

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| i | Cambia a **Modo Insert** a partir caracter en el que se encuentra. |
| I | Cambia a **Modo Insert** a partir primer caracter de la línea. |  
| a | Cambia a **Modo Insert** a partir caracter izquierda del que se encuentra. |  
| A | Cambia a **Modo Insert** a partir último caracter de la fila. |  
| o | Cambia a **Modo Insert** e inserta fila debajo. |  
| O | Cambia a **Modo Insert** e inserta fila encima. | 
| Esc | Salir del **Modo Insert**. |   


## Comandos para borrar
>**Nota:** Pulse **esc** para asegurarse que está en **Modo Normal**

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| dw | Borra desde inicio de palabra hasta el final **incluye espacio**. |
| ndw | Borrar n  palabras desde inicio de palabra actual. |  
| d$ | Borrar de la posición al final de la línea. | 
| nd$ | Borrar desde posición actual al final de la línea y n-1 líneas más. |  
| de | Borra desde inicio de palabra hasta el final **NO incluye espacio**. |  
| nde | Borrar n  palabras desde inicio de palabra actual. **NO incluye espacio**. | 
| dd | Borrar línea actual. | 
| ndd | Borrar n líneas desde la actual. | 

## Deshacer

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| u | Deshacer último comando hecho. |
| U | Devolver línea a su estado original. |  
| crtl + R | Desacer deshacer. | 

## Poner (pegar)

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| p | Pega lo último que ha borrado después posición actual del cursor. |
 
 
## Reemplazar 

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| r | Reemplazar caracter donde está el cursor. |
| R | Reemplazar a partir de donde está el cursor más de un caracter. |

## Cambiar 

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| cw | Cambiar parte de una palabra o toda ella. |
| cw | Borra desde posición en palabra hasta el final de la palabra. |
| ncw | Borrar n  palabras desde inicio de palabra actual. |  
| c$ | Borrar de la posición al final de la línea. | 
| nc$ | Borrar desde posición actual al final de la línea y n-1 líneas más. | 
| Esc | Salir del **Modo Insert**. | 


## Posición en fichero

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| crtl g | Mostrar línea actual en que se encuentra y total líneas. |
| Mayu G | Ir al final del fichero. | 

## Buscar (Search)
>**Nota:** Pulse **esc** para asegurarse que está en **Modo Normal**

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| /cccc | Buscar palabra cccc hacia adelante posición actual. |
| n | Repetir búsqueda hacia adelante. | 
| ?cccc | Buscar palabra cccc hacia atrás posición actual. | 
| :s/xxxx/yyyy | Sustitur primera aparición de xxxx por yyyy en la línea. | 
| :s/xxxx/yyyy/g | Sustitur toda aparición de xxxx por yyyy en la línea. | 
| :#,#s/xxxx/yyyy | Sustitur Toda aparición de xxxx por yyyy entre dos líneas. | 
| :%s/xxxx/yyyy/g | Sustitur Toda aparición de xxxx por yyyy. | 


## Ejecutar comando exterior
>**Nota:** Pulse **esc** para asegurarse que está en **Modo Normal**

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| :!comando | Ejecuta comando. |

## Guardar archivo / recuperar
>**Nota:** Pulse **esc** para asegurarse que está en **Modo Normal**

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| :w | Guardar cambios. |
| :w xxxx | Guardar cambios en xxxx. |
| :#,# w xxxx | Guardar entre las líneas en archivo xxxx. |
| :r xxxx | Incorpora el contenido del archivo xxxx en el actual a partir de la línea en la que se encuentre. |


## Fijar opciones
>**Nota:** Fijar una opción de forma que una búsqueda o sustitución ignore la caja. Se hace con un ejemplo  por pasos

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| /ignorar | Buscar ignorar. |
| n | Repetir búsqueda. |
| :set ic | Fijar la opción ic, ignorar la caja de la letra. |
| :set hls is| Fijar opciones hlsearch e insearch, esto resalta mientras escribimos lo que queremos buscar. |


## Ayuda

| COMANDO| DESCRIPCIÓN|
| ------ | ------ |
| :help | Ayuda. |
| :q | Salir de la ayuda. |
| :help w <intro> | Buscar ayuda sobre comando w. |
| :set hls is| Fijar opciones hlsearch e insearch, esto resalta mientras escribimos lo que queremos buscar. |
