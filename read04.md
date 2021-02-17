
# CSS Grid

<br>

Instead of using **tables**, **floats**, **positioning**, and **inline-block**, you can use ***CSS grids*** to layout your web page.

<br>

With CSS Grid-based layout system you can layout *columns* and *rows* because it is a **2-dimensional system**.

You will apply CSS rules on the **grid container** *(parent element)* and on the **grid items** *(children)*. 

<br>

#### So you have to define a container element
           display:grid ; 

<br>

#### then set the size of the columns and the rows
           grid-template-columns: 40px 50px auto 50px 40px;
           grid-template-rows: 25% 100px auto;

<br>

#### then put its child elements into the grid with grid column and grid row.

<br>

#### The order doesn't matter, you can place them with CSS.