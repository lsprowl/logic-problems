# Hundred Prison Hats Answer with three colors

The prisoner at the back of the line can see all the hats in front of him, so 
it is his job to communicate the total number of red, yellow, and blue hats to 
all the prisoners. As he cannot say a number, and can only say "red", "yellow", 
or "blue", the number of hats needs to be communicated to the other prisoners 
in sets of three. The prisoner at the end of the line counts the number of hats 
of each color in sets of three and mentally records the number of hats of each 
color that are left over which do not fit into a set of three. These numbers 
are communicated to the remaining prisoners by his answer of "red", "yellow", 
or "blue". The remaining prisoners can also count the number of hats of each 
color in front of them in sets of three and know how many of each color are 
left over which do not fit into a set of three, therefore knowing which color 
must be on their own head.

The strategy is that the prisoner at the back of the line says "red", "yellow", 
or "blue" which is a key for the number of each colored hat left over which 
does not fit into a set of three. The key given by the first prisoner 
questioned changes slightly depending on the number of prisoners in line. If 
the prisoner at the back of the line sees a multiple of three prisoners in 
front of him, such as with 100 prisoners, "red" indicates that the number of 
left over hats is equal for each color, "yellow" indicates that the number of 
left over hats of red, yellow, and blue are 2, 1, and 0 in some cyclic order 
such as 2-1-0 or 1-0-2 or 0-2-1, and "blue" indicates that the number of left 
over hats of red, yellow, and blue are 0, 1, and 2 in some cyclic order such 
as 0-1-2 or 1-2-0 or 2-0-1. If the prisoner at the back of the line sees a 
number of prisoners that is not a multiple of three, such as with 101 or 102 
prisoners, "red" indicates that the number of left over red hats is unique, 
"yellow" indicates that the number of left over yellow hats is unique, and 
"blue" indicates that the number of left over blue hats is unique. The 
following tables give the nine possible scenarios for each number of prisoners 
and which key the prisoner at the back of the line should use. By hearing the 
key told by the first prisoner questioned and listening to the following 
answers, the prisoners can achieve 100% survival for all but the first prisoner 
questioned.

with 100 prisoners (multiple of 3 seen by last prisoner):  
|red hats left|yellow hats left|blue hats left|what the 100th prisoner says|
|:-----------:|:--------------:|:------------:|----------------------------|
| 0           |  0             | 0            | "red"                      |
| 1           |  1             | 1            | "red"                      |
| 2           |  2             | 2            | "red"                      |
| 2           |  1             | 0            | "yellow"                   |
| 0           |  2             | 1            | "yellow"                   |
| 1           |  0             | 2            | "yellow"                   |
| 1           |  2             | 0            | "blue"                     |
| 2           |  0             | 1            | "blue"                     |
| 0           |  1             | 2            | "blue"                     |

with 101 prisoners (multiple of 3, plus 1 seen by last prisoner):  
|red hats left|yellow hats left|blue hats left|what the 101st prisoner says|
|:-----------:|:--------------:|:------------:|----------------------------|
| 1           |  0             | 0            | "red"                      |
| 0           |  2             | 2            | "red"                      |
| 2           |  1             | 1            | "red"                      |
| 0           |  1             | 0            | "yellow"                   |
| 2           |  0             | 2            | "yellow"                   |
| 1           |  2             | 1            | "yellow"                   |
| 0           |  0             | 1            | "blue"                     |
| 2           |  2             | 0            | "blue"                     |
| 1           |  1             | 2            | "blue"                     |

with 102 prisoners (multiple of 3, plus 2 seen by last prisoner):  
|red hats left|yellow hats left|blue hats left|what the 102nd prisoner says|
|:-----------:|:--------------:|:------------:|----------------------------|
| 2           |  0             | 0            | "red"                      |
| 0           |  1             | 1            | "red"                      |
| 1           |  2             | 2            | "red"                      |
| 0           |  2             | 0            | "yellow"                   |
| 1           |  0             | 1            | "yellow"                   |
| 2           |  1             | 2            | "yellow"                   |
| 0           |  0             | 2            | "blue"                     |
| 1           |  1             | 0            | "blue"                     |
| 2           |  2             | 1            | "blue"                     |
