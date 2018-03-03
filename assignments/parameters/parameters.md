# Understanding parameters settings in Evoltionary Algorithms

## Objectives

* Introduce \texttt{inspyred}

* Understand the parameter settings of a basic GA

* Observe the basic behaviour of an EA

* Customize the parameter settings

* Gather and process the main statistics

## Preliminary steps

Install *inspyred* following the instructions available on http://pythonhosted.org/inspyred/. Basically, *inspyred* is a Python module that can be installed like any other module. From an Unix console, just type ```pip install inspyred```.


## One-max problem with inspyred

Copy or download the following script, which implements the one-max problem with a basic Genetic Algorithm. All the relevant algorithm parameters are contained in variables defined in the begining of the script.

(code/onemax.py)

```Python
```

The parameter setting used is the following one:

* Representation: Binary

* Chromosome length: 15

* Crossover: 1-point crossover

* Mutation: Flip mutation

* Mutation probability: 0.1

* Population size: 50

* Termination: 15 generations

Perform the following tasks:

1. Execute the script to validate the installation of \textit{inspyred}.

2. Observe how average and best fitness evolve along the time. Explain their behavior.

3. Execute the script several times, did it always find the solution? Why?

4. Change the chromosome length to $30$ and repeat the previous questions.

5. Customize the algorithm settings to increase the probability of finding a solution.

6. Set $p_m=0.5$. What happen?

7. Set $p_m=1.0$. What happen?

8. Set the chromosome length to $50$ and customize the algorithm to increase the probability of finding a solution.




<img align="center" src="ga.jpg" width="400">

(Image taken from [here](http://file.scirp.org/Html/1-8302163_41175.htm).)

Once the algorithm is implemented, perform the following tasks:

1. Show the best fitness found in each generation. Execute the algorithm. How does the best fitness evolve?
2. Compare the execution time with n=10, n=20 and n=100. (Hint: Use the Unix command *time*).

