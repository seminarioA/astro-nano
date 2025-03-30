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

### "Soy purista, necesito una definicion mas tecnica 😒"

Bueno...

Una variable es un referenciador por nombre a un espacio de memoria.