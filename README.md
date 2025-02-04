**Problem Set 1 Stock–Market**

1. 
For a stock exchange of your choice, please download at least ten years of daily
data for the stock market index and five individual stocks. You can either download the
prices and then compute daily returns or else you download the returns series directly.

2.
Find the bond yield of a short term government bond for the country the stock
exchange you chose is located in. Download it and provide the database and header info.
The shorter term the horizon, the better. We will use this data as a proxy for the risk
free interest that could be earned.

3.
Make a table with descriptive statistics, where for each series (bond yield, index
return, individual stock returns) you report the mean, standard deviation, minimum and
maximum.

4.
Make one figure where you plot the bond yield, the index return, and one individual
stock return of your choice.
Make sure your table and figure look reasonable.


****
**Denote the index return for period** \( t \) **with** \( r^M_t \) **and the stock return for period** \( t \) **with** \( r^i_t \).  
Let \( r^f_t \) denote the risk-free rate. Compute excess returns \( x_t \) by subtracting the risk-free rate (i.e. bond yield) from the index return and individual stock returns:

$$
x^M_t = r^M_t - r^f_t
$$

$$
x^i_t = r^i_t - r^f_t
$$

Compute the alpha^i and beta^i for each stock \( i \) by regressing:

$$
x^i_t = \alpha^i + \beta^i x^M_t + \epsilon^i_t
$$

In the table above, add two columns that report for each stock \( i \) the estimated alpha^i and beta^i
