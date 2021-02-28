# EJS 

### **Embedded JavaScript templating** is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript. *(from ejs.co)*

### Advantages of using EJS:
* ## Fast development time.
* ## Simple syntax.
* ## Speedy execution.
* ## Easy debugging.
* ## Active development. 

<br>

### Example:

                    let ejs = require('ejs');
                    let people = ['geddy', 'neil', 'alex'];
                    let html = ejs.render('<%= people.join(", "); %>', {people: people});

                    <% if (user) { %>
                    <h2><%= user.name %></h2>
                    <% } %>

                    let template = ejs.compile(str, options);
                    template(data);
                    // => Rendered HTML string

                    ejs.render(str, data, options);
                    // => Rendered HTML string

                    ejs.renderFile(filename, data, options, function(err, str){
                        // str => Rendered HTML string
                    });
                    (from ejs.co) 