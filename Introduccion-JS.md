# Introducción a Javascript

Conceptos basicos.

## Variables

Es un sistema de almacenamiento que guarda la informacion donde puedes recuperar. Se estructura de la sigiente forma: (var/const) + nombre de la bariable = "ejemplo";

### var

la variable "var", es la funcion que asigna de un nombre de una bariable a cualquier tipo de cosa, por ejemplo tenemos (ejemplo 1 en: archivo-ejemplo.js):

```javascript
    var deudas = "problemas";
// deudas
// "problemas"
```
### const

La variable "const", es la funcion que asigna de una nombre de una bariable a constante, es decir es inamobible, por ejemplo tenemos:

```javascript
    const areaCir = "2rad";
// areaCir
// "2rad"
```
## Strings

s el valor en texto guardado, este es el tipo de dato que es en texto y esta delimitado entre comillas, como los ejemplos antes mostrados.

## Funciones

Se utiliza para agrupar codigo, e imprimir en otras lineas la  funcion, nos permite de una forma rapida, copiar el codigo y reescribirlo en otra parte. La estructura de estas son: function + nombre de la funcion(varialble) {codigo de la funcion}

```javascript
    function carateristicas(modelo, marca){
        console.log("modelos en stock" + modelo);
        console.log("presentacion" + marca);
    }
    var modelo = 2021
    var marca = "motoyota"
    presentar(modelo, marca);
// Modelo en stock 2021, presentacion motoyota
```
## Argumento

Significa compiar un bariable dentro de una funcion, que solo cuando utilize la funcion tomara validez esa variable, de lo contrario no. esta delimitado despues del nombre de la funcion entre ().

## Return

Al asignar la palabra clave return a la funcion, devuelve un valor, que será el resultado de una función que se ejecute, por ejemplo, se puede almacenar una varriable para utilizar mas adelante.

```javascript
    function areaCir (r) {
        return 3.1416 * (r*r);
    }
    var resultado = areaCir(4)
// El área del círculo es: 50.2656
```
## If

Esta torma como un condicional, como el en leneguaje usamos la palabra "Si", lo que hace esta funcion es comparar, para arrojar un resultado.

```javascript
    function ExesoDeVelocidad (kilometros) {
        if (kilometros > 60) {
            return true;
        }
            return false;
    }
// ExesoDeVelocidad(88);
```
##Boolean

Se utiliza al utilizar para referirnos entre "true" o "false".

```javascript
    var LA_ANTERIOR_FRASE_ES_FALSA = True;
// LA_ANTERIOR_FRASE_ES_FALSA
// True
```
