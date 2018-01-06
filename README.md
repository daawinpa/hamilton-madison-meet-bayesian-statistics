# hamilton-and-madison-meet-bayesian-statistics
As part of their analysis of the Federalist papers, Mosteller and Wallace (1964) recorded the frequency of use of various words in selected articles by Alexander Hamilton and James Madison. The articles were divided into blocks (247 for Hamilton, 262 for Madison) of about 200 words each, and the number of instances of various words in each block were recorded. The table below displays the results for the word “may.” # occurrences in a block 0 1 2 3 4 5 6 7+ Total blocks # blocks (Hamilton) 128 67 32 14 4 1 1 0 247 # blocks (Madison) 156 63 29 8 4 1 1 0 262  These data are also provided in the hamilton and madison vectors. a) Fit a Poisson model to these data, with different parameters for each author and a noninformative/weakly informative prior distirbution. Plot the posterior density of the Poisson mean parameter for each author. Interpret. Fit the model in Stan:
