# CoreCode-Week-7-JavaScript-Introduction

## Challenge 1 - String: substr()
Write a function firstWord, taking a string and returning the first word in that string. The first word are all characters up to the first space.
``` javascript
function firstWord(x){
let e = x.indexOf(' ');
let z = x.substr(0,e);
return z}
```

## Challenge 2 - Replace()
Write a function normalize, that replaces '-' with '/' in a date string.
``` javascript
function normalize(x) {
let e = x.replace('-','/')
let d = e.replace('-','/');
return d;}
``` 
## Challenge 3 - Increase

Which value does x have after execution of the following code?
``` javascript
let x = 3;
x++;
x = x * 2;
x--;
``` 
Answer
``` javascript
x = 7
``` 

## Challenge 4 - Fahrenheit 
Write a function toFahrenheit that converts a temperature from Celsius to Fahrenheit.
``` javascript
function toFahrenheit(e){
let x = (e*1.8)+32;
return x;
}
``` 

## Challenge 5 - Boolean
Write a function nand that takes two Boolean values. If both values are true, the result should be false. In the other cases the return should be true.
``` javascript
function nand(x,e){
let t = (x&&e);
return !t;
}
```
