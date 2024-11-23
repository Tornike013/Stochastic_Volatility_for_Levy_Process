# Stochastic_Volatility_for_Levy_Process
Group Assingment in Levy Process and Aplications. Project is about the Stochastic Volatility for Normal Inverse Gaussian process. Parameters and market prices are used from the book (Levy Processes in Finance: Pricing Financial Derivatives by Wim Schoutens).

We answered following questions:

(1) Simulate some trajectories of the underlying L´evy process of your model
and plot these trajectories for the parameter values estimated in the book and
also for a set of different values of the parameters. Describe the algorithm you
use for the simulation of these trajectories.

(2)
(i) By Monte-Carlo simulation and/or using an appropriate closed form formula, calculate the price of some call options over the S&P 500 Index
at the close of the market on 18 April 2002. This data is presented in a Table
in Appendix C (pages 155-156) of Schoutens book. Use the maturity date of
March 2003 and use all the strike prices in the Table for this maturity date.

(ii) Compare the obtained prices with the real prices (for the strikes in the
Table where you have real prices) and calculate the average relative percentage
error (ARPE) for the set of call option prices that
you calculated and that are presented in the Table of appendix C. Compare this
ARPE value with the ARPE value obtained by using the Black-Scholes formula
and the real prices.

(iii) By using the Black-Scholes formula, and based on the prices calculated
for the options by the model, calculate the implied volatilities and plot the
implied volatility against the strike, comparing with the implied volatilities obtained from the real option prices for the maturity date March 2003. Comment
the results obtained.

(3)
By Monte-Carlo simulation, calculate the price of an exotic Barrier option
of the type “down-and-out barrier call” (DOBC), which is worthless unless its
minimum remains above some low barrier H, in which case it retains the structure of a European call with strike K (see Schoutens, chapter 9). Take the time
to maturity T to be 12 months, the strike K = S0 = 1124.47, the barrier H
value is given by HDOB = 0.8 × S0 and compare the price obtained with the
ones in Table 9.1 (Chapter 9 of Schoutens). You can consider 2000 simulations
of paths and 300 equally small time steps.
