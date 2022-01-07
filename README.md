# Black-Scholes-Option-Pricing-model

The Black Scholes model is considered to be one of the best ways of determining fair prices of options. It requires five variables: the strike price of an option, the current stock price, the time to expiration, the risk-free rate, and the volatility.

![image](https://user-images.githubusercontent.com/81409900/148497360-9de281c9-6203-4432-be04-12c235af9aad.png)

# Implied Volatility

It is defined as the expected future volatility of the stock over the life of the option. It is directly influenced by the supply and demand of the underlying option and the market’s expectation of the stock price’s direction. It could be calculated by solving the Black Scholes equation backwards for the volatility starting with the option trading price.

![image](https://user-images.githubusercontent.com/81409900/148497470-b5ba9037-cf78-4e2a-a49d-eb45d5182929.png)

# Option Greeks

Delta: the sensitivity of an option’s price changes relative to the changes in the underlying asset’s price.
Gamma: the delta’s change relative to the changes in the price of the underlying asset.
Vega: the sensitivity of an option price relative to the volatility of the underlying asset.
Theta: the sensitivity of the option price relative to the option’s time to maturity.
Rho: the sensitivity of the option price relative to interest rates.

![image](https://user-images.githubusercontent.com/81409900/148497511-ca29f673-6ad3-4157-a796-8a64dd6573cd.png)
