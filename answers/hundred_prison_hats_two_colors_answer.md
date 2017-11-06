# Hundred Prison Hats Answer with two colors

The prisoner at the back of the line can see all the hats in front of him, so 
it is his job to communicate the total number of red and blue hats to all the 
prisoners. He cannot say a number, but he can indicate whether the number of 
blue hats, for instance, is odd or even by his answer of "red" or "blue". When 
it is each prisoner's turn to guess the color of his own hat, he can see every 
hat in front of himself and can count how many blue hats remain with the 
possibility of one more blue hat on his own head. Therefore, all that each 
prisoner needs to know is whether the number of blue hats remaining is odd or 
even in order to know whether or not he has a blue hat.

The strategy is that the prisoner at the back of the line says "blue" if the 
number of blue hats he sees is even and "red" if the number of blue hats he 
sees is odd. After the prisoner at the back of the line answers, every 
following "blue" answer changes whether the number of remaining blue hats is 
odd or even. As long as each prisoner hears the answer of the first prisoner 
questioned and counts the number of following "blue" answers, the prisoners can 
achieve 100% survival for all but the first prisoner questioned.
