In this project, we aimed to evaluate the performance of different collar strategies across various market cycles, specifically during the pre-COVID (2017-2019), COVID (2019-2020), and post-COVID (2020-2023) periods​.

**Project Objectives:**

Construct Collar Strategy Portfolios: We created portfolios with different combinations of moneyness (the relative difference between the asset price and strike price) for call and put options. The moneyness combinations were designed to balance risk mitigation and return generation under varying market conditions.
Monthly Rebalancing: We rebalanced the portfolios on a monthly basis, with strike prices for the options being updated to reflect changing market conditions​.
Comparative Analysis: Our goal was to compare the performances of these portfolios across the selected time periods, considering factors like market trends and volatility​.

**Collar Strategy:**

A collar strategy is a risk management approach combining a long position in the underlying asset, a protective put option to limit downside risk, and a short call option to cap upside potential​(collarpre-4).
This strategy is ideal for investors seeking downside protection while willing to accept limited gains.

**Portfolio Construction:**

We designed the following collar portfolios with various combinations of moneyness:

PF1: 3% Call and 5% Put
PF2: 5% Call and 3% Put
PF3: 3% Call and 7% Put
PF4: 5% Call and 1% Put​.

**Methodology:**

Option Pricing via Black-Scholes Model (BSM): We used the Black-Scholes model to calculate the option prices. This model incorporates inputs such as the spot price, time to maturity, strike price, rolling volatility, and risk-free rate​.
Profit Calculation: We calculated the daily profit or loss for each portfolio based on the change in option prices, as well as naked spot returns. The profit calculations were aggregated monthly to align with the rebalancing schedule​.
Data Handling: We fetched historical data, including S&P 500 prices and 3-Month Treasury Bill rates, and used a rolling window of volatility (10-day) to adjust for market fluctuations​.

**Results:**

Pre-COVID: PF3 (3% Call and 7% Put) yielded the highest returns (0.07% excess returns)​.
COVID: PF4 (5% Call and 1% Put) performed best during the volatile COVID period, generating 4.31% excess returns​.
Post-COVID: PF1 (3% Call and 5% Put) produced 0.85% excess returns in the stable post-COVID era​.

**Conclusion:**

While all portfolios produced similar returns in stable markets, the PF4 portfolio excelled during the volatile COVID era, providing strong downside protection with limited upside gains​.
