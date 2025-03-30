---
title: "¿Que es una variable?"
description: "Variables para todos. 👀"
date: "Mar 30 2025"
---

---

### Variables para dummies 🤓

Una variable es un contenedor, donde puedes almacenar datos del tipo numerico, textual, booleano, etc.

Puedes imaginar a una variable como una caja en donde puedes guardar "cosas".

#### ¿Y como creo una variable? 👀

La creacion de una variable tiene dos etapas

La **definicion**:
```python
frase = ""
```
Y la **asignacion** (de valores):
```python
frase = "¡Hola, mundo!"
```

```
📌 Ejemplo escrito en: Python 🐍
```

### El alcance importa 😮

Si... a esto se le denomia "scope"

No es lo mismo definir una variable para una funcion

```js
function scopeVar(string) {
    let text = "¡Hola, mundo!";
    return text;
}

console.log(scopeVar)
```

Que para **todo** el programa: 
```js
var frase =  "¡Hola, mundo!"; 
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

Una variable es un referenciador por nombre a un espacio de memoria.