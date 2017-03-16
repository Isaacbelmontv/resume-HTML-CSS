**HTML & CSS**

TAGS DE HTML


| TAG            | Para que sirve?|
| :------------- | :------------- |
| ```<title></title>```| Texto que va en ventana|
|```<ol> <li> </li> </ol>```  | Crear lista con numeros      |
| ```<lu> <li></li> </lu> ```       | Crear lista con vinetas       |
| ```<h1> </h1>```       | Titulo 1       |
| ```<p></p>```       | Agregar Parrafos       |
| ```<a href="pagina web">Texto</a>``` | Links  |
| ```<a href="pagina web" target="_blank">Texto</a>``` | Links que abre en una nueva ventana |
| ```<img src="direccion.jpg"/>```       | Imagen       |
| ```<img src="direccion.jpg" alt="descripcion"/>```       | Imagen con descripcion |
| ```<a href="url" target="_blank"><img src="direccion de la imagen" alt="descripcion de la imagen" >```       | Agregar Link en la imagen       |
| ```</br>```       | Salto de linea      |
| ```<!-- comentario -->```       | Comentarios en HTML    |



**CSS**

Se usa para mejorar la apariencia de nuestras pantallas en html.</br>
Todo va dentro de un archivo .css</br>
Al acabar un codigo procurar dejar un espacio entre cada parentesis.

| codigo         | Funcion     |
| :------------- | :------------- |
| ```<link rel="Stylesheet" href="styles.css">   ```      | Esto va dentor del Head de nuestro HTML para poder editar el archivo css       |
| ``` <style>       </style>```       | Todo codigo CSS va dentro       |
| ``` <style>    h2 {  }   </style>```       | Aqui se hace referencia lo que afectara dentro del codigo html       |
| ```font-family: Arial;   ```      | Cambiar tipo de letra       |
| ```font-family: Arial;   ```      | Cambiar tipo de letra       |
| ``` h1, p { color: DarkSlateGray; }   ```      | Cambiar colores a mas de una parte del texto       |
| ``` /* coment */      ```      | Agregar comentarios en CSS      |
| ``` background-color: color o codigo   ```      | Cambiar color de fondo      |
| ``` color: rgb(123, 40, 230);  ```      | Agregando colores RGB      |
| ``` color: hsl(182, %20, %50);  ```      | Saturacion de colores usando porcentaje      |
| ``` color: rgba(182, 20, 50 0.5);  ```      | Opacidad      |
| ``` color: hsla(239, 45%, 22% 0.4);  ```      | colores hsla      |
| ``` font-family: Garamond, Times, serif ```      | usando el comando serif     |
| ``` font-size: 18px; ```      | cambiando el tamano de la letra     |
| ``` line-height: 1.5em; ```      | lineas que separan     |
| ``` word-spacing: 0.3em; ```      | espacio entre palabras     |
| ``` letter-spacing: 0.3em; ```      | espacio entre letras     |
| ``` front-weight: bold; ```      | Bold    |
| ``` text-transform: uppercase; ```      | Todo mayuscula    |
| ``` text-align: right ```      | Alinear Texto puede ser left o center   |
| ``` text-align: right ```      | Alinear Texto puede ser left o center   |

Para editar los codigos debemos hace referencia a que lo estamos editando se agrega en el html.


```
<div class="header">
<h1>   </h1>
</div>
```


y para editar eso dentro de nuestro archivo .css
lo invocamos dentro de


 ```
 <style>      
 .header{
 color:Black;
 }
 </style>
 ```


o por id


```
<div id="header">
<h1>   </h1>
</div>
```


en el archivo .css lo invocamos como

```
<style>
#header{
text-align:center;
}
</style>
```


| codigo         | Funcion     |
| :------------- | :------------- |
| ```height: 320px; ```        | Dimenciones con width y height se puede usando px que son pixeles o ems o %     |
| ```min-width: 300px; ```         | ancho minimo      |
| ```max-width: 600px; ```        | ancho maximo      |
| ```max-height: 300px; ```        | alto minimo      |
| ```max-height: 600px; ```        | alto maximo     |


**Agregando Propiedades**


