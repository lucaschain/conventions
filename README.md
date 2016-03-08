# Coding Standards

## Text editor configurations:
Indentation: 2 spaces
Encoding: utf-8

## Commenting
Single item commenting:
```Javascript
var name = ""; // this is the user name
var age = 0;  // this is the user age
```
Block commenting:
```Javascript
/*
 * this will do that thing when foo is exactly equals bar.
 */
if (foo === bar) {
  doIt();
}
```
Do not rely only on comments. Use good variable names:
```Javascript
var myVar = "foo"; // This is the user name (bad)
var userName = "foo"; // This is the user name (good)
```

## Variables
Always declare variables at the beginning of the scope they are used:
```Javascript
function fooAndBar () {
  var foo = "";
  var bar = 0;

  doThat(foo, bar);
}
```
Use plural for arrays:
```Javascript
var fruit = 'apple'; // a single string for fruit
var fruits = ['tomato', 'apple', 'banana']; // an array of fruits for fruits
```

## Conditions
Use spaces before opening parenthesis and after closing them:
```javascript
/*
 * Good:
 */
if (true) {
  foo();
} else {
  bar();
}

/*
 * Bad
 */
if(true){
  foo();
} else{
  bar();
}
```
TODO: } else {

## Functions
Use camelCase for function names:
```Javascript
/*
 * good stuff:
 * pascal case for names
 */
function myTestFunction (x, y) {

}

/*
 * bad stuff
 * underlines, capital for first letter
 */
function My_test_function(foo,bar){

}
```
TODO: spaces before and after parenthesis
