# **JQuery**

**jQuery** is a *JavaScript library* that allows web developers to add extra functionality to their websites. It is open source and provided for free under the MIT license. ... jQuery can also work with Ajax code and scripting languages, such as PHP and ASP to access data from a database. 
*(from techterms.com)*

### Before using jQuery include the jQuery script in your page before the closing `</body>` tag.

### Example: 
            $('li.hot') 

### There are many methods that you can use with the elements you select by jQuery. 
### Example: 
            $('li.hot').addClass('complete') ; 

## Why use JQuery? 
1. Simple selectors. 
2. Common tasks in less code.
3. Cross-browser compatibility.

<br>

# A matched set / jQuery selection 

### JQuery object will return when you select one or more elements.

### There are several jQuery methods to get and set information, but they do not always apply to all elements. 

### Such as: 
`.html()` : returns only the content of the first element.  <br>

`.each()` : retrieve the value of every element. <br>

`.text()` : returns the content from every element. <br>
`.val()`  : to get the content from `<input>` or `<textarea>` elements. <br >


## Chaining: adding several methods to the same selector.

### Example: 
                     $('li[id!="one"] ')
                           .hide()
                           .delay(500)
                           . fadeln(1400);

**NOTE**: You can't chain methods that retrieve information from the DOM (or about the browser). 

### You can check if your code works or not by using 
`.ready()`          

