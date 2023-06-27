# gambit_mean_outcome
The following script is a (very bulky) way of calculating the average outcome of a game in game theory using the open-source Gambit software. Gambit is a game theory software that calculates the outcome of normal and extended form games. The script I have uploaded accomplishes the task of finding the average (mean) outcome of an extensive form game solved for using perfect Bayesian equilibrium (specifically, Gambit's logit solver).

By mean outcome, I mean the average payoff of the game as a function of the solution provided by the logit solver. Perfect Bayesian equilibria tell you how often a player should, in equilibrium, play a certain strategy. The point of my code is that it multiplies the final payoff by the probability that than node is actually reached. It essentially is the average of all of the "credible" outcomes of a game, weighted by their probability.

The code is very bulky but it works in a two-player context and it also works with moves by nature. Let me know if you find any bugs in it or if you can think of any improvements. I have brought this code to the attention of the Gambit staff.

Thank you!

Haven
