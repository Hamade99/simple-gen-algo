# simple-gen-algo

A simple genetic algorithm that is highly adaptable by changing the global variables in the first cells.

**Explanation**

In this piece of code I attempted to manually implement a genetic algorithm from scratch. The catch however is that the behavior and modelling is very, very variable. That is to say, we can adapt our algorithm to account for many different use cases. The implementation given below is for finding an individual that has 5 genes in its genotype, with the final individual reaching a maximum score of (hopefully) 10 in each gene. This is achieved by crossover (which can be changed easily), mutation (whose rates and implentation are changed easily), and tournament selection (whose restrictions and variables can be altered to experiment). The genotype variables can all be altered, in this case they are 10 for simplicity. 
Please note that crossover and mutation behavior can be changed or extended upon as necessary. Only a couple of variations were included for simplicity.

Depending on your input variables (and how lucky you get with the initial population), this could take a while to run. But such is the nature of Genetic Algorithms. Feel free to play around with the variables to see what happens!

**HOW TO USE**

1. Run everything from top to bottom. The top cells are variables, imports, and methods. The cells below that are the main loop.
2. The program stops automatically when it reaches optimality (which can be tuned in the variables below). It is currently set so that the program terminates when the sum of the optimal solution (all 10s) minus the sum of the current individuals is smaller or equal to 5. Depending on this parameter the program is faster/slower. An overall difference for 5 still produces a really really good individual, but feel free to change that if you do not want to wait for convergence... which is totally understandable. 
3. There are a lot of print statements in the methods that can be uncommented at any time to get more information. Jupyter Notebook just does not like loads and loads of text being printed constantly, so I kept it minimal. 
4. If you want to rerun the program (or after you terminated it), restart the whole kernel, clean all variables and run from the top to bottom again.
5. Let me know if there are any questions!
