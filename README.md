# Freecodecamp

## Basic-JavaScript

1. Comment Your JavaScript Code
```
/* my comment */
// my comment
```
2. Declare JavaScript Variables
```
var myName;
```
3. Storing Values with the Assignment Operator
```
// Setup
var a;

// Only change code below this line
a = 7;
```
4. Assigning the Value of One Variable to Another
```
// Setup
var a;
a = 7;
var b;

// Only change code below this line
b = a;
```
5. Initializing Variables with the Assignment Operator
```
var a = 9;
```
6. Declare String Variables
```
var myFirstName = "Sergey";;
var myLastName = "Vanukou";;
```
7. Understanding Uninitialized Variables
```
// Only change code below this line
var a = 5;
var b = 10;
var c = "I am a";
// Only change code above this line

a = a + 1;
b = b + 5;
c = c + " String!";
```
8. Understanding Case Sensitivity in Variables
```
// Variable declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Variable assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```
9. Explore Differences Between the var and let Keywords
```
let catName = "Oliver";
let catSound = "Meow!";
```
10. Declare a Read-Only Variable with the const Keyword
```
const FCC = "freeCodeCamp"; // Change this line
let fact = "is cool!"; // Change this line
fact = "is awesome!";
console.log(FCC, fact); // Change this line
```
11. Add Two Numbers with JavaScript
```
const sum = 10 + 10;
```
12. Subtract One Number from Another with JavaScript
```
const difference = 45 - 33;
```
13. Multiply Two Numbers with JavaScript
```
const product = 8 * 10;
```
14. Divide One Number by Another with JavaScript
```
const quotient = 66 / 33;
```
15. Increment a Number with JavaScript
```
let myVar = 87;

// Only change code below this line
myVar = ++myVar;
```
16. Decrement a Number with JavaScript
```
let myVar = 11;

// Only change code below this line
myVar = --myVar;
```
17. Create Decimal Numbers with JavaScript
```
const ourDecimal = 5.7;
let myDecimal = 13.5
```
18. Multiply Two Decimals with JavaScript
```
const ourDecimal = 2.0*2.5;
```
19. Divide One Decimal by Another with JavaScript
```
const quotient = 4.4 / 2.0; 
```
20. Finding a Remainder in JavaScript
```
const remainder = 11 % 3;
```
21 Compound Assignment With Augmented Addition
```
let a = 3;  
let b = 17;  
let c = 12;  

// Only change code below this line  
a += 12;  
b += 9;  
c += 7;  
```
22. Compound Assignment With Augmented Subtraction
```
let a = 11;
let b = 9;
let c = 3;

// Only change code below this line
a -=6;
b -= 15;
c -= 1;
```
23. Compound Assignment With Augmented Multiplication
```
let a = 5;
let b = 12;
let c = 4.6;

// Only change code below this line
a *=5;
b *=3;
c *=10;
```
24. Compound Assignment With Augmented Division
```
let a = 48;
let b = 108;
let c = 33;

// Only change code below this line
a /=12;
b /=4;
c /=11;
```
25. Escaping Literal Quotes in Strings
```
const myStr ="I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
```
26. Quoting Strings with Single Quotes
```
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```
27. Escape Sequences in Strings
```
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine"; // Change this line
```
28. Concatenating Strings with Plus Operator
```
const myStr = "This is the start. " + "This is the end."; // Change this line
```
29. Concatenating Strings with the Plus Equals Operator
```
let myStr = "This is the first sentence. "
myStr += "This is the second sentence.";
```
30. Constructing Strings with Variables
```
// Only change code below this line
const myName = "Sergey";
const myStr = "My name is " + myName + "and and I am well!";
```
31. Appending Variables to Strings
```
// Change code below this line
const someAdjective = "intrestig";
let myStr = "Learning to code is ";
myStr += someAdjective;
```
32. Find the Length of a String
```
// Setup
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName.length;
```
33. Use Bracket Notation to Find the First Character in a String
```
// Setup
let firstLetterOfLastName = "";
const lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0]; // Change this line
```
34. Understand String Immutability
```
// Setup
let myStr = "Jello World";

myStr = "Hello World"; // Change this line
```
35. Use Bracket Notation to Find the Nth Character in a String
```
// Setup
const lastName = "Lovelace";

const thirdLetterOfLastName = lastName[2]; // Change this line
```
36. Use Bracket Notation to Find the Last Character in a String
```
// Setup
const lastName = "Lovelace";

// Only change code below this line
const lastLetterOfLastName = lastName[lastName.length-1]; // Change this line
```
37. Use Bracket Notation to Find the Nth-to-Last Character in a String
```
// Setup
const lastName = "Lovelace";

// Only change code below this line
const secondToLastLetterOfLastName = lastName[lastName.length -2]; // Change this line
```
38. Word Blanks
```
const myNoun = "dog";
const myAdjective = "big";
const myVerb = "ran";
const myAdverb = "quickly";

// Only change code below this line
const wordBlanks = myNoun + " "+ myVerb +" "+ myAdjective+ " " + myAdverb; // Change this line
// Only change code above this line
```
39. Store Multiple Values in one Variable using JavaScript Arrays
```
// Only change code below this line
const myArray = ["food", 13];
```
40. Nest one Array within Another Array
```
// Only change code below this line
const myArray = [["one", 2], ["three", 4]];
```
41. Access Array Data with Indexes
```
const myArray = [50, 60, 70];
const myData = myArray[0];
```
42. Modify Array Data With Indexes
```
// Setup
const myArray = [18, 64, 99];
myArray[0] = 45
// Only change code below this line
```
43. Access Multi-Dimensional Arrays With Indexes
```
const myArray = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14],
];
const myData = myArray[2][1];
```
44. Manipulate Arrays With push()
```
// Setup
const myArray = [["John", 23], ["cat", 2]];

// Only change code below this line
myArray.push(["dog", 3])
```
45. Manipulate Arrays With pop()
```
// Setup
const myArray = [["John", 23], ["cat", 2]];

// Only change code below this line
const removedFromMyArray = myArray.pop()
```
46. Manipulate Arrays With shift()
```
// Setup
const myArray = [["John", 23], ["dog", 3]];

// Only change code below this line
const removedFromMyArray = myArray.shift()
```
47. Manipulate Arrays With unshift()
```
// Setup
const myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line
myArray.unshift(["Paul", 35]);
```
48. Shopping List
```
const myList = [["bread", 2], ["water", 3], ["fish", 5], ["milk", 4],["eggs", 10]]
```
49. Write Reusable JavaScript with Functions
```
function reusableFunction (){
  console.log ("Hi World");
}
reusableFunction()
```
50. Passing Values to Functions with Arguments
```
function functionWithArgs(x, y){
console.log(x + y);} 
functionWithArgs(10, 11);
```
51. Return a Value from a Function with Return
```
function timesFive (time) {
  return time * 5;
}
```
52. Global Scope and Functions
```
// Declare the myGlobal variable below this line
let myGlobal = 10;

function fun1() {
 oopsGlobal = 5;// Assign 5 to oopsGlobal Here
 }

// Only change code above this line

function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
```
53. Local Scope and Functions
```
function myLocalScope() {
  // Only change code below this line

  console.log('inside myLocalScope', myVar);
  const myVar = "two"
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);
```
54. Global vs. Local Scope in Functions
```
// Setup
const outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
const outerWear = "sweater"
  // Only change code above this line
  return outerWear;
}

myOutfit();
```
55. Understanding Undefined Value returned from a Function
```
// Setup
let sum = 0;

function addThree() {
  sum = sum + 3;
}

// Only change code below this line
function addFive() {
  sum = sum + 5;
}

// Only change code above this line

addThree();
addFive();
```
56. Assignment with a Returned Value
```
// Setup
let processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
processed = processArg(7);
```
57. Stand in Line
```
function nextInLine(arr, item) {
  // Only change code below this line
 arr.push(item);
 let removed = arr.shift();
 return removed;
 
  // Only change code above this line
}

// Setup
const testArr = [1, 2, 3, 4, 5];

// Display code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6));
console.log("After: " + JSON.stringify(testArr));
```
58. Understanding Boolean Values
```
function welcomeToBooleans() {
  // Only change code below this line

  return true; // Change this line

  // Only change code above this line
}
```
59. Use Conditional Logic with If Statements
```
function trueOrFalse(wasThatTrue) {
  // Only change code below this line
if (wasThatTrue){
  return "Yes, that was true";
}
return "No, that was false";

  // Only change code above this line

}
```
60. Comparison with the Equality Operator
```
// Setup
function testEqual(val) {
  if (val==12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testEqual(10);
```
61. Comparison with the Strict Equality Operator
```
// Setup
function testStrict(val) {
  if (val===7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);
```
62. Practice comparing different values
```
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

compareEquality(10, "10");
```
63. Comparison with the Inequality Operator
```
// Setup
function testNotEqual(val) {
  if (val!=99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testNotEqual(10);
```
64. Comparison with the Strict Inequality Operator
```
// Setup
function testStrictNotEqual(val) {
  if (val!==17) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testStrictNotEqual(10);
```
65. Comparison with the Greater Than Operator
```
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }

  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

testGreaterThan(10);
```
66. Comparison with the Greater Than Or Equal To Operator
```
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }

  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

testGreaterOrEqual(10);
```
67. Comparison with the Less Than Operator
```
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }

  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

testLessThan(10);
```
68. Comparison with the Less Than Or Equal To Operator
```
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }

  if (val <=24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

testLessOrEqual(10);
```
69. Comparisons with the Logical And Operator
```
function testLogicalAnd(val) {
  // Only change code below this line

  if (val <= 50 && val >= 25) {
      return "Yes";
  
  }

  // Only change code above this line
  return "No";
}

testLogicalAnd(10);
```
70. Comparisons with the Logical Or Operator
```
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20) {
    return "Outside";
  }
  // Only change code above this line
  return "Inside";
}

testLogicalOr(15);
```
71. Introducing Else Statements
```
function testElse(val) {
  let result = "";
  // Only change code below this line

  if (val > 5) {
    result = "Bigger than 5";
  } else {
    result = "5 or Smaller";
  }

  // Only change code above this line
  return result;
}

testElse(4);
```
72. Introducing Else If Statements
```
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }

  else if (val < 5) {
    return "Smaller than 5";
  } else {
  return "Between 5 and 10";
}
}
testElseIf(7);
```
73. Logical Order in If Else Statements
```
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

orderMyLogic(7);
```
74. Chaining If Else Statements
```
function testSize(num) {
  // Only change code below this line
if (num < 5) {
  return "Tiny";
} else if (num < 10) {
  return "Small";
} else if (num < 15) {
  return "Medium";
} else if (num < 20) {
  return "Large";
} else (num >= 20); {
  return "Huge";
}
  // Only change code above this line
}
testSize(7);
```
75. Golf Code
```
const names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];

function golfScore(par, strokes) {
  // Only change code below this line
if (strokes === 1) {
  return "Hole-in-one!";
}
else if (strokes <= (par -2)) {
  return "Eagle";
}
else if (strokes=== (par - 1)) {
  return "Birdie";
}
else if (strokes===par) {
  return "Par";
}
else if (strokes===(par+1)) {
  return "Bogey";
}
else if (strokes=== (par + 2)) {
  return "Double Bogey";
}
else (strokes>= (par + 3)); {
  return "Go Home!";
}
  // Only change code above this line
}
golfScore(5, 4);
```


