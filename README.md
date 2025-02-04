# Multiplicities-of-two-Einstein-Solid

This is a R code for computing the multiplicities of two Einstein Solids, solid A and B. 

The code provides the multiplicities of every macrostates and provides a table. It is recommended to call "html_mult_table" which opens up a webpage for the whole table. Input your desired values at the top of the codes. The three inputs are:

q_total - Total units of energy available to the system
n_a - Number of oscillators in solid A
n_a - Number of oscillators in solid B

The code also returns 4 useful information on "Most Probable Macrostate q_a", "Probability of most probable macrostate", "Least Probable Macrostate q_a", and "Probability of least probable macrostate". Calling "Results" will provide this information.

In addition, at the end of the code, A and B variables can be inputted with two values within the intervals of q_a, and returns the probability of this interval. This result is stored in "prob_int".

There are limitations in which above a certain value of q_total or n_total, R may no longer be able to perform the heavy computations.
