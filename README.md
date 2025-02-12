# AMP Project
Aim:  We want to implement a target volatility strategy on the commodities 

Steps to do
1) Gather and clean the data (aim to work with daily close prices)
   - Take the bloomberg future 3 months rolling indexes on each main contract of the main commodities (done)
2) Implement and test forcasting volatility models on each contract
  - GARCH
  - SARIMAX (done)
  - ARIMA
  - SABR
  The results may be different based on asset class seasonality, we might have to discuss how to adapt the implementation

3) Volatiltiy Targetting strategy implementation
   - Moreira and Muir (https://amoreira2.github.io/quantitativeinvesting/chapters/Finance/Volatilitytiming.html)
   - Moreira and Muir with risk factors
   - DeMiguel, V., A. Martin-Utrera, and R. Uppal. (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3982504)
   - Other from our creation
   - Transaction cost (based on the liquidity ?)

4) Evaluate Performances
   - Average return
   - Sharpe ratio computes
   - Compare to GMV
   - Max drawdown
   - Turnover
   - Review stats based on the section
   - Precise cases on the crisis

 5) Pretty graphs :)
