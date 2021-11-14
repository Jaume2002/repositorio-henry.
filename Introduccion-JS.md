# INTRODUCCIÓN A JAVASCRIPT

## Variables

Es un sistema de almacenamiento que guarda la información donde puedes recuperar. Se estructura de la siguiente forma: (var/const) + nombre de la variable = "ejemplo";

### Var

La variable `var`, es la funcion que asigna de un nombre de una variable a cualquier tipo de cosa, por ejemplo tenemos:

```javascript
    var deudas = "problemas";
// deudas
// "problemas"
```
### const

La variable `const`, es la funcion que asigna de una nombre de una bariable a constante, es decir es inamobible, por ejemplo tenemos:

```javascript
    const areaCir = "2rad";
// areaCir
// "2rad"
```
## Strings

El valor en texto guardado, este es el tipo de dato que es en texto y está delimitado entre comillas `""`, como los ejemplos antes mostrados.

## Funciones

Se utiliza para agrupar código, e imprimir en otras líneas la  función, nos permite de una forma rápida, copiar el código y reescribirlo en otra parte. La estructura de estas son: `function` + nombre de la función (varialble) {codigo de la funcion}.

```javascript
    function carateristicas(modelo, marca){
        console.log("modelos en stock" + modelo);
        console.log("presentacion" + marca);
    }
    var modelo = 2021
    var marca = "motoyota"
    presentar(modelo, marca);
// Modelo en stock 2021, presentación motoyota
```
## Argumento

Significa copiar un variable dentro de una función, que solo cuando utiliza la función tomara validez esa variable, de lo contrario no. Está delimitado después del nombre de la función entre `()`, como podemos observar en el ejemplo anterior.

## Return

Al asignar la palabra clave `return` a la función, devuelve un valor, que será el resultado de una función que se ejecute, por ejemplo, se puede almacenar una variable para utilizar más adelante.

```javascript
    function areaCir (r) {
        return 3.1416 * (r*r);
    }
    var resultado = areaCir(4)
// El área del círculo es: 50.2656
```

## If

`If` torna como un condicional, como él en lenguaje usamos la palabra "Si", lo que hace esta función es comparar, para arrojar un resultado.

```javascript
    function ExesoDeVelocidad (kilometros) {
        if (kilometros < 60) {
            return true;
        }
            return false;
    }
// ExesoDeVelocidad(88);
// True
```
##Boolean

Los booleanos se utiliza con el fin de arrojar 2 tipos de resultados, estos nos referimos a `true` quiere decir de lo anterior es verdadero;  o `false` quiere decir de lo anterior es falso. 

```javascript
    var LA_ANTERIOR_FRASE_ES_FALSA = True;
// LA_ANTERIOR_FRASE_ES_FALSA
// True
```
