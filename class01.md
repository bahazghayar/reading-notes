# Node Ecosystem, TDD, CI/CD 

## Array.map()  
* #### It iterates over an array and runs a callback function for each element.
* #### It returns a new array with the same length.
* #### No need to push to the new array. 
* #### It doesn't affect the original array.  
### Example:
                let numbers = [2,3,4,5];
                let squares = numbers.map( ( item,index ) => {
                    return item * item ;
                });

## Array.reduce()
* #### It takes 3 parameters (accumulator, value, index ).
* #### It iterates over an array and returns the result of the accumulator.
* #### The accumulator can be an initial empty object, variable, string, or array.
* #### There is an initial value that represents the value of the accumulator in the first iteration.
### Example: 
                let numbers = [1,2,3,4];
                let sum = numbers.reduce(  (accumulator,value,idx) => {
                accumulator = accumulator + value;
                return accumulator;
                }, 0);


# superagent()

* ## With normal Promise .then() syntax
                const superagent = require('superagent') ;
                function getData(req , res ){
                    superagent.get(url)
                    .then(results =>{
                    console.log(results.body)
                })
                } 

* ## Again with async / await syntax 
                async function getData(req , res){
                    let results = await superagent.get(url) ;
                    console.log(results) ; 
                };               


# Promises 
## JavaScript is single-threaded, meaning that two bits of script cannot run at the same time; they have to run one after another. A Promise is an object that represents the eventual completion (or failure) of an asynchronous operation, and its resulting value. 
from (freecodecamp.org) 

# Are all callback functions considered to be Asynchronous? Why or Why Not?
## No, because a callback doesn't make a function asynchronous. For example, there's forEach in Array. It iterates over each item and calls the function once per item. 
from (bytearcher.com)
