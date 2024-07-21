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
9.  important functions of Javascript.
10.  Variable in Javascript.
11.  Scope and Lite time of a variable the HTML Element.
12. DOM(Document Object Method) . 
13.  What is an Operator and Type of Operators in Js.
14. String Concatenation in Javascript.
15. Array in Javascript.
16. Conditional Statement in Javascript.
17. Types of Conditional Statements in Javascipt.
 18. Event Handling in Javascript.   
 19. Loop in Javascript.
    

# 1.  What Is javascript

 - Javascript is an interpreted, client-side, event based, object-oritented scripting language.
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


- Step 3:- Select debian package for linux system.
- Step 4:- After completion VS Code, Check your download Folder.
- Step 5- Open Terminal in Linux or  for shortcut click (ctrl + alt + t)
- Step 6:- Check if the system up-to-date using following command :

    
                $ sudo apt-get update
- Step 6. After update system Now you can Install VS Code using the following command:

  
           $ sudo dpkg -i vscode_package(Downlaoded)

- Step 6. Open VS Code.          


![1](https://code.visualstudio.com/assets/updates/1_68/translations-core.png)

- Step 6:- Create a new file.

 
![30](https://media.dev.to/cdn-cgi/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fjxnhb4rnchxhywu05f7a.gif)
<br>

# 3.  What can Javascript do?
**Interact with Users**: It can respond to user actions like clicking buttons, filling out forms, or moving the mouse. This makes websites interactive, allowing things like dropdown menus, image sliders, and games.
**Update Web Pages**: JavaScript can change the text, images, and layout of a web page without needing to reload the whole page.*
**Form Validation**: JavaScript can check data in forms to ensure correct and complete information is submitted.
**Responsive Design**: JavaScript can adjust the page layout based on screen size or device, making the website look good on both mobile and desktop.

# 4. How to use Javascript with HTML?
**Include JavaScript in HTML**: You can write JavaScript code directly inside an HTML file using the <script> tag.

**Place the JavaScript Code**: Insert your JavaScript code between the <script> tags, usually inside the <body> section.

# 5. HOW to use internal Javascript?

> Javascript can be inserted into documents by using the SCRIPT tag.
>
> The SCRIPT tag provides a block to write the Javascript programs.
>
  ```js
  <script type = "text/javascript">
  //js code goes here
  <script>
  ```



# 6. How to use external Javascript?

   To use the pre-defined programs of any Javascript library.

  ```js
  <script scr = "myscript.js"></script>
  ```



# 7. Functions in Javascript
  
>**Function**
> Functions are group of code or program which is used more often.
>It leads programming to code resusability and clear code.

>**Types**
>1. Pre defined Function.
>2. User defined Function.

**1.Pre defined Function**.
>:- Such functions one defined at the time of making of any language.


**2.User defined Function**.
>:- Such function are defined by users according to their needs.




# 8. important functions of Javascript.
   
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



    
 # 9. Variable in Javascript

**What is a Variable**
Variables are Containers which hold reusable data.
It is the basic unit of storage in program.
The value stored in a variable can be changed during program execution.




# 10. Scope and Lite time of a variable

**Scope of a variable**
>*Variables declared within a function are local to that function.
>*Variables declared outside of any function are global variables.


**Life time of a variable**
>*Local variable's life time is within the block of it's declaration.
>*Global variable's life time is throughtout the program.




# 11. DOM(Document Object Method)

> When a web page is loaded, the browser creates a Document Object Model (DOM)of the page.


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




# 12.  What is an Operator and Type of Operators in Js

**Operator**
> :- An operator is a symbol that tell the compiler which arithmetic or logical operation to be performed between the respective operands.



**Types**
>1. Arithmetic Operators.
>2. Logical Operators.
>3. Assignment Operators.
>4. Comparison / Relational Operators.

**1. Artithmetic Operators**.
>Javascript arithmetic operators are used to perform mathematical calculations between variables and/or values.
>These include addition (+), subtraction (-), multiplication (*), division (/), modulus (%), increment (++), and decrement (--).



**2. Logical Operators.**
>An operator that performs a logic operation on nodes, groups, or numbers.
> AHDL logical operators are NOT ( ! ), AND ( & ), NAND ( !& ), OR ( # ), NOR ( !# ), XOR ( $ ), and XNOR ( !$ ).


**3. Assignment Operators.**.
>An assignment operator assigns a value to its left operand based on the value of its right operand.
> The simple assignment operator is equal ( = ), which assigns the value of its right operand to its left operand.



**4. Comparison / Relational Operators.**
>Relational operators compare two operands and return true or false depending on the validity of the comparison.
>The most common relational operators are: > (greater than) < (less than)




# 13. String Concatenation in Javascript

- String concatenation in JavaScript is the process of combining two or more strings into one. This can be done using the + operator or template literals.
   ## Example
  
```bash
let firstName = 'Muskan';
let lastName = 'Thakur';
let fullName = firstName + ' ' + lastName;
console.log(fullName);
```




## Output

Muskan Thakur


## 14. Array in javascripts

- In JavaScript, an array is a variable that can hold multiple values, each accessed by an index number starting from 0.

# Example:

```bash
let fruits = ["Apple", "Banana", "Cherry"];

console.log(fruits[0]); 
console.log(fruits[1]);
console.log(fruits[2]); 

```
## Output
 Apple
 Banana
 Cherry


# 15. Conditional Statement in Javascript

**What are Conditional Statement**
> Coditional Statements(Control Statements) used to change the flow of the Program's execution.



# 16. Types of Conditional Statements in Javascipt
 
**If**
>:- If proved true, performs a function or displays information.

**If-else**
>:- It proved true, performs a task.
>If false performs any other task.

**If-elseif**
>:- If proved true, performs a task.
>If false checks another if condition.




# 17.Event Handling in Javascript   
- Event handling in JavaScript involves attaching event listeners to DOM elements to respond to various events. Here’s the syntax and an example for event handling:
- Syntax
``` bash
element.addEventListener(event, function);
```
- element: The DOM element to which the event listener is attached.
- event: A string representing the event type ( 'click', 'mouseover').
- function: The function to be called when the event occurs.
 ## Example
## HTML
```bash
<body>
  <button id="myButton">Click Me!</button>

  <script src="script.js"></script>
</body>
```
## JavaScript (script.js)
```bash
const button = document.getElementById('myButton');


function handleClick() {
  alert('Button was clicked!');
}

button.addEventListener('click', handleClick);

```
  # 18. LOOP IN JS
 
  **Loop**
> Loops are handy, if you want to run the same code over and over again, each time with a different value.
>
> **Types of Loop**
  1. for Loop
  2. Infinite Loop
  3. while Loop
  4. do-while loop
  
## for Loop
 ```bash
    let i =1;
   for (int i = 1; i <= 5; i++) 
     {
       console.log("Hello world");
     }
   ```
   # Output 
   Hello world
   Hello world
   Hello world
   Hello world
   Hello world
   

 ## Infinite Loop:- 
 ```bash
  while (true) {
    console.log("This will print forever");
}
```
  ## Output
  This loop will run indefinitely, continuously printing the message to the console.
  
  ## while Loop:-
                while (condition) {
                // do some work
                     }
                     
## Program              
```bash
let count = 1;

while (count <= 5)
{
  console.log(count);
  count++;
}
```
## output
1 2 3 4 5

## do-while Loop

         do{
          //do some work
         }while(condition);
         
## Program              
```bash

let count = 1;


do {
  console.log(count);
  count++;
} while (count <= 5);

```
## output
1 2 3 4 5 
 ## Conclusion
In this project, we successfully built a simple yet functional calculator using HTML, CSS, and JavaScript. 
This exercise not only demonstrated the power of combining these three technologies but also emphasized key programming concepts such as:

# Reference link
https://www.w3schools.com/js/
            .  







