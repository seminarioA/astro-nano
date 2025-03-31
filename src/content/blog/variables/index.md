---
title: "¿Que es una variable?"
description: "Variables para todos. 👀"
date: "Mar 30 2025"
---

---

### Variables para dummies 🤓

Una variable es un contenedor, donde puedes almacenar datos de cualquier tipo (numerico, textual, booleano, etc).

Puedes imaginar a una variable como una caja en donde puedes guardar "cosas".

![Gato entrando a una caja](./gato.gif)

#### ¿Y como creo una variable? 👀

La creacion de una variable tiene dos etapas

La **definicion**:
```java
// En Java:
String frase;
```
```python
# En Python:
frase:str
```

Y la **asignacion** (de valores):
```java
// En Java:
frase = "¡Hola, mundo!";
```
```python
# En Python:
frase = "¡Hola, mundo!"
```


### El alcance importa 😮

Si... a esto se le denomia "scope"

No es lo mismo definir una variable para una funcion

```js
function saludo() {
    let frase = "¡Hola, mundo!";
    return frase;
}

console.log(saludo())
```

Que para **todo** un programa: 
```js
var frase = "¡Hola, mundo!"; 
```
### Variables que no varian: ¿Que? 🤔
Bueno...

En algunos lenguajes existen palabras reservadas que nos permiten declarar y asignar variables que ya no cambiaran a lo largo del tiempo (de ejecucion). A este tipo de variables se les denomina constantes y a la caracteristica de no cambiar una vez asignadas se les denomina inmutabilidad.

¡Quiero ver un ejemplo!

```java
// En Java
static final String saludo = "¡Hola, mundo!";
```

```js
// En JavaScript
const frase =  "¡Hola, mundo!"; 
```

### "Soy purista, necesito una definicion mas tecnica 😒"

Bueno...

Una variable es un referenciador por nombre a una direccion de memoria.