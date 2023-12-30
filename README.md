**Stock Portfolio Optimization Project**
**Objective** : This project aims to construct a stock portfolio that balances risk and profit effectively while comparing various investment strategies. The focus will be on Modern Portfolio Theory (MPT) and Momentum Trading (MT).

**Strategies Overview**
**Modern Portfolio Theory (MPT)**
**Purpose**: Allocate investments in stocks to maximize expected returns, considering individual risk tolerance, which is quantified by volatility.
Method: Employ a piecewise approach to optimize the allocation of stocks for each defined risk tolerance level. By evaluating numerous risk levels (e.g., 100 different levels), this method will yield a range of investment allocations, each tailored to a specific risk ceiling.

**Outcome**: The model will showcase a spectrum of portfolio compositions from low-risk, diversified portfolios with potentially modest returns to high-risk, concentrated investments with the possibility of higher returns. The goal is to illustrate the efficient frontier – the range of possible profit outcomes across all risk levels.

**Momentum Trading (MT)**

**Approach**: Leverage the relationship between short-term (8-day) and medium-term (21-day) moving averages to trigger buy and sell decisions.

**Strategy**: Execute buy orders when the 9-day moving average surpasses the 21-day average, and sell orders when the reverse occurs.

**Integration with MPT**: Adapt MT parameters to complement and enhance portfolios developed using the MPT model.

This notebook contains the steps that we took for optimal portfolio allocation using Modern Portfolio Theory (MPT) and Momentum Trading (MT). 

The three sectors selected for our group were Consumer Staples, Utilities, and Real Estate.

Our selected stocks for each sector are as follows:

**Consumer Staples:** Church & Dwight Co. (CHD), Keurig Dr Pepper Inc. (KDP), and Walmart Inc. (WMT).

**Utilities:** Exelon Corporation (EXC), Pinnacle West Capital Corporation (PNM), and FirstEnergy Corp. (FE).

**Real Estate:** Avalonbay Communities (AVB), Invitation Homes Inc. (INVH), and Prologis, Inc. (PLD).
