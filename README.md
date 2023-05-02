Download Link: https://assignmentchef.com/product/solved-cmsc412-operating-systems-final-project
<br>






Design and implement a <strong>Demand Paging</strong> virtual memory simulator!

It must be a text based application (NOT a GUI based one).

You can use the <strong>C/C++</strong> or <strong>Java</strong> programming language.

The following algorithms must be implemented: <strong>FIFO</strong>, <strong>OPT, LRU</strong> and <strong>LFU</strong>.

The application must simulate the execution of each of these algorithms on a hypothetical computer having only <strong>N</strong> physical frames (numbered from <strong>0 to N-1, N&lt;8</strong>), assuming that the single process that is running has a virtual memory of <strong>ten</strong> frames (numbered from <strong>0 to 9</strong>). The number N should be a number provided in the command line as an argument. The algorithms will be simulated based on a reference string (a sequence of pages that are to be accessed) that will be either read from the keyboard or randomly generated.




<strong><em>THE SIMULATION MUST FOLLOW THE ANIMATED EXAMPLES FROM THE ONLINE MODULE 3 AS CLOSE AS POSSIBLE IN ALL ASPECTS !!! </em></strong>




The program should be menu-based and the menu will keep the user in a <strong>loop</strong> containing the following options:




<strong>0 – Exit </strong>

Will exit the program

<h1>1 – Read reference string</h1>

A reference string will be read from the keyboard and stored in a buffer. Each value of the reference string will be verified and validated (or rejected).

Using option 1 again will result in overwriting the old reference string.

<h1>2 – Generate reference string</h1>

A reference string will be randomly generated; the length of the reference string will be given by the user interactively. The string will be stored in a buffer.

Using option 2 more than once will result in overwriting the old reference string.

<h1>3 – Display current reference string</h1>

Will display the stored reference string; if there is no reference string stored yet, an error message will be displayed.

<h1>4 – Simulate FIFO</h1>

Will simulate the step by step execution of the FIFO algorithm using the stored reference string; if there is no reference string stored yet, an error message must be displayed.

The user will press a key after each step of the simulation to continue the simulation. The total number of faults will be displayed at the end of the simulation.

<h1>5 – Simulate OPT</h1>

Will simulate the step by step execution of the OPT algorithm using the stored reference string; if there is no reference string stored yet, an error message must be displayed.

The user will press a key after each step of the simulation to continue the simulation. The total number of faults will be displayed at the end of the simulation.

<h1>6 – Simulate LRU</h1>

Will simulate the step by step execution of the LRU algorithm using the stored reference string; if there is no reference string stored yet, an error message must be displayed.

The user will press a key after each step of the simulation to continue the simulation.

The total number of faults will be displayed at the end of the simulation.

<h1>7 – Simulate LFU</h1>

Will simulate the step by step execution of the LFU algorithm using the stored reference string; if there is no reference string stored yet, an error message must be displayed.

The user will press a key after each step of the simulation to continue the simulation. The total number of faults will be displayed at the end of the simulation.




Selecting a different option will result in an error message but the user will NOT exit the loop!





