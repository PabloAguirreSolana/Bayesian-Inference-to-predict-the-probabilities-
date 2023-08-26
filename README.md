# Bayesian Inference to predict the probabilities of a Primary Party Election based on Opinion Polls

 The objective of this notebook is to provide a simple code to calculate the posteriors of A and B and see who is more likely to have the biggest probability. (Assuming that A and B are two final candidates that are contesting a Primary Election)

 The procedure is very simple:

 - Transform percenateges of opinion polls of candidate A and B as trials so that they can serve as priors.
 - Create a function to simulate the beta posteriors (with this function we can add new information as priors and add it to the model, based on previous knowledge or domain expertise)
 - Plot the posterior distributions
 - Calculate the posterior difference between A and B
 - Calcualte a 90% and 95% credible inetrval, which will tell us the estimation error in terms of proababilities.
