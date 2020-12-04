# Arrays
Alcuni metodi per l'utilizzo di array in JavaScript.

## .push(elemento)
Viene aggiunto `elemento` come ultimo nell'array.
```
var stringArray = ["apple","banana","oranges"];
stringArray.push("avocado");

console.log(stringArray);
```
#### Output
`["apple","banana","oranges","avocado"]`.

## .pop()
Viene eliminato l'ultimo elemento dell'array.
```
var stringArray = ["apple","banana","oranges"];
stringArray.pop();

console.log(stringArray);
```
#### Output
`["apple","banana"]`.

## .shift()
Viene eliminato il primo elemento dell'array.
```
var stringArray = ["apple","banana","oranges"];
stringArray.shift();

console.log(stringArray);
```
#### Output
`["banana","oranges"]`.
