### Q2
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
```js
let value = parseInt(prompt('How many runs you scored in this ball'));
if (value === 4) {
      console.log("You hit a Four");
} else if (value === 6) {
      console.log("You hit a Six");
} else {
      console.log("I couldn't figure out");
}
```
```js
let login = 'Employee';
let message = (login == 'Employee') ? (login == 'Director') ? 'Greetings' : (login == '') ? 'No login' : 'Welcome' : '';
console.log(message);
```
```js
let message;
if (null || 2 || undefined)
{
 message = "welcome boss";
}
else
{
 message = "Go away";
}
console.log(message);
``` 
```js
let message;
let lock = 0; //Dont change any code below this 
if (null || lock || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
console.log(message);
```
```js
let message;
let lock = 0; // Dont change any code below this
if (lock && " " || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
console.log(message);
```
```js
let i = 3;
while (i) {
  console.log(i--);
}
```
```js
for(let num = 1; num < 11; num++) {
  console.log(num);
}
```
```js
for (let num = 2; num <= 20; num += 2) {
  console.log(num)
}
```
```js
let gifts = ["teddy bear", "drone", "doll"];
for (let i = 0; i < 3; i++) {
  console.log(`Wrapped ${gifts[i]} and added a bow!`);
}
```
```js
let countdown = 100;
while (countdown > 0) {
  if(countdown == 0)
  {
   console.log("bomb triggered");
  }
  countdown--;
}
```
```js
// It will print "hi" because "0" is truthy value and 0 is falsy value.
```
### Q3
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var new_string = “”;
 
for (var i = 0; i < 11; i--) {
  new_string += numsArr[i] 
}
console.log(new_string);
```
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var new_string = “”;
 
for (var i = 0; i < 10; i++) {
  new_string += numsArr[i] + ','; 
}
new-string += numsArr[i];
console.log(new_string);
```
```js
var new_string = “”;
 
for (var i = 10; i > 0; i — ) {
  new_string += numsArr[i] + “ “; 
}
new_string += numsArr[i];
console.log(new_string);
```
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
for (var i = 0; i <=10; i++) {
  if(numsArr[i] %2 == 0) {
    numsArr[i] = "even";
  }
}
console.log(numsArr);
```
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
for (var i = 0; i <=10; i++) {
  if(i % 2 == 0 ) {
    numsArr[i] = "even";
  }
}
console.log(numsArr);
```
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
let sum = 0;
for (var i = 0; i <=10; i++) {
  sum += numsArr[i]
}
console.log(sum);
```
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=0;
for (var i = 0; i <10; i++) {
  if(numsArr[i] % 2 == 0){
    sum += numsArr[i];
  }
}
console.log(sum);
```
```js
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=100;
for (var i = 0; i <=10; i++) {
  if(numsArr[i] % 2 == 0);{
    sum += numsArr[i]
  }
  else {
    sum -= numsArr[i]
  }
}
console.log(sum);
```
```js
var numsArr = [[1, 2, 3, 4, 5], [ 6, 7, 8, 9, 10, 11]];
for (var i = 0; i < numsArr.length; i++); {
  console.log( numsArr[i]);
}
```
```js
var numsArr = [[1, 2, 3, 4, 5], [ 6, 7, 8, 9, 10, 11]];
var str_all = "";
for (var i = 0; i < numsArr.length; i++) {
  var inner_array = numsArr[i];
  for(var j = 0 ; j < inner_array.length; j++ ) {
    str_all += inner_array[j];
  }
}
console.log(str_all);
```
```js
var numsArr = [[1, 2, 3, 4, 5], [ 6, 7, 8, 9, 10, 11]];
for (var i = 0; i < numsArr.length; i++) {
  var inner_array = numsArr[i];
  for(var j = 0 ; j < inner_array.length; j++ )
    if(j % 2 == 0 ) {
      numsArr[i][j] = "even";
    }
  }
}
console.log(numsArr);
```
```js
var numsArr = [[1, 2, 3, 4, 5], [ 6, 7, 8, 9, 10, 11]];
var str_all = "";
for (var i = numsArr.length - 1; i >= 0; i--) {
  var inner_array = numsArr[i];
  for(var j = inner_array.length - 1; j >= 0 ;j-- )
    str_all +=inner_array[j];
  }
}
console.log(str_all);
```
```js
var numsArr = [[1, 2, 3, 4, 5], [ 6, 7, 8, 9, 10, 11]];
var sum_odd=0;
var sum_even=0;
for (var i = 0; i < numsArr.length; i++) {
  var inner_array = numsArr[i];
  for(var j = 0 ; j < inner_array.length;j++ ){
    if(inner_array[i] % 2 != 0) {
      sum_odd += inner_array[i];
    }
    else {
      sum_even += inner_array[i];
    }
  }
}
console.log(sum_odd);
console.log(sum_even);
```
