## D3 Key Function Demo
The script demonstrates the use of a key function when binding data to a D3 selection. The user will cycle through a sequence of steps that will mutate a data structure. For each step, <label> elements in the DOM will be updated accordingly. Red items are elements created initially, whereas black elements are added subsequently. The user can toggle the key function on or off at each step (and thereby switch between the default "by index" access and "by key" access). The user can also force a reordering of the DOM elements to match the selection order.

A div on the right shows the **current content** of the data structure. A div at the bottom shows the **source code** that is about to be executed (using a bit of code introspection). 

For **bl.ocks.org** users, the script should be viewed in its own window. [Link](http://bl.ocks.org/boeric/raw/8b34abda1d33b983b09b/)