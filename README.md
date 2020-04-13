# Javascript Building Blocks

Checklist

Basic programming knowledge

```

Lets get started

````

## Key concepts

> Javascript is case sensitive

> Since JavaScript is mainly used for web products, it is highly recommended to know HTML and CSS beforehand,
 so it becomes easier to develop things, Not necessary



````
var name = "Mkhululi"

var NAME = "Mkhululi"

````

## Changing HTML Content

Using getElementByID("") method

```` document.getElementById("name").innerHTML = "Hello Mkhululi Cooper"; ````

Method getElementByID("") finds element with id="name" then replace the element contents with innerHTML text "Hello Mkhululi Cooper"

> single '' and double quotes "" are the same in Javascript

## Adding Javascript to a page

Javascript is inserted between <script></script> tags (Inline Javascript)

### Referencing to external js file

You can also import Javascript from a js file by referring to it as seen below :

<script src="jsfile.js"></script>


> Please note that adding scripts at the bottom of the <body> element improves the display speed, 
because script interpretation slows down the display

## Displaying Javascript in a page

document.write() //for testing
console.log() // for debugging
innerHTML // To access html element
window.alert() //Alert box

## Syntax

> var a, b, c; // Declaring variables

> var a = 1; // Assigning variables

> Semicolon ; seperate javascript statements

> Whitespaces are ignored


## Reserved words

Javascript statements usually start with a keyword/reserved word.

Reserved words cannot be used as names of variables.

Check the list of reserved words here [W3Schools](https://www.w3schools.com/js/js_reserved.asp)

## Comments

Any text inbetween comments is ignored

```` // Single line comment ````

```` /*  Multiple line comments */ ````

## Data types

```` var x = 5 //  Number ````
```` var name = "Mkhululi Cooper" //  String````
```` var address = {street:12,city:"dubai"} //  Object````

## Arrays

Array indexes are zero based meaning the first item is [0] and second item [1]

```` var products = ["samsung","nokia","iphone"] ````


## Objects

Written with curly braces {}

Written as name, value pairs and seperated by commas as seen below.

```` var address = {street:12,city:"dubai"} //  Object ````