| codigo         | Funcion     |
| :------------- | :------------- |
| ```overflow: scroll; ```    | Aparece contenido y barra para verlo todo       |
| ``` overflow: hidden:```      | Aparece contenido y se esconde       |


**Tipos de Bordes**


| Tipo de borde  | descripcion     |
| :------------- | :------------- |
| solid       | linea       |
| dashed       | guiones       |
| dotted       | puntos cuadrados       |
| double       | frontera de dos lineas      |
| groove       | borde ranura      |
| inset      | corta la pantalla     |
| outset       | aparece para salir de pantalla   |
| ridge       | marco de imagen |
| hidden o none      | sin borde      |


Ejemplo
```
border-style: solid;
border-width: 2px;
```
El border-width es prara hacer referencia al tamano


**Especificando el tamano de cada borde**

```
border-width:3px 1px 3px 1px;
```

o

uno por uno


```
border-top-width: 3px;
border-right-width: 1px;
border-bottom-width: 3px;
border-left-width: 1px;
```

**Cambiando el borde de color**


```
border-color: rgb (22, 77, 100);  <-- o codigo de color
```

**Todo Abreviado**

```
border: 2px Solid #FFF
```

Los pixeles, el tipo, color


**borde que no sea cuadrado**

```
border-radius: 5px;
```


**padding**


padding, sirve para establecer el mismo valor a todas las zonas de relleno de un elemento

```
 padding: 10px;
```

**margin**


Se quiere establecer el mismo valor para todos los márgenes de un elemento:

```
margin-top: 10px;
margin-right: 10px;
margin-bottom: 10px;
margin-left: 10px;
```

o todo Abreviado


```
  margin: 10px 20px 30px 40px;
```


**Para centrar**


```
margin: auto;
```

**Display**


Todos los elmentos se comportan como uno

```
display: inline;
```

Todos es como un elemento en linea

```
display: inline-block;
```


Bloque pero en linea

```
display: block;
```


Elimina elemento de la vista


```
display: none;
```

**Ocultar elmentos**


```
visibility: hidden;
```


**Creando modelo caja**
El que use * antes del parentesis significa que es para todo
```
* {
  box-sizing: border-box;
}
```

**Bloque de niveles**

```
position: static;
position: relative;
position: absolute;
position: fixed;
```

Encima de elementos


```
Z-index: 1000;
```


**Editar tamano de imagen en CSS**

```
<img src="ubicacion" alt="descripcion" class="leaf"/>
```

En CSS


```
img.leaf{
  width: 350px;
  height: 200px;
}
```

Hacer un bloque la imagen


```
display: block;
```


**Fondo de imagen en CSS**

```
background-image:url("link");
```


Tipos de background-image


```
background-repeat;
background-repeat-x;
background-repeat-y;
background-no-repeat;
```

En el primero se repite horizontal y vertical</br>
En el segundo solo a lo horizontal</br>
En el tercero a lo vertical</br>
En el cuarto no se repite</br>


Posicion Css del background

```
background-position: right center;
left top;
center top;
right top;
left center;
center center;
right center;
left bottom;
center bottom;
right bottom;
```


Todo Abreviado

```
background: url("") no-repeat right center;
```


Tamano de el fondo


```
background-size: cover;
background-size: contain;
```


El primero expande la imagen lo mas que pueda

El segundo expande pero no cubrira el ancho de altura


Attachment

```
background-attachment: fixed;
                      scroll;
```


El primero se desplaza


**Generando tablas en HTML**

```
<table>
<tr>
<th> titulos </th>
</tr>
<td>
texto
</td>
</table>
```


row es fila


col es columna


```
<th scope="row"> Texto </th>
<table>
<tr>
<th scope="col">Texto</th>
</tr>
<td>
</td>
</table>
```


**Editando la table en CSS**


Bordes


```
table, td{
border: 1px solid black;
}
```


Abarcar varias columnas


```
<td colspan="2"> Texto<td>
```


Abarcar varias filas


```
<td rowspan="3">Texto dos<td>
```


Tablas Grandes


```
<table>
<tbody>


</tbody>
</table>
```


Separar elementos usando el
```
<thead>
</thead>
```

Cortar usando
```
<tfoot>
```


**Cambiar el tamano desde CSS**


```
table, th, td{
  font-size: 18px;
}
```
