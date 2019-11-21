# NDL
Parametric Gradient Space simulations with Non Default Learner. 

This work was written by Katherine Howitt and Soumik Dey under the supervision of Prof. William Sakas
at Hunter College, Computer Science and the Graduate Center, Linguistics and Computer Science of the City University
of New York. It is written in Python 2.7.

kghowitt@gmail.com

zionsoumik@gmail.com

sakas@hunter.cuny.edu

The program implements a learner that weights parameters on a continuum from 0 to 1, using human-like language e-triggers grounded in Chomsky's principles and parameters framework. The learning model is one of first language acquisition, i.e., acquisition by a child of approximately 2 years of age.

The learner and the abstract domain over which it operates is in detail in:

Sakas, W.G. & Fodor, J.D. (2012) Disambiguating Syntactic Triggers, Language Acquisition (19) pp 83-143.

The paper and domain and other relevant information are downloadable here:

http://www.colag.cs.hunter.cuny.edu/downloadables.html

-----

11/19/2019: The project is currently being maintained by Katherine Howitt & Soumik Dey

kghowitt@gmail.com

zionsoumik@gmail.com



The data regarding the simulations are organized into 3 sql files previous_simulations.sql, published_simulation.sql and further_simulations.sql. It details the various attempts we made about changing the learning rates. The tables are run_1 through run_10 and the published results are in run_published.

###Running the program
The program must be run with a Python interpreter that supports Python 2.7. It can run with
`python main.py <number of learners> <number of sentences to be processed>`


###Output
The program will write simulation results to a csv file simulation-output.csv
