# JavaScript Introduction

## _History of JavaScript_
>**This programming language was created by Brendan Eich in 1995.It was first called Mocha, then LiveScript , and finnaly JavaScript**
## _What is ECMAScript?_
>**ECMAScript (ES) is a standardized scripting language specification that JavaScript is based on.**

## _What is JavaScript?_
>**JavaScript is a programming language that is commonly used for creating interactive and dynamic websites**

## _What is dynamic?_
>**In JavaScript, "dynamic" means that things can change and adapt while the program is running.**

## _What is ineractive?_
>**"Interactive" means that a program or application allows users to actively engage with it by providing input and receiving immediate feedback or results.**

## _JavaScript variables_
>**What is variable? -Variable is a container(storage area) to hold data**

>**Var-is used in the older versions of JavaScript** 

 
``` js
var number = 127 

console.log(number)  //127
```


>**Let-is the new way of declarations variables.**

``` js 
let number = 127 

console.log(number) //127

```

>**Const-is a keyword used to declare a variable that cannot be reassigned or redeclared once it has been assigned a value.**

``` js
const pi= 3.14

console.log(pi) //3.14

 ```

## _What value in JavaScript_
>**In JavaScript, a value is a piece of data that can be stored in a variable or used in an expression.**
>>values divided into two groups
- ## What is Object?
_Objects are more complex data types in JavaScript. They are collections of key-value pairs, where each key is a string (or symbol) and each value can be of any data type, including other objects. Objects are created using the object literal syntax, which consists of key-value pairs enclosed in curly braces {}._
```js
let person ={
    name:"Muhammadullo",
    job:"student",
    phone:999 000 333,
    country:"Tajikistan"
    email:"nastulloev@gmail.com"
}
```

- ## _Primative_
_Primitives are the basic, fundamental data types in JavaScript. They represent simple values and are immutable, meaning their values cannot be changed once they are created._
```js 
let firstName="Muhammadullo"
console.log(firstName)

let job="Student"
console.log(job)
```
- ## _Also there are seven primitive types in JavaScript:_
- ### 1.Number-number value represents numeric data. It can be used to perform mathematical operations, store quantities, or represent numerical information in a program.
```js
let number=123.45
console.log(number)
``` 
- ### 2.String-is a sequence of characters enclosed in single quotes (') or double quotes ("). It is used to represent textual data, such as names, sentences, or any other collection of characters.
```js

let fullName="Nastuloev Muhammadullo"
console.log(fulName)
```
- ### 3.Boolean-logical type that can only be true or false
```js
10>5? console.log(true) : console.log(false); // true
```

- ### 4.Undefined-value taken  by a variable that is not yet defined ("EMPTY VALUE")

```js 
let number
console.log(number)         // undefined

let number=undefined
console.log(typeof(number))  //undefined

let undefined=undefined
console.log(undefined)      //undefined

```
- ### 5.Null aslo-empty value *but typeof() object
```js
let number=null
console.log(number) //number


let number=null
console.log(typeof(number)) //object


** console.log(undefined==null) // true
```
- ### 6.Symbol-a  is a unique and immutable data type that is used as an identifier for object properties.Символ — это уникальный и неизменяемый тип данных, который используется в качестве идентификатора свойств объекта.(рамз як навъи додаи беназир ва тағйирнопазир аст, ки ҳамчун идентификатор барои хосиятҳои объект истифода мешавад.)
```js
const symbol1 = Symbol(); 
const symbol2 = Symbol(); 

console.log(symbol1 === symbol2); 
// Output: false (symbols are always unique)
```
- ### 7.BigInt- values are created by appending the n suffix to an integer literal or by using the BigInt() function. 
```js
const bigNumber = 1234567890123456789012345678901234567890n; // 
console.log(bigNumber); // Output: 1234567890123456789012345678901234567890n


//typeof
const bigNumber=1234n
console.log(typeof(biNumber)) //BigInt
```

- >># _JavaScript has dynamic typing: We do not have to manually define the data tyoe of value stored in a variable ***Value has type , Not variable_


- ## _Operators in JavaScript_
> ### _Arithmatic Operator in JavaScript_
```js

//plus
consoloe(20+30) //50

//minus
console.log(10-5) //5  

//multiplying
console.log(2*8) //16

//devided
console.log(8/2) //4
```
> ### _Comparison in JavaScript_
```js

// ==
console.log(2==2) //true
console.log(2=="2")// true

// ===  
console.log(2==="2") // false

// >=
console.log(2>=1) //true
console.log(2>1) //true

//!=
console.log(2!=2) //false

```

> _Logical In JavaScript_
```js

// ||_or

if(2>5 || 2<5){
    console.log(true)
}else
console.log(false)   //true


// &&_and
if(2<3 && 3>2)
{
    console.log(true)
}else 
console.log(false) //true


// !_not
console.log(!true) //false

```

- ## _JavaScript type Conversions_
```js

// +
console.log(2+"2") //22
console.log(2+"2a") //22a
console.log(2+true) //2true
console.log(2+undefined) //2undefined
console.log(2+null) //2nul  

//worked concat 

```

- ## _Conditions in javaScript_
>simple
```js


let numOne=5
let numTwo=3
if(numOne>numTwo){
    console.log("NumOne is big")
}else 
console.log("NumTwo is big")


```
>Ternary Operator
```js

let numOne=5
let numTwo=3


numOne>numTwo? console.log("NumOne is big") : console.log("NumTwo is big")

```
>Switch Case
```js
let winter = "December"
switch (winter) {
    case "December":
        console.log("Seasons winter");
        break;
    case "January":
        console.log("Season winter");
        break;
    case "February":
        console.log("Season winter");
        break;
    case "March":
        console.log("Season spring");
        break;
    case "April":
        console.log("Season spring");
        break;
    case "May":
        console.log("Season spring");
        break;
    case "June":
        console.log("Season summer");
        break;
    case "July":
        console.log("Season summmer");
        break;
    case "August":
        console.log("Season summer");
        break;
    case "September":
        console.log("Season Autumn");
        break;
    case "October":
        console.log("Season Autumn");
        break;
    case "November":
        console.log("Season Autumn");
        break;
    default:
        console.log("Eror Enter ");
        break;
}

```

- ## _Loop in JavaScript_
>loop_for_in_JavaScript
```js

for(let i=0; i<10 ; i++){
    console.log("Welcome to SoftClub")
}
```
>Loop while in JavaScript
```js
let n=0;
let x=0;

while(n<3){
    n++
    x+=n
}
console.log(n) //3 
console.log(x) //6
```
>Loop do While in JavaScript
```js
let result ='';
let i=0;

do{
    i=i+1;
    result=result+i;
}while (i<5)
console.log(result)  //12345    
```
## ___________________________________________________________________

## _What is Function in JavaScript?_
> ### _In JavaScript, a function is a reusable block of code that performs a specific task or calculates a value.(В JavaScript функция — это повторно используемый блок кода, который выполняет определенную задачу или вычисляет значение.)_


## - _Three are ways of writing a function in JavaScript_
> # _1.Function declaration_
```js

function SumNum(a,b){
    return a+b
}
console.log(SumNum(5,5)) // 10
```
> # _2.Function Expression have two way_
```js
//first way -> anonymous function

let SumNum=function(a,b){
    return a+b
}
console.log(SumNum(2,3))


//arrow function
let SumNum=(a,b)=>{
    return a+b
}
console.log(SumNum(2,3))
```
> # _3.  Immediately Invoked  Function Expression_
```js
(function () {
    console.log(3 + 3);
})()

```

!["time"](time.jpg)

