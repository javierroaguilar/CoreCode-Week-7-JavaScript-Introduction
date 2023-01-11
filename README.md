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
## Challenge 6 - Objects-Codewars
Codewar link
<https://www.codewars.com/kata/571f1eb77e8954a812000837/train/javascript>
``` javascript
let obj={name:"dog", legs:4,color:'white'};
function animal(obj){
  let x=obj;
  return 'This ' + x.color + " "+ x.name + " has " + x.legs + " legs."
}
```

## Challenge 7 - Return to sanity
Codewar link
<https://www.codewars.com/kata/514a7ac1a33775cbb500001e/train/javascript>
``` javascript
function mystery () {
  let results = {sanity:'Hello'};
  return results;
}
```

## Challenge 8 - Debugging 
Codewar link
<https://www.codewars.com/kata/56d8ae9237123036d3001b54/train/javascript>
``` javascript
var rooms = { first: 
             {description: 'This is the first room', items: {chair: 'The old chair looks comfortable',
      lamp: 'This lamp looks ancient'}
            ,
  second: {
    description: 'This is the second room', items: {
      couch: 'This couch looks like it would hurt your back', table: 'On the table there is an unopened bottle of water'
    }
  }
}
}
``` 
