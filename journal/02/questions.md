# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | Const, Let and Var |

02. What is the definition of a function?

    > | A function is a subprogram designed to perform a particular task. They always return a value, if no return is specified then it returns undefined. Functions are objects and usually will have a function name in front of it followed by parentheses to set parameters.|

03. What are the `SOLID` principles?

    > | Single Responsibility Principle, Open-Closed Principle, Liskov Substitution Principle, Interface Segregation Principle, and Dependency Inversion Principle. SOLID is an acronym five for design principles intended to make object-oriented designs more understandable, flexible, and maintainable. |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | delete fruit[2];| 
    <!-- Google and AI said something about using splice or filter but I wasnt sure how to do that. -->

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | No clue, my brain is fried |

06. Give an example of a JavaScript `Conditional`:

    > | Conditionals let you do different parts of code based off the "if" or "if else" or "if else if" conditions. 
    Let age = 18;
    if (age >= 30) {
        console.log('You are old');
    } else console.log{ (You are young);
        
    }
<!-- You arent actually old if you are older than 30 haha -->
    |

07. What is the main difference between `parameters` and `arguments`?

    > | Parameters are variables that are part of a function whereas arguments are the actual values passed to a function when it is called.|

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | The debugger is a great way to debug because it pauses where there is an error. |

09. What is the difference between a `primitive` value and a `reference` value?

    > | Primitive values cant be changed, they are stored directly and are accessed by their value, the sic types of primitive are string, number, boolean, null, undefined, and symbol. Reference values can be changed, they are stored as references to their actual data. Reference examples are objects, arrays, functions, etc. |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for (i = -100; i <= 100; i++) {
        console.log(i)}|
