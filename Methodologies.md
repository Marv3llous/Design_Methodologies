There are three principle design strategies used in software engineering:

Structured design
Function oriented design
Object oriented design



## **What do we mean by coupling and cohesion when discussing structured design?**

In regards to structured design:

Coupling - refers to how dependant modules are of each other. If a design has high coupling it means that the modules are highly dependant on each other, if it has low coupling then they are less dependant.

Cohesion - Cohesoion is important in design. Low cohesion refers to loosely related elements, whereas high cohesion refers to the elements beig strongly related to each other. As developer we want high cohesion within a class so updates and changes to a class only affect the behaviours we intend(e.g avoding having classes with multiple unrelated functions ).

------------------------------------------------------------------------------------------------

## **What is the difference between top-down and bottom-up design? Which best describes a function oriented design?**

A bottom-up design starts small and builds upwards to create larger systems, whereas a top-down approach starts from the top, building down into smaller subsections.

Bottom-up best describes a function oriented design as it focuses on building smaller modules with distict functions, into a larger system.

------------------------------------------------------------------------------------------------
## **In which design methodology would a class diagram be most useful?**

A class diagram would be most useful in object-oriented design methodology. They are useful in order to map out the structure of a program, including multiple classes, along with their respective properties and functions.

------------------------------------------------------------------------------------------------

## **What are the four pillars of object oriented programming? Give a single-sentence description of each.**
The four pillars of object oriented programming are inheritance, abstraction, polymorphism, and encapsulation.

Inheritance - A process where two classes have a relationship with each other, with the new class' objects acquiring properties or functions of the existing class. 

Abstraction - This is the process whereby developers work on reducing the complexity of our code, exposing only what is necessary and hiding the complexity, especially from users.

Polymorphism - This is a form of abstraction whereby multiple different classes can exhibit the same behaviour. This allows implementation of methods such as interfaces to improve code efficiency.

Encapsulation - This refers to making parts of our code private so as to limit access. A benefit of encapsulation is that it helps prevent unwanted data manipulation which could lead to bugs or other unwanted errors.

------------------------------------------------------------------------------------------------

## **What is the strategy pattern? How would its implementation differ between a functional and object oriented system?**

The strategy pattern is a design pattern whereby there are multiple algorithms, one of which can be selected by a client application at runtime. In a functional system this involves passing functions as arguments for other functions. In object oriented programming this would involve encapsulation of these algorithms in multiple classes.

------------------------------------------------------------------------------------------------

## **Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.**

I would suggest object oriented design for an online payment system. Being able to make use of inheritence, polymorphism, encapsulation, and abstraction will ensure that the code is scalable and also reusable in a myriad of ways, improving efficiency and code readability. This reusability would be especially useful as the system can be used across multiple sectors as specified.