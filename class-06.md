# ***Problem Domain***

**Is it logical to solve a problem before you know the question?** I think that you **won't be even close to the right answer**, and you will make everything harder and harder on yourself. 

In fact, ***programming*** is easy if you understand the ***problem domain***, the hardest thing in coding is *understanding the problem domain*, and the easiest way to solve any problem is to understand the whole question from A to Z, but sometimes you don't have the complete information about the problem domain in order to understand it.

## So you have to: 
* ### Make the problem domain easier.
* ### Get better at understanding the problem domain. 

### You can cut off the problem into several parts, then focus on a particular part.




# ***Object Literals***

***Object***: series of variables and functions that represent a model from the world around us. 

In an object, ***variables*** become known as ***properties*** of the object, and ***functions*** become known as ***methods*** of the object. 

### Properties (variables):  have a name and value. 

            name: 'Baha' ; 
            key: name 
            value: 'Baha' 

### Methods (functions): have a name and a value.


You can ***create objects*** by using ***literal notation***, it's the easiest way, and you can access properties or methods by using ***dot notation***, also you can access properties by ***square brackets***.

### ***Examples:***
     var hotelName = hotel.name ; 
     var roomsFree =  hotel.checkAvailability ( ) ; 

     var hotelName = hotel['Name'] ;


# ***Document object model***

***The document object model*** is a separate set of rules about making a model of the HTML page ***(DOM tree)*** and accessing and changing the HTML page by JavaScript, of course, it's not a part of HTML nor JavaScript.

Browsers represent the web page using a DOM tree and it offers tools for viewing it.

### DOM trees have four types of nodes:
* Document nodes.
* Element nodes.
* Attribute nodes.
* Text nodes.


### How you can select element nodes:
1. ID attribute.
2. Class attribute.
3. Tag name.
4. CSS selector syntax.



The DOM query will return a ***Nodelist*** if it can return more than one node. 

