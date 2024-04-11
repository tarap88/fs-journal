# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create, Read, Update, and Delete representing the four main operations performed on data. CRUD is a foundational concept in computer programming, databases, and application design. 
  <!-- It's a basic way to understand what you can do with data in a computer system. You can create new data, read or view existing data, update or change data, and delete or remove data. It's like the essential toolkit for managing information in software. | -->

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | Create = Post, Read = Get, Update = Put, Delete = Delete  |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | ORM stands for Object-Relational Mapping. The orm we use when interacting with MongoDB is mongoose.| 

  <!-- Helps bridge the gap between programming languages and databases. When we work with MongoDB, Mongoose is a popular ORM tool. It helps us define how our data should look in our code and how it's stored in the MongoDB database, making it easier to work with MongoDB using JavaScript.-->

04. Which two `HTTP` request types include a body?

  > | Post and Put.|

  <!-- Examples:
  POST: Imagine you're filling out a job application online. When you hit the "submit" button, the information you entered (like your name, email, and qualifications) is sent to the company's server using a POST request. It's like mailing a letter with all your details to someone.

  PUT: Now, let's say you already have a profile on a job website, but you want to update your skills or contact information. You would use a PUT request to send the updated information to the website's server. It's like sending a revised version of your resume to the company, replacing the old one. -->


05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | 1. Synchronous 2. Asynchronous |

06. What are the three types of data relationships? Provide an example of each.

  > | One-to-One (1:1): Imagine you have a key and a locked box. Each key opens only one box, and each box has only one key. That's a one-to-one relationship. For instance, each person has only one unique social security number, and each social security number is linked to only one person.

One-to-Many (1:N): Picture a teacher and their students. A teacher can have many students, but each student has only one teacher. It's like a parent having multiple children, but each child has only one parent.

Many-to-Many (M:N): Think of a library where many books can be borrowed by many readers. Each book can be borrowed by multiple readers, and each reader can borrow multiple books. It's like a group of friends sharing their toys — each friend can play with multiple toys, and each toy can be played with by multiple friends. |

07. What is middleware?

  > | Middleware is software that acts as a bridge between different applications, systems, or components. It can be described as "software glue". It's like a layer of software that sits between different parts of a system and helps them communicate or interact with each other. |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | Request Pipeline |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | http://localhost:3000/api/jobs/?tag=winter OR 
  const response = await dbContext.jobs.find({"tag": "winter"})  |

10. What is a ***virtual property***?

  > | Virtual properties in JavaScript are like little helpers that allow you to create new properties based on existing values stored in an element or nearby elements. These "formulas" return a single value, either a string or a number, which becomes the value of the virtual property for that specific element. |

  <!-- For example, imagine you have a program that stores people's first names and last names. With a virtual property called "full name," you can ask the program, "Hey, what's this person's full name?" And even though the program doesn't have a stored value for "full name," it quickly combines the first name and last name and tells you the answer. It's like a handy shortcut for getting extra information without storing it all in the database. -->
