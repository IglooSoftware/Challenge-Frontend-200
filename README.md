# Frontend Code Challenge (200) 

This challenge consists of creating a _marble machine_ that produces sequences of marbles.
This machine takes an input of one single argument, an integer from 1 to 5, that determines the set of colours available for making a marble sequence.
Your task is to write a web application, that runs in a browser, that outputs all possible marble sequences that this machine could generate.

**Please return to us:**  
1. The source code.  
2. A chosen input and a screen shot of the resulting output your program produced.  
3. The list of browsers (and versions) in which you tested your program.

### Input
Your program must prompt the user for the number of colours, 1 to 5. The colours available to the machine for each input selection are as follows:

`1` = [blue]  
`2` = [blue, green]  
`3` = [blue, green, red]  
`4` = [blue, green, red, yellow]  
`5` = [blue, green, red, yellow, purple]  

### Output
Your program should generate the list of all possible marble sequences that could be generated for the given input selection from 1 to 5.

#### Sample Input  
`2`  

#### Sample Output
![alt text](static/marble-output-for-2.png "Sample Output Image")
 
### Constraints
1. The machine is allowed to use any colour only once per sequence, or not at all.
2. A marble can be made of only one colour.
3. The machine must generate at least one marble per sequence.

### User Interface
We have provided [mockups](mockups/) of the expected UI of your marble machine, it should look as close as possible to the mockups.
There are 3 configuration settings that can visually affect the output:

**Marble Style** – Fill or outline  
**Display** – Row or column  
**Marble Size** – Small (20px), medium (40px), large (60px)  

### Other
Your program should be written in JavaScript without the use of any JavaScript framework library (i.e. jQuery, Dojo, Backbone.js, Angular.js, Raphael, etc. cannot be used)
The program should run in a browser by placing the source in a file system directory and opening the main html page in the browser.

##### Bonus Points (in no particular order):
- Works in IE11
- Uses SASS
- ES6 Syntax
- Responsive
