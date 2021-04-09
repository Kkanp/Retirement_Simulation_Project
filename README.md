# Retirement_Simulation_Project

The goal of this project is to create an algorithm that calculates the probability that a person will run out of money any time before he/she dies, given his/her initial amount of money, age, annual withdrawal amount, and investment in stocks and bonds. 

The individual owns $1 million dollars and every year, at the end of the year, he draws out $X. He is invested 60% stocks – 40% bonds. He lives for a random number of years, which is uniformly distributed between 70-Y and 90-Y. With Y being his age between 50-65.

Assumptions:
- a stock fund (mu = 6%, sigma = 20%)
- a bond fund (mu= 3% sigma = 3%)
- correlation in the GBM between the stock and bond fund is 0.2

I also an approach to fit a ML model to generated samples and how to select optimal hyperparameters.
