Backend & JavaScript Assignment

Intro to Backend • Variables • Datatypes • Coding

Section A — Intro to Backend (Theory: 12 Questions)

1.What is backend development and how is it different from frontend development?

Answer: Backend development refers to the server-side of an application. This is where developers handle the logic, databases and core infrastructure that the user doesn't see. They write code that tells the website how to bring the frontend programming languages to life. Backend development is different from frontend development as backend is focused on the server side using languages like (Javascript)node.js, Python, and Java, while the frontend is focused on the the side the user sees, the client side of things like designs, the layouts, dropdown menus, etc, using programming languages like HTML, Javascript and CSS.

2.Mention three backend programming languages.

Answer: Node.js, Java, and PHP.

3.What is a server? Explain its role in backend development.

Answer: A server is a computer or application that receives and processes requests transmitted over a network, providing appropriate responses. The device that receives and processes the request from the client is called the server. In backend development, its primary role is to act as a central hub for an application, receiving client requests processing them by interacting with application logic and databases, and then sending back responses.

4.Define an API and explain its purpose.

Answer: An API in full means Application Programming Interface and it is a set of rules or protocols that define how different software applications can communicate with each other.


5.What is a database and why is it important in backend systems?

Answer:A database is an organized collection of data, typically stored electronically, that is designed for easy access, management, and updating. Without a backend database, an application wouldn’t be able to store, manage, or protect data. Backend databases provide a central location for storing data, securing it, scaling it and also keeping the information consistent across users.

6.List two differences between SQL and NoSQL databases.

Answer:Data structure
SQL databases store data in fixed, structured tables with rows and columns.
NoSQL databases store data in flexible formats like documents, key-value pairs, wide columns, or graphs.
Schema
SQL databases require a predefined schema before inserting data.
NoSQL databases are schema-less or schema-flexible, letting you store data without defining strict structure in advance.

7.What is a backend framework? Mention one example.

Answer:A backend framework is a set of tools and pre-written code that helps developers build the server-side of a web application more efficiently. It provides a structured way to handle common tasks like routing, database interactions, and user authentication, allowing developers to focus on building core functionality instead of writing repetitive "plumbing" code from scratch.
 
8.Explain what HTTP is and why it is important.

Answer: The Hypertext Transfer Protocol (HTTP) is the foundational protocol that enables data communication on the World Wide Web. It functions as a set of rules for how clients (like web browsers) and servers communicate to exchange various types of data, such as HTML documents, images, and videos. 


9.Mention two responsibilities of a backend developer.

Answer: A backend developer is responsible for building and maintaining the server-side of web applications, including the logic, databases, and APIs that power the user-facing front end. Their key duties include writing and debugging code, managing databases, ensuring application security, optimizing performance, and collaborating with other developers to ensure a functional and cohesive application. 

10.What does CRUD stand for? Explain each word.

Answer: CRUD is an acronym for Create, Read, Update, and Delete, the four basic operations used to manipulate persistent data in databases and applications.

Create: This adds new data to a system. For example, creating a new user account, uploading a photo, or adding a new product to an e-commerce store. 
Read: This retrieves or views existing data without changing it. Examples include searching for a product, viewing a user profile, or generating a report. 
Update: This modifies existing data. This could involve editing a user's profile information, changing a password, or updating an inventory count. 
Delete: This removes data from the system. This is often done when a user account is closed or a product is discontinued, though it can sometimes involve a "soft delete" where the data is marked as deleted instead of being completely removed.

11.What is authentication and why is it important for backend applications?

Answers: Authentication is the process of verifying the identity of a user, system, or entity trying to access a backend application or system. It acts as a gatekeeper, ensuring that only legitimate and verified users are granted access to resources and data they are authorized to use.

12.What is the difference between a GET request and a POST request?

Answer: A GET request is used to retrieve data from a server. The data is sent through the URL, so it’s visible and mainly used for reading or fetching information.
A POST request is used to send data to a server. The data is included in the request body, not the URL, and it’s used for actions like creating accounts, submitting forms, or uploading information.

Section B — JavaScript Variables & Datatypes (Theory: 10 Questions)

1.What is a variable in JavaScript?

Answer: A variable is a named storage location used to hold data. It acts as a bucket or a container for different types of information, such as numbers, text (strings), or more complex data structures like objects and arrays.

2.List the three ways to declare variables in JavaScript.

Answer:The three ways to declare variables are:
1.var
2.let
3.const

3.Explain the difference between let and const.

Answer: The main difference between them is that let allows for a variable to be reassigned, while const creates a variable that cannot be reassigned. Both let and const are block-scoped, meaning they are restricted to the block in which they are declared, and const variables must be initialized when they are declared. 

4.Mention the seven primitive datatypes in JavaScript.

Answer:
1.Number
2.Boolean
3.String
4.Null
5.Undefined
6.Symbol

5.What datatype is assigned to the value: true?

Answer:This is assigned to the Boolean data type. This data type is used to represent logical values, which can only have one of two possible states: true or false. 

6.What datatype is a JavaScript array?

Answer: A javascript array is an object datatype.

7.Give one example of a string in JavaScript.

Answer: In JavaScript, a string is a sequence of characters used to represent text.

8.Give one example of a number in JavaScript.

Answer: An example of a number in JavaScript is 50. JavaScript has only one general type for numbers, which is the number type, used for both integers and floating-point numbers. 

9.What will be the output of this expression?

typeof "123"
Answer: The output would be "number". This typeof displays the datatype of a variable.

10.Explain the difference between null and undefined.

Answer:  Null represents the absence of any object value, though it is intentional. It is a value that must be assigned by a developer to a variable to signify that it currently holds no meaningful value, while undefined means the variable has been declared but has not been assigned a value.


Section C — Coding Questions (8 Questions)

1.Declare a variable using let and assign your name to it.

Answer: 
Let myName = "Bill";

2.Write JavaScript code to add two numbers and log the result.

Answer: 
const number1 = 28;
const number2 = 30;

const sum = number1 + number2;

console.log("The sum is: " + sum);

3.Create an object called student with properties: name, age, and department.

Answer: 
const student = {
  name: "Bill",
  age: 20,
  department: "Backend development"
};

4.Write a JavaScript function called greet() that prints "Hello World".

Answer: 
function greet() {
  console.log("Hello World");
}

5.Write a program that checks if a number is even or odd.

Answer: 
function checkEvenOrOdd(number) {
  if (number % 2 === 0) {
    return "Even";
  } else {
    return "Odd";
  }
}


6.Create an array of 5 colors and print the first color.

Answer: 
const colors = ["red", "green", "blue", "yellow", "purple"];
console.log(colors[0]);


7.Write a function that returns the square of a number passed into it.

Answer: function square(number) {
  return number * number;
}

8.Write a small code snippet that converts a string to a number:

let value = "42";
// convert to number here

let value = "42";

let num1 = Number(value);
console.log(num1); // Output: 42
