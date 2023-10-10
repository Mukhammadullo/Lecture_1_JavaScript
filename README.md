# JavaScript Introduction

## _History of JavaScript_
>**This programmin language was created by Brendan Eich in 1995.It was first called Mocha, then LiveScript , and finnaly JavaScript**
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


