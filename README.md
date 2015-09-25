# Code Challenge B

This challenge consists of creating a marble machine that produces sequences of marbles. This machine takes as input one single argument, an integer from 1 to 5, that determines the set of colours available for making a marble sequence.
Your task is to write a web application that runs in a browser that outputs all of the possible marble sequences that this machine could possibly generate. Please return to us:
* Τhe source code
* A chosen input and the resulting output your program produced
* The list of browsers (and versions) in which you tested your program

Input:

Your program must prompt the user for the number of colours, 1 to 5. The colours available to the machine for each input selection are as follows:

1 = [blue] 

2 = [blue, green] 

3 = [blue, green, red] 

4 = [blue, green, red, yellow] 

5 = [blue, green, red, yellow, orange] 


Constraints:

1. The machine is allowed to use any colour only once per sequence, or not at all.
2. A marble can be made of only one colour.
3. The machine must generate at least one marble per sequence.
4. Your program should be written in JavaScript without the use of any JavaScript framework library (i.e. jQuery, Dojo, Backbone.js, Angular.js, Raphael, etc. cannot be used)
5. The program should run in a browser by placing the source in a file system directory and opening the main html page in the browser.

Output:
Your program should generate the list of all possible marble sequences that could be generated for the given input selection from 1 to 5.
Each sequence must be output one per line with no line wrapping. A marble is to be represented by a circle of that colour. Each marble must be reasonably separated from its neighbours.

Sample Input:

2

Sample Output:

![alt text](https://github.com/IglooSoftware/Code-Challenge-B/blob/master/Output.png "Output screenshot")

Submit your response to careers@igloosoftware.com
