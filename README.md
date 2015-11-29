This was a requirement for Udacity's front-end nanodgree P4: Web Optimization Project.

1st part: Open index.html 
2nd part: go to views file and click on pizza.html

The following were done to optimize the speed of the pages:
-compress and optimize image files
-add async scripts
-move down js to the end of body
-inline minified style.css
-add media="print" for print.css
-remove link to Open Sans fonts
-use document.getElementById
-create local variables outside the loop so the DOM is not explicitly doucted in every iteration
-saved the array length where applicable
-the number of bacground pizzas reduced to at least 24
-add accelerated CSS with transform:translateZ(0) and backface-visibility:hidden properties 