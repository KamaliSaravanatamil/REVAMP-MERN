What is JavaScript?
-Javascript is used to create interactive and dynamic web pages
-It is responsible for adding functionality to a website and allows users to interact with the content

Variables and Types:
-Used to store information data
-JavaScript Variables can be declared in 4 ways:
Automatically
Using var
Using let
Using const

Comments in JavaScript:
-Comments are clasified into SINGLE LINE and MULTILINE COMMENTS
-Multi-line comments start with /* and end with */.
Any text between /* and */ will be ignored by JavaScript.
-Single line comments start with //.
Any text between // and the end of the line will be ignored by JavaScript (will not be executed).

Data Types:
-Primitive
// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

//NULL
let x=null;

//undefined
var x;

-Non Primitive
// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

Functions in JavaScript:
function greetUser(name) {
    return "Hello, " + name + "! Welcome!";
}

// Calling the function with a sample name

let message = greetUser("Alice");

// Displaying the result
console.log(message);

if Else in JavaScript:
const temperature=10.5;
if(temperature>30)
{
console.log("high");
}
else
{
console.log("low);
}


FOR LOOP:
for(let i=1;i<=5;i++)
{
console.log(i);
}

Loose vs Strict Equality:
console.log(5 == "5"); // true (string "5" is converted to number 5)
console.log(0 == false); // true (false is converted to 0)
console.log(null == undefined); // true (both are treated as empty values)

console.log(5 === "5"); // false (number vs string)
console.log(0 === false); // false (number vs boolean)
console.log(null === undefined); // false (different types)
