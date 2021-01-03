
# ***TEXT***
#### There are six levels of headings, we usually use **h1** for *main headings* and **h2** for *subheadings*, and **h6** is *the smallest one*.

#### When we want to write a paragraph we use an opening p tag and closing p tag
> <p>    </p>
#### if you want to modify your text you can use i tag for italic
> <i> 
> <b> for bold 
> <sup> for characters that should be superscript
> <sub> for characters that should be subscript
> <br /> for line breaks
> <hr /> for horizontal rules

#### ***Semantic markup***: it adds extra information to the web pages but it doesn't affect the structure of the web pages.

> <strong>:  its content is so important, it will be bold.
> <em>:  it subtly changes the meaning of a sentence, it will be italic.

#### we use for quotations: 
> <blockquote>: for long quotes.
> <q>: for short quotes. 

#### if you want to make abbreviations and acronyms use 
> <abbr> 
> <cite> for citations 
> <dfn> for definitions 
> <address> for author details and it can contain an email or phone number
> <ins> for inserted document
> <del> for deleted text



# ***INTRODUCING CSS***
#### We use CSS to make our website more attractive by controlling the design of HTML elements, so you need to learn CSS features to design the texts, images, backgrounds, and so on. 

#### Each part of your page will be a separate box, and you can control the design of each one of them. 

### **CSS rule:** 
- #### Selector: indicates which element the rule applies to. 
- #### Declaration: indicates how the element should be styled.

#### p { 
#### font-family: Arial;} 

#### And there are many types of selectors you can use at different elements.


# **Basic JavaScript Instructions**

#### A **script** is made from a lot of statements, each statement is an instruction from the programmer, and you will use variables to store information used in the syntax. 

#### If you want to explain what your code does, you can use **comments**, it makes the code easier to understand and read by you and by other people. 
### **Two types of comments:** 
1. #### Multi-line comment     
        /* comment 
             goes 
             here   */ 
    
2. #### Single-line comment  // comment goes here

#### Declaring and assigning a variable: 
> #### var username = Baha ; 
#### There are rules for naming a variable you have to follow always, and you can change the value of the variable. 

#### **Data types:** 
* ##### Numeric: (0 - 9 ) 
* ##### String:  'Baha' 
* ##### Boolean:  True or false 

#### If you want to store a list of values you have to use ***arrays***, you can access its values and change them. 

## **Expressions**
#### Every expression has a value, but you need to assign that value to a variable by using operators like arithmetic (such as +, -, and so on), string, logical, assignment (=), and comparison operators. 

#### Operators allow programmers to create a new value from one or more values. 

#### When you evaluate a condition by comparison operators the result will be a boolean which means true or false. 

### ***Comparison operators:***
  * #### == : is equal to 
  * #### != : is not equal to 
  * #### === : strict equal to
  * #### !== : strict not equal to 
  * #### > : greater than 
  * #### < : less than 
  * #### >= : greater than or equal to 
  * #### <= : less than or equal to 

### ***Logical operators:***
#### Allow you to compare more than one condition

 * #### && : and 
 * #### || : or 
 * #### ! : not

#### In many cases, you have to decide which code should be run next, in order to make this decision, you need to use **conditional statements** such as **if and if-else**, it allows the code to make decisions about what to do next. 

#### Comparison operators: used to compare two operands
* ##### strict equal to ===  
* ##### is equal to ==
* ##### is not equal to ! =
* ##### strict not equal to !==
* ##### less than <
* ##### greater than >
* ##### less than or equal to <=
* ##### greater than or equal to =>

#### In *If statements* the code will *run* if the condition is *true*, and it *won't run* if it's *false*. 
#### But in *if-else statements*, the code will *run* if the condition is *true*, and *another code will run* if it's *false*.
