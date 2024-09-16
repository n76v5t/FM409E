java c
FM409E: Risk Management in Financial Markets, LSE
Summative Problem Set
Turn in your solutions using the submission link on Moodle by the stated deadline.Please follow the ofﬁcial submission instructions carefully. In addition, the solution to the problem set should be submitted as a single document in a format which is easily printable. Please summarize your results in tables and/or ﬁgures and discuss them as appropriate. Do not submit any spreadsheets or other work ﬁles. The word limit is 2000 words.
1.  (80 Marks) Go to Yahoo inance (http://finance.yahoo.com) and download daily data for the Nikkei 225 index from January 5, 1965 until December 15, 2023 (the ticker for the Nikkei 225 index is ˆ N225).   Use the one to the last column of the downloaded data, i.e. the “adjusted closing prices.”
(a)  (20 Marks) Calculate daily log returns expressed in percent using these ad- justed closing prices as:

where Pt is the closing price on day t and ln denotes the natural logarithm. Provide the following summaries of the data:
i.  Plot the closing prices, returns, and squared returns over time.
ii.  Calculate the mean, standard deviation, skewness, and kurtosis of re- turns.
iii.  Compute and plot the irst 20 autocorrelations of returns and of the squared returns.
iv.  Plot a histogram of the returns with the normal distribution depicted as well.
Comment on the above indings.
(b)  (60 Marks) Consider an European call, and an European put option on the above Nikkei 225 index issued at-the-money (at the end of the trading day) on 2023-09-19 and with expiration on 2023-12-15 (i.e.  60 trading days fol- lowing the issuance).  In your calculations:  assume a continuously com- pounded interest rate of 0.1% per year; set the volatility parameter using the index return volat代 写FM409E: Risk Management in Financial MarketsPython
代做程序编程语言ility estimate obtained using the 60 trading days be- fore the issuance of the options.
i.  (20 Marks) Compute the Black and Scholes prices at each date from issuance until maturity and plot your results. Also plot the difference between the price of the underlying and the strike price of the options. Interpret your results.
ii.  (20 Marks) For each of the two call options compute and plot the fol- lowing ‘greeks’ at each date from issuance to expiration: △; Γ; Vega. Interpret your results.
iii.  (20 Marks) Consider a dynamic trading strategy (implemented via daily rebalancing) that aims to replicate a portfolio that is long the above put and call (one unit of each, from issuance to expiration).
A.  Compute the initial portfolio position and explain your calculations.
B.  Compute and plot the trading strategy at each date.C.  Plot the evolution of the components of the replicating portfolio.D. At every point in time, compute and plot the daily tracking error i.e. 	the difference in value between the portfolio of options (evaluated using the Black and Scholes prices) and its replicating strategy.
What drives the above tracking error? Comment on the above indings.
2.  (20 Marks) Suppose that at time 0 you observe the prices of a zero coupon bond with maturity in one year, P(1), and of a zero coupon bond with maturity in two years, P(2).
(a)  Suppose P(2) > P(1).  Is there an arb itrage opportunity available on this market?
(b) What does your answer above imply for the prices of zero coupon bonds with different maturities when there are no arb itrage opportunities on the market?
(c)  In light of the answer given at point (b) above, can forward rates be negative in the absence of arb itrage opportunities?







         
加QQ：99515681  WX：codinghelp
