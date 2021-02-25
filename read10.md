# Call stack

<br>

### When **the interpreter** keep tracking its place in the code when the script calls multiple functions and keep tracking the functions that called from that function and so on, that what we called ***"Call stack"***

### every function (called by the current function) will be added by the interpreter to the call stack when it called and the code inside it will be executed and when the current function is done, the interpreter will take it off and resume executing the code.

<br>

### Example:  *(from https://developer.mozilla.org/ )*

                function greeting() {
                // [1] Some code here
                sayHi();
                // [2] Some code here
                }
                function sayHi() {
                return "Hi!";
                }           

                // Invoke the `greeting` function
                greeting();

                // [3] Some code here


### The interpreter will ignore everything until it reaches the function invocation, so the greeting function will be added to the call stack list, , then the code inside the greeting function will be executed until it reaches the sayHi function invocation, it will be added to the call stack list, and execute all of the code inside this function, when it's done, the result will be returned and it will be deleted from the list, then the code after the sayHi function invocation will be executed also, and when it's done, the greeting function will be deleted from the call stack list.