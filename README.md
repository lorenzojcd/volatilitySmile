# volatilitySmile
How to use the Black Scholes model to calculate implied volatility

What Is a Volatility Smile?
A volatility smile is a common graph shape that results from plotting the strike price and implied volatility of a group of options with the 
same underlying asset and expiration date. The volatility smile is so named because it looks like a smiling mouth.

Implied volatility rises when the underlying asset of an option is further out of 
the money (OTM) or in the money (ITM), compared to at the money (ATM). The volatility smile does not apply to all options.


What Does a Volatility Smile Tell You?
Volatility smiles are created by implied volatility changing as the underlying asset moves more ITM or OTM. The more an option is ITM or OTM, the greater its implied volatility becomes. Implied volatility tends to be lowest with ATM options.


The volatility smile is not predicted by the Black-Scholes model, which is one of the main formulas used to price options and other derivatives. The Black-Scholes model predicts that the implied volatility curve is flat when plotted against varying strike prices. Based on the model, it would be expected that the implied volatility would be the same for all options expiring on the same date with the same underlying asset regardless of the strike price. Yet, in the real-world, this is not the case.


Volatility smiles started occurring in option pricing after the 1987 stock market crash. They were not present in U.S. markets prior, indicating a market structure more in line with what the Black-Scholes model predicts. After 1987, traders realized that extreme events could happen and markets have a significant skew. The possibility for extreme events needed to be factored into options pricing. Therefore, in the real world, implied volatility increases or decreases as options move more ITM or OTM.

Also, the volatility smile's existence shows that OTM and ITM options tend to be more in demand than ATM options. Demand drives prices which affects implied volatility. This could be partially due to the reason mentioned above. Extreme events can occur causing significant price shifts in options. The potential for large shifts is factored into implied volatility.
