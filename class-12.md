# ***Charts*** 

<br>

When you want to **display your data**, the best way to do so is by **charts**.

<br>

You can make charts by using **chart.js** *( it use HTML5 canvas elements to draw all kind of graphs )*. 
                 
               <canvas> 

<br>

**Charts types:** 
* *Bar charts*.
* *Line charts*.
* *Pie charts*. 
and more. 


**HTML file:**
                    `<canvas id="stockGraph" width="150" height="150">`
                           `current stock price: $3.15 + 0.15`
                    `</canvas>`

<br>

*You can style it by using CSS.* 

<br>

**JS file:**

                   var canvas = document.getElementById('tutorial');
                   var ctx = canvas.getContext('2d');

<br>

You can draw **rectangles**, **triangles**, **lines**, **arcs**, and **curves** on the canvas, then you can apply *styles and colors*.

                   fillRect(x, y, width, height)

                   arc(x, y, radius, startAngle, endAngle, anticlockwise)