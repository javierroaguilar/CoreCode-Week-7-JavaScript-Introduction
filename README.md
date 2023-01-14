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

## Challenge 9 - Count Strings in an object
Codewar link
<https://www.codewars.com/kata/565b3542af398bfb50000003/train/javascript>
``` javascript
function strCount(obj) {
let t = 0;
for (let key in obj) {
  if (typeof obj[key] == 'string') t++;
  if (typeof obj[key] == 'object') t+= strCount(obj[key]);
}
return t;
}
``` 

## Challenge 10 - First() & Last ()
Codewar link
<https://www.codewars.com/kata/581351c40d8f13bc450008b8/train/javascript>
``` javascript
Array.prototype.first = function () {
  return this[0];
}
Array.prototype.last = function () {
  return this[this.length-1]
}
```
## Challenge 11 - Object oriented policy 
Codewar link
<https://www.codewars.com/kata/54fe05c4762e2e3047000add/train/javascript>
``` javascript
function Ship(draft,crew) {
 this.draft = draft;
 this.crew = crew;
 this.isWorthIt = function(){
   if (((this.draft - this.crew*1.5)>20) == true) {
   return true;} return false
   }
}
```
## Challenge 12 - String to a number

Codewar link
<https://www.codewars.com/kata/544675c6f971f7399a000e79/train/javascript>
``` javascript
const stringToNumber = function(str){
  let x = parseInt(str)
  return x;
}
```

## Challenge 13 - Convert number to reversed array of digits
Codewar link
<https://www.codewars.com/kata/5583090cbe83f4fd8c000051/train/javascript>
``` javascript
function digitize(num) {
  
    return String(num).split('').reverse().map(Number);
}
```

## Challenge 14 - Truthy or falsy
Codewar link
<https://www.codewars.com/kata/595c2988d946a13298000157/train/javascript>
``` javascript
const truthy = [true, 1, 'true', {}, (true!=false);
const falsy = [2==3, 0, null, 4 ==2,9 ==='9'];
```

## Challenge 15 - Arrays practice
Codewar link
<https://www.codewars.com/kata/571effabb625ed9b0600107a/train/javascript>
function getLength(arr){

  return arr.length;
}
function getFirst(arr){
 
  return arr[0];
}
function getLast(arr){
  
  return arr[arr.length-1]
}
function pushElement(arr){
  var el=1;
  arr.push(el);
  return arr;
}

function popElement(arr){
  arr.pop();
  return arr;
}
