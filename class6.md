

### Dynamic Web Pages with JavaScript

##### New Vocabulary
* JavaScript
* conditionals
* operators
* data types
* variable

## What is Java Script
Java Script is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, etc.


**For starting:** Go to your test site and create a new folder named **scripts**. Within the scripts folder, create a new text document called **main.js**, and save it. In your **index.html** file, enter this code on a new line, just before the closing </body> tag:
`<script src="scripts/main.js"></script>`   (That means we linked js to html file)


##### Language basics 


##### **Variables** are contaniers for storing data.There are 4 ways to declare a JavaScript variable:
 
 var x = 5; var y = 6; var z = x + y;   (  **var** = Used in older JS code )
 
let x = 5; var y = 6; var z = x + y;   ( **let** = Use it if value of variable can be changed  )

const x = 5; var y = 6; var z = x + y;   ( **const** = Use it value of variable cannot be changed )

const x = 5; var y = 6; var z = x + y;    ( **nothing** = Mostly used in Python )

### `let myVariable;` 
* A semicolon at the end of a line indicates where a statement ends. 
* It is only required when you need to separate statements on a single line. 
* There are other rules for when you should and shouldn't use semicolons.(Don't worry about it for now)
* JavaScript is case sensitive. This means `myVariable` is not the same as `myvariable`
* You retrieve the value by calling the variable name: `myVariable;` ( after assigning value `let myVariable;` )
* Also After assigning a value to a variable, you can change it later in the code:
* 
`let myVariable = "Bob";`
`myVariable = "Steve";`

Variables may hold values that have different **data types:**
* **String** `let myVariable = 'Bob';`  means incluede Text Data
* **Number** `let myVariable = 10;`  means incluede Number
* **Boolean** `let myVariable = true;` means this is a True/False value. The words true and false are special keywords.
* **Array**  `let myVariable = [1,'Bob','Steve',10];` Means you're storing multiple values in a single reference.
 
Refer to each member of the array like this:

`myVariable[0]`, `myVariable[1]`, etc.

* **Object** `let myVariable = document.querySelector('h1');` Means This can be anything. Everything in JavaScript is an object and can be stored in a variable. (All of the above examples too.)




###  Basic Functions

**alert** will show up as a pop-up with the text input 

**document.write** will display text that is input in the browser

**console.log** text that is input will show up in the console of the browser; warnings and errors will show up here

**prompt** will display a pop-up window where users can wrtie in their responses

**confirm** will display a pop-up window with a yes or no question


