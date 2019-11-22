# NDL
Parametric Gradient Space simulations of the No-Defaults-Learner (NDL). 

This repository contains Python code simulating the NDL on the CUNY CoLAG Language Domain.

The simulations were written by Katherine Howitt and Soumik Dey under the supervision of Prof. William Sakas
at Hunter College, Computer Science, and at the Graduate Center, Linguistics and Computer Science of the City University
of New York. It is written in Python 2.7. The results and theoretical underpinnings are in Howitt, Dey and Sakas (submitted to Language Acquisition).

kghowitt@gmail.com

zionsoumik@gmail.com

sakas@hunter.cuny.edu

The program implements a learner that conceptualizes parameter values on a continuum from 0 to 1. It makes use of human-like language e-triggers first proposed by Sakas & Fodor (2012) and significanlty expanded by Howitt, Dey and Sakas. The learner is grounded in Chomsky's principles and parameters framework. The learning model is one of first language acquisition, i.e., acquisition by a very young child.


The Sakas & Fodor (2012), the CUNY CoLAG Domain in its entirety, a technical report describing the domain and other relevant information are downloadable here:

http://www.colag.cs.hunter.cuny.edu/downloadables.html

References: 

Sakas, W.G. & Fodor, J.D. (2012) Disambiguating Syntactic Triggers, Language Acquisition (19) pp 83-143.
Draft of Howitt, Dey and Sakas (Submitted) can be obtained by emailing kghowitt@gmail.com.

-----

11/19/2019: The project is currently being maintained by Katherine Howitt & Soumik Dey

kghowitt@gmail.com

zionsoumik@gmail.com

The resulting data of the simulations are organized into 3 sql files:

previous_simulations.sql
published_simulation.sql
further_simulations.sql. 

The sql files detail various attempts that were made concerning varying the NDL learning rate. 

The tables are are named:

In previous_simulations.sql:  run_1 through run_4
In further_simulations.sql:   run_6 through run10 
In published_simulation:      run_published


###Running the program

The program must be run with a Python interpreter that supports Python 2.7. It can run with
`python main.py <number of individual learners to be simulated> <number of sentences to be processed before stopping per learner>`

###Output
The program will write simulation results to a csv file simulation-output.csv
