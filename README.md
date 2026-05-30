Implements SVI (Stochastic Volatility Inspired) parameterization 
to fit implied volatility across strike and expiry dimensions.
IV is solved numerically using Newton-Raphson on the Black-Scholes 
vega. Surface is validated for static arbitrage (butterfly and 
calendar spread conditions).
