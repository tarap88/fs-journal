# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > | Asynchronous code the tasks can be started and finished independently while in Synchronous code the tasks have to be done one after the other in the order it appears in. |

02. What is an event listener?

    | A function or a piece of code that waits for and responds to specific events that happen within an application. 
  <!-- JavaScript can be used to register event listeners to respond to user actions like mouse clicks, keyboard presses, or changes in the state of the webpage.| -->

03. What does *REST* stand for, and in simple terms what does it mean??

  > |  Representational State Transfer, REST is used for designing networked applications specifically web services. 
<!-- REST is like ordering food in a restaurant: you tell the server what you want, they take your request, and the kitchen prepares your food accordingly. Each order is independent, and the restaurant doesn't keep track of your past orders. This simplicity and standard way of ordering make it easy for both you (the client) and the restaurant (the server) to interact smoothly.  | -->

04. What is a callback / higher order function?

  > | Callback function is a function that is passed as an argument to another function and is expected to be called when a certain event occurs or when the parent function completes its task. it's a way to specify what should happen after a particular task is done.
  <!-- commonly used in asynchronous programming, event handling -->
   A higher-order function is a function that either takes another function as an argument or returns a function as its result (or both).
   <!-- For example, in JavaScript, map(), filter(), and reduce() are higher-order functions that take another function (callback) as an argument and apply it to each element of an array.| -->

05. What is a `promise`? How do you capture an error from a `promise`?

  > | A promise is an object representing the eventual completion or failure of an asynchronous operation. It allows you to handle asynchronous operations more easily and gracefully compared to traditional callback-based approaches. Promises are commonly used in JavaScript for handling asynchronous tasks like fetching data from a server, reading files, or waiting for a timer to finish. 
  <!-- 3 states: Pending: Initial state, neither fulfilled nor rejected. -->
<!--   Fulfilled: The operation completed successfully. -->
<!--   Rejected: The operation failed.  -->
   You catch an error using the .catch() |

06. Name three processes used to make requests over `HTTP`?

  > | HTTP GET, HTTP POST, and HTTP PUT.
  <!-- Other common HTTP methods include DELETE, PATCH, HEAD, OPTIONS  | -->

07. What does the `API` acronym stand for?

  > |Application Programming Interface.
   <!-- API is basically like the buttons and displays on a vending machine that let you interact with it, but in the context of software, it's a set of rules and tools that let one program use the functions and data of another program.  -->
  |

08. What must you do in order to `await` a promise inside of a function?

  > | Mark the function itself as async. This allows you to use the await keyword within the function to pause execution until the promise is settled (either fulfilled or rejected). 
  <!-- This tells JavaScript that the function contains asynchronous code and may use the await keyword to pause execution until promises are settled.| -->

09. What is the purpose of encapsulation in programming?

  > | The purpose of encapsulation in programming is to bundle data (variables) and the methods (functions) that operate on that data into a single unit, called a class in object-oriented programming (OOP), or a module in other programming paradigms. |
  <!-- Encapsulation is like putting your data in a treasure chest, locking it up, and only giving the key to trusted methods/functions. This keeps your data safe, organized, and secure, making your code easier to manage and less prone to problems. -->

10. What is `HTTP` response code for a successful request?

  > | '200 OK.' |

11. What is a 400 error?

  > | HTTP status code that indicates the server cannot process the client's request due to invalid syntax or malformed request structure. |
  <!-- In simpler terms, a 400 Bad Request error occurs when the server cannot understand the request sent by the client because the request is incorrect or improperly formatted.  -->
