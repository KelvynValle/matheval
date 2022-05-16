# matheval - Javascript arithmetic expression evaluator
<p align="center">📚✖️➕➗🔢</p><br/>

## 🤓 Matheval? What?
Yes. Matheval. This is a small javascript project focused in allow you and me to safely evaluate arithmetic expressions in strings, returning a float as result. Yes, without the ill-spoken Javascript's eval.
## 🤔 But... Why would I use it?
Mmmm... I don't know. But if you need to evaluate an arithmetic expression from a string, certainly it will be useful. With Matheval.js you can interpret math expressions in strings easily and safely, in a free and open source approach.
## 📐 How can I implement it?
**Step 1**: Download mathEval.js 

Did you download? So, just move the file to your project's directory.


**Step 2**: Paste the following in the header of your page:
```Javascript
<script src="mathEval.js"></script>
```


**Step 3**: It's done!

To use the mathEval() function, just call it with the string expression as parameter.

## 📝 Code examples
**String:**
```Javascript
mathEval("1 + 1 + 1"); //returns 3
mathEval("2 * 7"); //returns 14
mathEval("8 * 2 - 1"); //returns 15
mathEval("2 ^ 7 + 110 - (2 * 73)"); //returns 92
mathEval("600 / 10 + (2.5 * 2)"); //returns 65
```
**Using template strings:**
```Javascript
let a = 15;
let b = 20;
let result = mathEval(`${a} + ${b}`); //returns 35
```
**Concatenating:**
```Javascript
let a = 90;
let b = 1;
let result = mathEval(a + " - " + b); //returns 89
```

**Getting expressions from users:**
```Javascript
//user-input is the id of the input text that get expression from user
var expression = document.getElementById("user-input").value;
let result = mathEval(expression);
```

**Code generated expression:**
```Javascript
//myExpression() is a function that returns an string expression
var expression = myExpression();
let result = mathEval(expression);
```