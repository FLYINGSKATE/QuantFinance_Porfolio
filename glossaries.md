# Quantitative Finance Glossary

A comprehensive guide to essential terms, concepts, and methodologies in quantitative finance.

## Table of Contents

- [Mathematical Foundations](#mathematical-foundations)
- [Statistical Concepts](#statistical-concepts)
- [Risk Management](#risk-management)
- [Derivatives and Options](#derivatives-and-options)
- [Fixed Income](#fixed-income)
- [Portfolio Theory](#portfolio-theory)
- [Time Series Analysis](#time-series-analysis)
- [Algorithmic Trading](#algorithmic-trading)
- [Market Microstructure](#market-microstructure)
- [Credit Risk](#credit-risk)
- [Regulatory and Compliance](#regulatory-and-compliance)

---

## Mathematical Foundations

**Alpha (α)** - A measure of an investment's performance relative to a benchmark index. Positive alpha indicates outperformance.

**Beta (β)** - A measure of systematic risk, representing the sensitivity of an asset's returns to market movements.

**Brownian Motion** - A mathematical model for random price movements, fundamental to many financial models including Black-Scholes.

**Geometric Brownian Motion (GBM)** - A continuous-time stochastic process used to model stock prices, assuming constant drift and volatility.

**Ito's Lemma** - A fundamental theorem in stochastic calculus used to find the differential of a function of a stochastic process.

**Monte Carlo Simulation** - A computational method using random sampling to solve mathematical problems and model complex systems.

**Stochastic Differential Equation (SDE)** - A differential equation containing stochastic terms, used to model random processes in finance.

---

## Statistical Concepts

**Autocorrelation** - The correlation of a time series with a delayed copy of itself, indicating how past values influence current values.

**Central Limit Theorem** - Statistical theorem stating that sample means approach a normal distribution as sample size increases.

**Covariance** - A measure of how two variables change together, fundamental to portfolio theory.

**Kurtosis** - A measure of the "tailedness" of a probability distribution, indicating extreme events frequency.

**Maximum Likelihood Estimation (MLE)** - A method for estimating parameters of a statistical model by maximizing the likelihood function.

**P-value** - The probability of obtaining test results at least as extreme as observed, assuming the null hypothesis is true.

**Regression Analysis** - Statistical method for modeling relationships between dependent and independent variables.

**Skewness** - A measure of asymmetry in a probability distribution.

**Standard Deviation** - A measure of dispersion around the mean, commonly used to quantify risk.

**Variance** - The average of squared deviations from the mean, measuring variability in returns.

---

## Risk Management

**Conditional Value at Risk (CVaR)** - Expected loss beyond the VaR threshold, also known as Expected Shortfall.

**Drawdown** - The decline from peak to trough in an investment's value over a specific period.

**Expected Shortfall** - See CVaR; the expected loss given that a loss exceeds the VaR threshold.

**GARCH (Generalized Autoregressive Conditional Heteroskedasticity)** - A model for estimating volatility clustering in financial time series.

**Greek Letters** - Risk sensitivities of derivatives:
- **Delta (Δ)** - Price sensitivity to underlying asset changes
- **Gamma (Γ)** - Rate of change of delta
- **Theta (Θ)** - Time decay sensitivity
- **Vega (ν)** - Volatility sensitivity
- **Rho (ρ)** - Interest rate sensitivity

**Hedging** - Risk management strategy to offset potential losses in investments.

**Sharpe Ratio** - Risk-adjusted return measure calculated as excess return divided by standard deviation.

**Sortino Ratio** - Risk-adjusted return measure focusing only on downside deviation.

**Stress Testing** - Risk assessment technique examining portfolio performance under extreme market conditions.

**Value at Risk (VaR)** - Maximum potential loss over a specific time period at a given confidence level.

**Volatility** - Measure of price fluctuation, typically expressed as standard deviation of returns.

---

## Derivatives and Options

**American Option** - Option that can be exercised at any time before expiration.

**Asian Option** - Exotic option where payoff depends on the average price of the underlying asset.

**Barrier Option** - Option with payoff dependent on whether the underlying asset reaches a certain price level.

**Binomial Model** - Discrete-time model for option pricing using a tree-like structure of possible price movements.

**Black-Scholes Model** - Fundamental partial differential equation for pricing European options.

**Call Option** - Right to buy an underlying asset at a specified price within a certain time.

**Delta Hedging** - Risk management strategy maintaining a delta-neutral position.

**European Option** - Option that can only be exercised at expiration.

**Implied Volatility** - Volatility value that makes the theoretical option price equal to market price.

**In-the-Money (ITM)** - Option with intrinsic value (call: spot > strike; put: spot < strike).

**Intrinsic Value** - The immediate exercise value of an option.

**Moneyness** - Relationship between current asset price and strike price.

**Out-of-the-Money (OTM)** - Option with no intrinsic value.

**Put Option** - Right to sell an underlying asset at a specified price within a certain time.

**Put-Call Parity** - Relationship between call and put option prices with same strike and expiration.

**Time Value** - Option value beyond intrinsic value, decreasing as expiration approaches.

**Volatility Smile** - Pattern where implied volatility varies with strike price.

---

## Fixed Income

**Accrued Interest** - Interest earned but not yet received on a bond.

**Bond Duration** - Measure of price sensitivity to interest rate changes.

**Convexity** - Measure of the curvature of price-yield relationship for bonds.

**Credit Spread** - Yield difference between corporate and government bonds of similar maturity.

**Discount Factor** - Present value of one unit of currency received at a future date.

**Forward Rate** - Interest rate for a future period implied by current yield curve.

**Macaulay Duration** - Weighted average time to receive bond cash flows.

**Modified Duration** - Approximation of percentage price change for a 1% yield change.

**Yield Curve** - Graph showing yields of bonds with different maturities.

**Yield to Maturity (YTM)** - Total return anticipated on a bond if held until maturity.

**Zero-Coupon Bond** - Bond that pays no periodic interest, sold at discount to face value.

---

## Portfolio Theory

**Arbitrage** - Simultaneous buying and selling to profit from price differences with no risk.

**Arbitrage Pricing Theory (APT)** - Multi-factor model for asset pricing based on systematic risk factors.

**Capital Asset Pricing Model (CAPM)** - Model describing relationship between systematic risk and expected return.

**Efficient Frontier** - Set of optimal portfolios offering highest expected return for each risk level.

**Efficient Market Hypothesis (EMH)** - Theory that asset prices reflect all available information.

**Factor Model** - Statistical model explaining asset returns through exposure to systematic factors.

**Fama-French Three-Factor Model** - Extension of CAPM including size and value factors.

**Markowitz Mean-Variance Optimization** - Portfolio optimization technique balancing expected return and risk.

**Modern Portfolio Theory (MPT)** - Framework for constructing portfolios to maximize return for given risk.

**Risk-Free Rate** - Theoretical return on investment with zero risk, typically government bond yield.

**Security Market Line (SML)** - Graphical representation of CAPM showing risk-return relationship.

**Systematic Risk** - Market-wide risk that cannot be eliminated through diversification.

**Unsystematic Risk** - Company-specific risk that can be reduced through diversification.

---

## Time Series Analysis

**Autoregressive (AR) Model** - Model where current value depends on previous values.

**Autoregressive Integrated Moving Average (ARIMA)** - Statistical model for time series forecasting.

**Cointegration** - Long-term equilibrium relationship between non-stationary time series.

**Dickey-Fuller Test** - Statistical test for unit root presence in time series.

**Heteroskedasticity** - Condition where variance of errors changes over time.

**Moving Average (MA) Model** - Model where current value depends on past error terms.

**Random Walk** - Time series where each step is independent and random.

**Seasonality** - Predictable patterns that repeat over fixed periods.

**Stationarity** - Statistical property where mean, variance, and autocorrelation remain constant.

**Unit Root** - Characteristic of non-stationary time series indicating random walk behavior.

**Vector Autoregression (VAR)** - Model for multiple time series with interdependencies.

**White Noise** - Random signal with constant power spectral density.

---

## Algorithmic Trading

**Algorithm** - Set of rules or instructions for automated trading decisions.

**Backtesting** - Testing trading strategy on historical data to evaluate performance.

**Execution Algorithm** - Algorithm designed to execute large orders with minimal market impact.

**High-Frequency Trading (HFT)** - Automated trading using high-speed computers and algorithms.

**Implementation Shortfall** - Difference between paper portfolio and actual portfolio performance.

**Latency** - Time delay in order execution, critical in high-frequency trading.

**Market Making** - Providing liquidity by continuously quoting bid and ask prices.

**Mean Reversion** - Tendency for prices to return to long-term average.

**Momentum** - Tendency for asset prices to continue moving in the same direction.

**Order Book** - Electronic list of buy and sell orders organized by price level.

**Pairs Trading** - Market-neutral strategy trading correlated securities.

**Slippage** - Difference between expected and actual execution prices.

**Technical Analysis** - Method of evaluating securities using price and volume data.

**TWAP (Time-Weighted Average Price)** - Benchmark and execution strategy.

**VWAP (Volume-Weighted Average Price)** - Benchmark weighted by trading volume.

---

## Market Microstructure

**Bid-Ask Spread** - Difference between highest bid and lowest ask prices.

**Dark Pool** - Private exchange for trading securities away from public markets.

**Electronic Communication Network (ECN)** - Automated system matching buy and sell orders.

**Limit Order** - Order to buy or sell at specific price or better.

**Liquidity** - Ease of buying or selling assets without affecting price.

**Market Impact** - Effect of trading on asset prices.

**Market Maker** - Entity providing liquidity by quoting bid and ask prices.

**Market Order** - Order to buy or sell immediately at current market price.

**Price Discovery** - Process of determining asset prices through supply and demand.

**Tick Size** - Minimum price increment for trading.

**Volume** - Number of shares traded in a security or market.

---

## Credit Risk

**Credit Default Swap (CDS)** - Financial derivative providing protection against credit events.

**Credit Rating** - Assessment of creditworthiness by rating agencies.

**Default Probability** - Likelihood of borrower failing to meet obligations.

**Expected Loss** - Probability of default × Loss Given Default × Exposure at Default.

**Exposure at Default (EAD)** - Amount owed if default occurs.

**Loss Given Default (LGD)** - Percentage of exposure lost if default occurs.

**Merton Model** - Structural model treating equity as call option on firm assets.

**Probability of Default (PD)** - Likelihood of default within specific time period.

**Recovery Rate** - Percentage of exposure recovered after default.

**Survival Probability** - Probability of no default within specific time period.

---

## Regulatory and Compliance

**Basel III** - International regulatory framework for bank capital adequacy.

**Capital Adequacy Ratio** - Measure of bank's capital relative to risk-weighted assets.

**Dodd-Frank Act** - US financial reform legislation following 2008 crisis.

**MiFID II** - European regulation on investment services and activities.

**Risk-Weighted Assets** - Bank assets weighted by risk for capital requirement calculations.

**Stress Testing** - Regulatory requirement to assess bank resilience under adverse scenarios.

**Tier 1 Capital** - Core measure of bank's financial strength.

**Value at Risk (VaR)** - Regulatory measure for market risk capital requirements.

**Volcker Rule** - US regulation restricting banks' proprietary trading activities.

---

## Contributing

This glossary is a living document. To contribute:

1. Fork the repository
2. Add new terms with clear, concise definitions
3. Maintain alphabetical order within sections
4. Include mathematical notation where appropriate
5. Submit a pull request with your changes

## Resources

- **Books**: "Options, Futures, and Other Derivatives" by Hull, "Quantitative Risk Management" by McNeil
- **Journals**: Journal of Financial Economics, Review of Financial Studies
- **Online**: Quantlib, Risk.net, CFA Institute materials

## License

This glossary is provided for educational purposes. Please verify definitions with authoritative sources before using in professional contexts.

---

*Last updated: [Current Date]*
