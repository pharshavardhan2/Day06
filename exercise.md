- I will put each question in it's own code block
```js
alert("I'm JavaScript!");
```
```js
// It's working fine for me. No errors
```
```js
// js engine can recognize the end of statement automatically so not mandatory to insert semicolons
// string templates can span multiple lines
// As expression is broken into new lines at operator, it works.
```
```js
let admin=9, fname=10.5; 
fname = "Guvi";
lname = "geek"
admin = fname + " " + lname;
alert(admin);
```
```js
let fname=10.5; 
fname = "Guvi";
lname = "geek";
let name = fname + " " + lname;
alert(`hello ${name}`);
```
```js
let a = parseInt(prompt("First number?"));
let b = parseInt(prompt("Second number?"));
alert(a + b);
```
```js
// var a = "2" > "12"; // This line checks which first first character has larger ASCII value as both are strings and '2' is bigger than '1'. So true
var a = 2 > 12;  // It checks for value of nos so returns false
if (a) {
  console.log("Code is Blasted")
}
else
{
  console.log("Diffused") 
}
```
```js
let a = prompt("Enter a number?"); // a value will be string always. whatever num may be string even '0' which is not empty string
// only '' i.e empty string is false in js.
if (a) {
 console.log( 'OMG it works for any number inc 0' );
}
else
{
 console.log( "Success" );
}
```
