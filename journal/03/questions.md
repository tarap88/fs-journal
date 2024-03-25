# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | Encapsulation, Inheritance, Polymorphism, and Abstraction |

02. How does `export` differ from `export default`?
  
  > | Export us used to share multiple things like (variables, functions, classes, etc.) from a file with other files, you have to use the specified name though while Export Default is used to share one main thing from a file and doesn't need a specific name and when it is used you can name it anything you want.|

03. What is Encapsulation?
  
  > | Encapsulation is the bundling of data and the methods that act on that data such that access to that data is restricted from outside the bundle, or as Alan Kay describes it, “local retention and protection and hiding of state-process.” In OOP, that means that an object stores its state privately, and only the object’s methods have access to change it.
    --It is fundamental in OOP. Essentially it means keeping some info safe inside an object and only allowing certain methods to access or change it which then helps keep the data organized, secure, and prevents it from being messed up.   |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?

  > | The Proxy object in JavaScript provides a powerful way to control and manipulate the behavior of objects. Some benefits include Meta-Programming, Validation and Security, Dynamic Property Handling, and Debugging.|Proxies are Middleware for Javascript Objects.

05. What the difference between a `class` and an instance of a `class`?
  
  > | A Class is the blueprint for creating objects because it defines the properties(attributes) and behaviors (methods) that objects of that class will have. 
  An  Instance of a Class ala object of a class is a specific occurrence of that class. It's created based on the blueprint defined by the class and it encloses its own set of data(state) and behavior (methods) as defined by the class. |
  <!-- A class is like a recipe that describes how to make something. It lists all the ingredients (properties) needed and the steps (methods) to follow. It's a plan for creating multiple similar things.
  
  An instance of a class is like one actual thing made using the recipe. It's a real sandwich created following the instructions in the recipe. Each sandwich can have its own unique ingredients and can be eaten separately. -->

06. What is a computed Property?
  
  > a computed property is like a special function attached to an object that automatically recalculates its value whenever one of its dependent properties changes.|


07. What is the purpose of the `MVC` pattern?
  
  > | Provide a structured and organized way to design and develop software applications, specifically user interface-driven applications such as web applications. 
  Model, View, and Controller. |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | It's in charge of handling user input, updating the Model accordingly, and then deciding which View to display.
  The Controller is like a traffic director that handles user input, processes requests, and coordinates interactions between the Mod |

09. What is the job of the `Service` in `MVC`?
  
  > | Used to handle business logic, data manipulation, and communication with external systems or resources.|

10. What is the job of the `Model` in `MVC`?
  
  > | Plays a central role in representing the data and business logic of an application. Essentially is the brain and the heart of the application.|
