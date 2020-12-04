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

## Leggere i-esimo elemento
Vogliamo leggere l'elemento in posizione `x` dell'array.
Ricordare che le posizioni iniziano da 0.
```
var stringArray = ["apple","banana","oranges"];
var x = 2;
console.log(stringArray[x]);
```
#### Output
`"oranges"`.

## Leggere ultimo elemento
Vogliamo leggere l'elemento in ultima posizione dell'array.
```
var stringArray = ["apple","banana","oranges"];
console.log(stringArray[stringArray.length]);
```
#### Output
`"oranges"`.


