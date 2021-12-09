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
### Q4
```js
aa = (f,s,t) => {
  if(f>s && f>t){
    console.log(f);
  } else if(s>f && s>t) {
    console.log(s);
  } else {
    console.log(t);
  }
};
aa(1,2,3);
```
```js
let n = 123;
function add(n) {
  let sum = 0;
  while(n > 0) {
    sum += n % 10;
    n = n / 10;
  }
  return sum;
}
console.log(add(n));
```
```js
const arr = [9,8,5,6,4,3,2,1];
(function(arr) {
  let sum = 0;
  for (var i = 0; i <= arr.length; i++);{
    sum += arr[i];
  }
  console.log(sum);
})(arr);
```
```js
var arr = [“guvi”, “geek”, “zen”, “fullstack”];
var ano = function(arro) {
  for (var i = 0; i <= arro.length; i++) {
    console.log(arro[i][0].toUpperCase() + arro[i].substr(1));
  }
};
ano(arr);
```
```js
const newArray=[1,3,2,5,10];
const myPrime = newArray.filter(num => {
  let prime = true;
  for(let i = 2; i <= num ** 0.5; i++) {
    if(num % i == 0) {
      prime = false;
      break;
    }
  }
  return num === 1 ? false : prime;
});
console.log(myPrime);
```
```js
const num = [10, 20, 30, 40,50,60,70,80,90,100];
const fun = (a, b) => a + b;
const sum = num.reduce(fun)
console.log(sum);
```
```js
var arr = [1, 2, 3, 6, 8, 6, 1, 9, 10, 12, 13];
var k = 3;
k = arr.length % k;
(function(arr) {
    out = arr.slice(k + 1, arr.length);
    var count = out.length;
    for (var i = 0; i < k + 1; i++) {
        out[count] = arr[i];
        count += 1;
    }
    console.log(out);
    
})(arr);
```
```js
var arr = ["guvi", "geek", "zen", "fullstack"];
(function(arr) {
 for (var i = 0; i <= arr.length; i++) {
    console.log(arr[i][0].toUpperCase() + arr[i].substr(1));
 }
})(arr);
```
```js
var arr = [1, 2, 3, 5, 7, 79, 7, 2, 6, 9, 4];
(function(arr) {
 for (var i = 0; i < arr.length; i++) {
    if (arr[i] % 2 !== 0) {
        console.log(arr[i]);
    }
 }
})(arr);
```
```js
(function(str){
 str1 = str.split("").reverse().join("");
 console.log(str1); 
})('abcd');
```
```js
var res = function(arr){
 let newArr = [];
 for(var i=0; i < arr.length; i++){
    if(newArr.indexOf(arr[i]) == -1) {
        newArr.push(arr[i]);
    }
 }
 console.log(newArr);
};
res(["guvi","geek",'guvi','duplicate','geeK']);
```
```js
var array =[[['firstname','vasanth'],['lastname','Raja'],['age',24],['role','JSWizard']],[['firstname','Sri'],['lastname','Devi'],['age',28],['role', 'Coder']]];
var final=[];
while(array.length!=0) {
 var outer_remove = array.shift();
 let new_object = {};
 while(outer_remove.length!=0) {
     var inner_remove = outer_remove.shift();
     var key = inner_remove[0];
     var value =inner_remove[1];
     new_object[key]=value;
 }
 final.push(new_object);
}
console.log(final);
```
```js
var as=[12,34,5,6,2,56,6,2,1];
var s = as.reduce(function(a,c){
 if(c%2!=0)
 {
    return a+c;
 }
 return a;
}, 0);
console.log(s);
```
```js
let aa = (a) => {
    let l='';
    for(let i = 0; i < a.length-1; i += 2){
        let s=a[i+1];
        let b=a[i];
        l+=s;
        l+=b;
    }
    if((a.length%2)!=0){
        l+=a[a.length-1];
    }
    console.log(l);
};
aa('1234');
```


