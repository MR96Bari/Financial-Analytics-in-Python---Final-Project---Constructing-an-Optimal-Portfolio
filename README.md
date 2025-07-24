# Financial-Analytics-in-Python---Final-Project---Constructing-an-Optimal-Portfolio
Optimal Portfolio Construction with Technical Strategies

As part of Maryland-College Park and the Smith School's BMSO 758F course, our team—Michael Lindale, Matthew Rutigliano, and Taylor Sheridan—developed a Python-based investment portfolio optimization model across equities, fixed income, commodities, and currencies.

📌 Objective
Build an 8-instrument portfolio that:

Maximizes Sharpe Ratio

Maintains Beta to SPY ≤ 0.5

Uses a mix of asset classes (5 equities, 1 bond, 1 commodity, 1 currency)

Applies three distinct technical strategies (MA-Flat, MA-Short, Bollinger Bands)

🔧 Methodology
Sharpe Ratio Maximization: We evaluated all instruments’ technical strategy variants and selected those with the highest risk-adjusted returns.

Low Correlation Selection: We screened for low inter-instrument correlation (avg. absolute correlation = 0.062).

Portfolio Weighting:

Equal Weight

Min Volatility

Max Sharpe (Optimal)

Final Portfolio Performance:

Annual Return: 10.73%

Annual Risk: 8.34%

Sharpe Ratio: 1.29

Beta to SPY: 0.098

📊 Tools & Libraries
Python (Jupyter Notebook)

Pandas, NumPy, Matplotlib

Portfolio theory, CAPM, Technical indicators
