# JavaScript

![29](https://wpengine.com/wp-content/uploads/2021/07/jsheader-1024x535.png)

                                                                 
                                                                 


## Table of contents

1. What Is javascript
2.  How to Set Up VsCode
3.  What can Javascript do
4.  What makes Javascript unique
5.  How to use Javascript with HTML
6.  HOW to use internal Javascript
7.  How to use external Javascript
8.  Functions in Javascript
9.  important functions of Javascript
10.  Variable in Javascript
11. What is an Operator and Type of Operators in Js
12. String Concatenation in Javascript
13. Array in Javascript
14. Event Handling in Javascript 
15. Loop in Javascript
    

# 1.  What Is javascript

- JavaScript is a scripting or programming language that allows you to implement complex features on web pages.
- Invented in 1995 at Netscape Corporation.

- It is a case-sensitive language.


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
- **Interact with Users**: It can respond to user actions like clicking buttons, filling out forms, or moving the mouse. This makes websites interactive, allowing things like dropdown menus, image sliders, and games.
  
- **Update Web Pages**: JavaScript can change the text, images, and layout of a web page without needing to reload the whole page.*
  
- **Form Validation**: JavaScript can check data in forms to ensure correct and complete information is submitted.
  
- **Responsive Design**: JavaScript can adjust the page layout based on screen size or device, making the website look good on both mobile and desktop.

# 4. How to use Javascript with HTML?

   Using the <script> tag integrates JavaScripts into an HTML page .this tag allows to directly write JavaScripts code within your HTML file.
      
# 5. HOW to use internal Javascript?

**Internal JavaScript**: Code is written directly within an HTML file, inside the <script> tags.

  ```js
  <script type = "text/javascript">
  //js code goes here
  <script>
  ```

# 6. How to use external Javascript?
 **External JavaScript**: Code is written in a separate .js file and linked to an HTML file using the <script> tag with the src attribute. 

  ```js
  <script scr = "myscript.js"></script>
  ```

# 8. Functions in Javascript
  
>**Function**
>:- Functions are group of code or program which is used more often.
>It leads programming to code resusability and clear code.

>**Types**
>1. Pre defined Function.
>2. User defined Function.

**1.Pre defined Function**.
>:- Such functions one defined at the time of making of any language.

```bash
console.log("Hello Wrold");
```

**2.User defined Function**.
>:- Such function are defined by users according to their needs.
## Example

```bash
function greetUser(name) {
    console.log("Hello, " + name + "!");
}


greetUser("Muskan"); 

```
## Output
Output: Hello, Muskan!

# 9. important functions of Javascript.
   
>1. alert() function
>2. confirm() function
>3. console.log() function
>4. document.write() function
>5. prompt() function
> 

**alert() function**
* It is used to alert the user that something has happened.
  
 ```js
     <script type = "text/javascript">
       alert("Hello wrold");
     </script>
 ```

**console.log()**
* Writes information to the browser console, good for debugging purposos.

 ```js
  <script type> = "text/javascript">
  
  console.log("Hello World");

</script>

 ```
**document.write() function**
  
* document.write(): write directly to the HTML document.
  
```js
  <script type ="text/javascript">
    
  document.write("Hello World");
    
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

**Example**

```bash
let a=5;
console.log(a);
```

## Output
5



# 11.  What is an Operator and Type of Operators in Js

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



**2. Assignment Operators.**.
>An assignment operator assigns a value to its left operand based on the value of its right operand.
> The simple assignment operator is equal ( = ), which assigns the value of its right operand to its left operand.



**4. Comparison / Relational Operators.**
>Relational operators compare two operands and return true or false depending on the validity of the comparison.
>The most common relational operators are: > (greater than) < (less than)




# 12. String Concatenation in Javascript

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


## 13. Array in javascripts

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




# 16.Event Handling in Javascript   
- Event handling in JavaScript involves attaching event listeners to DOM elements to respond to various events. Here’s the syntax and an example for event handling:
- Syntax
``` bash
element.addEventListener(event, function);
```

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
# 17. LOOP IN JS
 
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
# Thank You!






