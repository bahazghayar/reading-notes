# **Domain Modeling** 

***Domain modeling*** is about creating a code for a *problem domain*, and it has *properties* to *store data* and *methods* for the *behaviors*.
<br>

#### Define a constructor for your many objects because you need to define the same properties, we define a constructor by using a function expression, then you can add properties using `this`, so you can access its properties and methods from inside. 
  
                                     var EpicFailVideo = function(epicRating, hasAnimals) {
                                                this.epicRating = epicRating;
                                                this.hasAnimals = hasAnimals;
                                      }
<br>

#### of course, you can add objects by using `new` keyword and calling the function. It will be stored in a variable so you can access its properties and methods from outside. 
 
                                      var parkourFail = new EpicFailVideo(7, false);
<br>

# **Tables** 
<br>

If you want to represent information in a grid format you will use tables, such as temperatures or sport results. 
<br>

* `<tr>` : table row.
* `<td>` : table data.
* `<th>` : table heading.
<br>

#### You have to use empty `<td>` and `<tr>` elements if you want your table to render correctly, even if it was an empty cell. 
<br>

if you want to span the columns, use colspan attribute, you can use it with `<th>` and `<td>` , and rowspan attribute can be used on a `<th>` or `<td>` to span the rows. 
<br>

#### You can split the table into a `<thead>`, `<tbody>`, and `<tfoot>` for ***long tables***. 

                         <table>
                             <tr>
                             <th></th>
                             <th>9am</th>
                             <th>10am</th>
                             <th>11am</th>
                             <th>12am</th>
                             </tr>
                             <tr>
                             <th>Monday</th>
                             <td colspan="2">Geography</td>
                             <td>Math</td>
                             <td>Art</td>
                             </tr>
                             <tr>
                             <th>Tuesday</th>
                             <td colspan="3">Gym</td>
                             <td>Home Ec</td>
                             </tr>
                             </table>
