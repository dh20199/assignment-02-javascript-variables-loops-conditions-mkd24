# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 

We should use a function like ‘carefulSubtract’ when the information processed by the code is more complex and does not necessarily consist of numbers only. This function assures that only calculations are run, that lead to valid results and thus, error messages can be avoided.

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 

Information in JavaScript can be stored as different types of data. Since JavaScript is a dynamic programming language, variables do not have to be connected to only one data type, but their type can be changed numerous times during the coding process. Assigning a data type to a variable enables the computer to process the information accordingly. If you wanted your code to contain a text element, you need to make sure that the text is recognized as a string. In this particular case you would need to write the text in quotation marks. Other examples of data types in JavaScript are numbers, objects, booleans, and arrays.

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?

Arrays are a specific type of object, but contain extra methods that mere objects do not provide (e.g. push() and pop() to add or remove an element). Using arrays is the preferred option when you are working with a group of entities with the same shape. Using objects might be better suited for a single entity with different data types, especially if you want to manipulate individual properties. Also, order plays an important role: While the elements’ order is rather important in an array and you can address the elements only by using the index number, objects do not keep track of the order and it might be easier to add properties anywhere in the object.


## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?

Similar to the codes we had to work on during the assignment, you could use if/else-statements in order to test the properties and data types and adapt the output accordingly. For example, you could use an if-statement to eliminate error messages that are caused by missing data by saying something like ‘If property is missing, ignore or substitute this element with …’. This way you could also vary the output according to data type and have the function produce different outputs for different data types. A more interesting “transform” might be using this data structure in order to produce a student register with their names, the subject they’re studying and the duration of university experience they have (in years). This might be interesting for a bigger group of students and – coming back to history – could also help to create student registers for past years. 