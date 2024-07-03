# JavaScript

![29](https://wpengine.com/wp-content/uploads/2021/07/jsheader-1024x535.png)

                                                                 
                                                                 


## Table of contents##

1. What Is javascript?
2.  How to Set Up VsCode?
3.  What can Javascript do?
4.  What makes Javascript unique?
5.  How to use Javascript with HTML?
6.  HOW to use internal Javascript?
7.  How to use external Javascript?
8.  Functions in Javascript.
9.  important funtions of Javascript.
10.  Variable in Javascript.
11.  Scope and Lite time of a variablethe HTML Element.
12. DOM(Document Object Method) . 
13.  What is an Operator and Type of Operators in Js.
14. String Concatenation in Javascript.
15. Array in Javascript.
16. Conditional Statement in Javascript.
17. Types of Conditional Statements in Javascipt.
 18. Event Handling in Javascript.   
 19. Loop in Javascript.
    

# 1.  What Is javascript

> Javascript is an interpreted, client-side, event based, object-oritented scripting language.
> 
> Invented in 1995 at Netscape Corporation(Livescript).
> 
> Javascript programs are run by an interpreter built into the user's web browser.
> 
> It is a case-sensitive language.




# 2.  How to Set Up VsCode

- Step 1:- Search on Google or Chrome Download VsCode.
- Step 2:- click on the first link.
  
  - VsCode Download :-
  ![vs](https://code.visualstudio.com/assets/updates/1_68/vscode-dev-download.png)



- Step 3:- After completion VS Code, Check your download Folder.
- Step 4:- Open Terminal in Linux or  for shortcut click (ctrl + alt + t)
- Step 5:- Check if the system up-to-date using following command :

    
                $ sudo apt-get update
- Step 6. After update system Now you can Install VS Code using the following command:

  
           $ sudo apt install vscode 

- Step 6. Open VS Code.          


![1](https://code.visualstudio.com/assets/updates/1_68/translations-core.png)

- Step 6:- Create a new file.

 
![30](https://media.dev.to/cdn-cgi/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fjxnhb4rnchxhywu05f7a.gif)
<br>

# 3.  What can Javascript do?

> Javascript can dynamically modify and HTML page.
>
> Javascript can vaildate user input Javascript can vaildate user input.
>
> Javascript can be used to create cookies.
>
> Javascript is a full-featured programming language.
>
> Javascript user interaction does not require any communication with the server.


# 4. What makes Javascript unique?

> Support by all major browsers and enabled by default.
>
> Complex things are done simply.
>
> Full intergration with HTML/CSS.


# 5. How to use Javascript with HTML?

>You can add JavaScript code in an HTML document by employing the dedicated HTML tag <script> that wraps around JavaScript code.
>
>The <script> tag can be placed in the <head> section of your HTML or in the <body> section, depending on when you want the JavaScript to load.
>
>Generally, JavaScript code can go inside the document <head> section in order to keep it contained and out of the main content of your HTML document.
>
>However, if your script needs to run at a certain point within a page’s layout when using document.write() to generate content, you should put it at the point where it should be called, usually within the <body> section.

# 6. HOW to use internal Javascript?

> Javascript can be inserted into documents by using the SCRIPT tag.
>
> The SCRIPT tag provides a block to write the Javascript programs.
>
  ```js
  <script type = "text/javascript">
  //js code goes here
  <script>
  ```



# 7. How to use external Javascript?

   To use the pre-defined programs of any Javascript library.

  ```js
  <script scr = "myscript.js"></script>
  ```



  # 8. Functions in Javascript
  
>**Function**
> Functions are group of code or program which is used more often.
>It leads programming to code resusability and clear code.
>
>
>**Types**
>1. Pre defined Function.
>2. User defined Function.
>
>
**1.Pre defined Function**.
>:- Such functions one defined at the time of making of any language.


**2.User defined Function**.
>:- Such function are defined by users according to their needs.




   # 9. important funtions of Javascript.
   
>1. alert() function
>2. confirm() function
>3. console.log() function
>4. document.write() function
>5. prompt() function
> 

**alert() functioin**
* It is used to alert the user that something has happened.
  
  ```js
     <script type = "text/javascript">
       alert("Welcome to Ws cube");
     </script>
  ```

**confirm() function**
  
* Opens up a confirm/cancel dialog and returns true/ false depending on user's click.


**console.log()**
* Writes information to the browser console, good for debugging purposos.

  ```js
  <script type> = "text/javascript">
  
  console.log("Wscube javascript tutorials");
  ```
**document.write() function**
  
* document.write(): write directly to the HTML document.
  
  ```js
  <script type ="text/javascript">
    
  document.write("Wscube Tech");
    
  </script>
  ```

**Prompt() function**

Prompt(msg,default): create an dialogue for user input.

  ```js
  <script type ="text/javascript">
    prompt("hello","Wscube");
  </script>
  ```



    
 # 10. Variable in Javascript

**What is a Variable**
Variables are Containers which hold reusable data.
It is the basic unit of storage in program.
The value stored in a variable can be changed during program execution.




# 11. Scope and Lite time of a variable

**Scope of a variable**
>*Variables declared within a function are local to that function.
>*Variables declared outside of any function are global variables.


**Life time of a variable**
>*Local variable's life time is within the block of it's declaration.
>*Global variable's life time is throughtout the program.




# 12. DOM(Document Object Method)

> When a web page is loaded, the browser creates a Document Object Model (DOM)of the page.

> 
## Selecting with id
- document.getElementById(“myld")
  
## Selecting with class
- document.getElementsByClass Name("myclass)
  
## Selecting with tag
- document.getElementsByTagName(“p”)

## Properties
-  tagName : returns tag for element nodes
- innerText : returns the text content of the element and all its children
- innerHTML : returns the plain text or HTML contents in the element  
- textContent : returns textual content even for hidden elements. 




# 13.  What is an Operator and Type of Operators in Js

**Operator**
> :- An operator is a symbol that tell the compiler which arithmetic or logical operation to be performed between the respective operands.



**Types**
>1. Arithmetic Operators.
>2. Logical Operators.
>3. Ternary Operators.
>4. Assignment Operators.
>5. Comparison / Relational Operators.
>
>
**1. Artithmetic Operators**.
>Javascript arithmetic operators are used to perform mathematical calculations between variables and/or values.
>These include addition (+), subtraction (-), multiplication (*), division (/), modulus (%), increment (++), and decrement (--).



**2. Logical Operators.**
>An operator that performs a logic operation on nodes, groups, or numbers.
> AHDL logical operators are NOT ( ! ), AND ( & ), NAND ( !& ), OR ( # ), NOR ( !# ), XOR ( $ ), and XNOR ( !$ ).



**3. Ternary Operators**.
>An alternative to the if/else statement, the ternary operator allows JavaScript developers to write concise conditional statements.
> It is written as “?:” and takes three operands; a logical condition, a value to return if true, and a value to return if false.



**4. Assignment Operators.**.
>An assignment operator assigns a value to its left operand based on the value of its right operand.
> The simple assignment operator is equal ( = ), which assigns the value of its right operand to its left operand.



**5. Comparison / Relational Operators.**
>Relational operators compare two operands and return true or false depending on the validity of the comparison.
>The most common relational operators are: > (greater than) < (less than)




# 14. String Concatenation in Javascript
>There are four methods in JavaScript for string concatenation: using the concat() method, using the '+' operator, using the array join() method, and using template literals.




# 15. Array in Javascript

> In JavaScript, an array is a variable that can hold multiple values, each accessed by an index number starting from 0.

>Example:

>javascript copy code
// Define an array with some values
let fruits = ["Apple", "Banana", "Cherry"];

// Accessing array elements using their index
console.log(fruits[0]); // Outputs: Apple
console.log(fruits[1]); // Outputs: Banana
console.log(fruits[2]); // Outputs: Cherry
In this example, fruits[0] accesses "Apple", fruits[1] accesses "Banana", and fruits[2] accesses "Cherry".


# 16. Conditional Statement in Javascript

**What are Conditional Statement**
> Coditional Statements(Control Statements) used to change the flow of the Program's execution.



# 17. Types of Conditional Statements in Javascipt
 
**If**
>:- If proved true, performs a function or displays information.

**If-else**
>:- It proved true, performs a task.
>If false performs any other task.

**If-elseif**
>:- If proved true, performs a task.
>If false checks another if condition.




# 18.Event Handling in Javascript   

**Event Handling**
> When an event, consider pressing a keyboard key or clicking an element, occurs on a DOM or an HTML element, we can call the specific functions based on these events. Now, how does the HTML element know when to call the mentioned JavaScript code or JavaScript function? This is taken care of by the event handlers. The properties of DOM or HTML elements are called event handlers to control how an element should respond to a given event.

**event-and-event-handlers**

> As shown in the above figure, when a user clicks a specific mouse button or types a specific keyword into the browser, that action activates the corresponding event handler for that HTML  element. The browser then shows the end users the effects of the actions that were carried out on the webpage by the JavaScript code that was executed by the event handler.

Event handlers can be assigned directly using the equal (=) operator because they are attributes of HTML/DOM elements as well. The syntax is as follows:

**Syntax:**

name_of_EventHandler = "The javaScript code / function which is required to be execute






  # 19. LOOP IN JS
 
  **Loop**
> Loops are handy, if you want to run the same code over and over again, each time with a different value.
>
> **Types of Loop**
  1. for Loop 
  2. while Loops
  3. do-while loop
  4. for-of Loop
  5. for-in   

## for Loop
   {
           
           for (int i = 1; i <= 5; i++) 
            console.log("Hello world");
            
   } 
   # Output 
   Hello world
   Hello world
   Hello world
   Hello world
   Hello world
   

 ## Infinite Loop:- 
-  A Loop that never ends.
  
  ## while Loop:-
                while (condition) {
                // do some work
                     }
                     
## Program              
while (i < 10) {
  text += "The number is " + i;
  i++;
}
 ## output
while Loop
The number is 0
The number is 1
The number is 2
The number is 3
The number is 4
The number is 5
The number is 6
The number is 7
The number is 8
The number is 9

## do-while Loop

         do{
          //do some work
         }while(condition);
         
## Program              
let text = "";
let i = 0;
do {
  text += i + "<br>";
  i++;
}
 ## output
 do-while Loop
>* 0
>* 1
>2
>3
>4   

## for-of Loop
           for (let key in objVar) {
           //do some work
             }
## Program              
const cars = ["BMW", "Volvo", "Mini"];

let text = "";
for (let x of cars) {
  text += x;
}
 ## output
 The for of statement loops through the values of any iterable object:

BMW
Volvo
Mini
## for-in Loop
              for (let key in objVar) {
                //do some work
                 }         
## Program              
const person = {fname:"John", lname:"Doe", age:25};

let text = "";
for (let x in person) {
  text += person[x];
}
 ## output
The for in statement loops through the properties of an object:

John Doe 25

 ## Conclusion
In this project, we successfully built a simple yet functional calculator using HTML, CSS, and JavaScript. 
This exercise not only demonstrated the power of combining these three technologies but also emphasized key programming concepts such as:



  # Thank you!
            .  







