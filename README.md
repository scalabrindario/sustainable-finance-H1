# Sustainable Finance Homework 1

## Introduction
The objectives of this homework are the following:
- Evaluate the impact of diversification in portfolio construction
- Build portfolios of stocks based on the mean-variance criterion (effcient frontier)
- Evaluate the effect of imposing restriction on the set of assets

Our Group was asked to look at firms from **emerging countries** with available **environmental scores** (MSCI)

## Exercise 1
#### Compute and report the annualized average return and annualized volatility for all individual assets. Compute the correlation between individual average returns and volatility and comment on the observed correlation.

In our case, the observed correlation between annualized average return and annualized average volatility is ~0.38. As expected, this figure means that these two variables are positive correlated, which implies that they tend to move towards the same direction.
As a matter of fact, volatility is a statistical measure of a security's or market index's return dispersion. Most of the times, a higher volatility of an asset translates into a higher risk premium. By undertaking this risk, investors expect to be remunerated with higher returns.
However, whether we can affirm that investors taking a greater risk could be subjected to greater losses, we cannot state the contrary. Namely, investors taking a greater risk cannot be assured to be remunerated with greater returns.

Another insightful information is represented by the correlation between assets. From our computation, we obtained a positive correlation of ~0.22. As a side note, we cannot forget about the nature of our assets: stocks from developing countries, which are not bounded in a specific area, but are scattered worlwide. Therefore, they are not affected by the same regional trends.
Modern portfolio theory (MPT) frequently uses correlation to assess the degree of diversification among the assets in order to establish the most optimal frontier in a portfolio.

## Exercise 2
#### Form an equally-weighted and value-weighted portfolio with monthly rebalancing. Re-port the following statistics for both portfolios: annualized average return, annualized volatility, minimum return, maximum return, and Sharpe ratio. Plot the time series of returns for both portfolios.
```
**RESULTS**

Portfolio type:  Equally Weighted Portfolio 

Annualized Return:  0.17310842608783353
Annualized Volatility:  0.18754053111886498
Minimum Return:  -0.2552462808361818
Maximum Return:  0.21575172858709732
Sharpe Ratio: 0.8577121625347975
________________________________________________

Portfolio type:  Market Value Weighted Portfolio 

Annualized Return:  0.1876058785111936
Annualized Volatility:  0.18285317784548893
Minimum Return:  -0.22880895916692642
Maximum Return:  0.2078214760071684
Sharpe Ratio: 0.9589838634383476
________________________________________________
```
For the second exercise, we built an equally and a market-value weighted portfolio.
In the former case, the portfolio offers investors two key benefits: reduced concentration risk and increased allocation into smaller stocks. However, there are also some downsides. For instance, equal-weighted portoflio tends to have higher stock turnover than market-value weighted portfolio, which will lead to higher transaction fees.
From our computations, we can see that in the Market-Value Weighted Portfolio offers a slightly higher annualized return compared to the Equally Weighted one. However, this is not reflected in the annualized volatility, since the portfolio with the lowest annualized volatily is the one with highest annualized return.
Those information are also embedded in the Sharpe Ratio, indeed, market-value weighted portfolio has an higher sharpe ratio. Nevertheless, both portfolios have a sharpe ratio smaller than 1, which means that they are not considered "acceptable" by investors.

<p align="center"><img src="https://drive.google.com/uc?id=1Qq3cbT1rN35bOvlB1aDzM4T-wSUXm50N" width="800"/></p>


As we can see from the image above, the two portfolio have similar returns/trends.

## Exercise 3
#### Supposed that you invested 100% of your wealth in the asset with the highest annualized average return computed in point 1. Compare the annualized average return and annualized volatility of this one-asset portfolio with the equally-weighted and value weighted portfolios? What explains the differences between a one-asset portfolio and a portfolio composed of many stocks? What if you invest 100% of your wealth in the asset with the highest average return computed over the first 2 years?

```
Best Asset: 
index                    US62914V1061
annualized_return             1.69139
annualized_volatility         1.25656
```

<p align="center"><img src="https://drive.google.com/uc?id=1d--0Nm19eVZVtkwvZ7VnAXCR9iTFGSMA" width="800"/></p>


The ISIN "US62914V1061NIO" corresponds to NIO, a Chinese firm operating in the automotive industry, especially active in building electric cars. NIO is our best performing asset in terms of annualized average return (~169%).
As we can see from the graph above, the asset has a strong positive trend (Red dashed line), mainly driven by the results obtained from end 2019.
This asset significantly outperforms the equally weighted portfolio return (17%) and the value weighted portfolio return (~19%).
However, we can notice that the annualized average volatility of NIO is likewise high (~126%). Once again, compared to the equally weighted portfolio volatility (18%) and the value weighted portfolio volatility (20%), NIO is not representative of the whole population.
With a portfolio composed of many stocks (a.k.a. a diversified portfolio), we can limit the firm-specific risk. While with a one-asset portfolio there is no diversification of the firm-specific risk, meaning that this strategy is extremely hazardous.

```
Compounded Return:  2.297000000000001
```

In the first 2 years the one-asset portfolio obtained a compounded return of ~230%.
This result means that by investing $1 on the primary market when NIO was listed, you would have obtained ~\$230 after 2 years.
However, by investing 100% of the wealth in this asset a person would undertake an enormous risk, given the high volatility (~126%)., performing worse than if he/she had invested in one of the two portfolios.

## Exercise 4
#### For this question, limit your set of firms to 50 randomly selected firms. Build an optimal portfolio with minimum variance with monthly rebalancing. Report the following statistics: annualized average return, annualized volatility, minimum return, maximum return, and Sharpe ratio. Comment on the reported statistics in comparison with the equally-weighted and value-weighted portfolio.
```
*** Min Variance Portfolio with monthly rebalancing ***
Annualized Return:  0.006799299209266268
Annualized Volatility:  0.1366580531168425
Minimum Return:  -0.016730211678433755
Maximum Return:  0.037651416301920884
Sharpe Ratio: -0.03990494702144253
```

##### Results
| Statistics | Equally Weighted | Market-value Weighted | Minimum Variance |
| --- | --- | --- | --- |
| Annualized Return | 17.28% | 18.76% | 0.07% |
| Annualized Volatility | 18.33% | 18.55% | 13.66% |
| Minimum Return | -25.50% | -23.08% | -1.67% |
| Maximum Return | 21.59% | 21.30% | 3.38% |
| Sharpe Ratio | 0.85 | 0.95 | -0.04 |

In the table above, we can see summarized the main statistics of the three portfolios computed by now.
In terms of sharpe ratio, all the portfolios are below the "minimum acceptance" threshold (<1). Focusing on the return, the Minimum Variance Portfolio is the worst one, since its return is below 2% level, which is often considered the same return of the risk-free rate. For this reason, it would not make any senses to choose the minimum variance portfolio, given the 13.66% volatility.
Additionally, the minimum variance portfolio is the "safest" between the three, and this is also recognizable from the minimum return of -1.67%.
At the same time, the other two portfolios are slightly missing the acceptable threshold of 1. In terms of annualized average return, the equally-weighted portfolio slightly outperforms the market-value weighted portfolio (18.76% vs 17.28%). Therefore, also in this case, the best portfolio is the Market-value weighted.

<p align="center"><img src="https://drive.google.com/uc?id=1NZKXJZ6rlabvus_fEYBYSsEJ9T9jgd8Y" width="800"/></p>

As we can see, compared to the other two portfolios, the minimum variance one has always a constant return, which is almost always positive. Even during 2008 financial crisis and 2020 Covid market crash, the minimum variance portfolio resisted compared to the other two. This is also partially explained by the fact that the portfolio is built to minimize volatility, using the ex-post covariance matrix (i.e. Covariance Matrix computed at the end of 2020).

<p align="center"><img src="https://drive.google.com/uc?id=1f1JPpe2Btu1uhsczdkW_G_nUbub7doXx" width="800"/></p>

As we can see, the volatility of the three portfolio decreases with years. At the same time, the volatility of the minimim variance portfolio needs to be further investigates since it decreases sharply in appareantly random periods.
It is important to mention that the equally weighted and market value weighted portofolios are better representative of the market trends, since they include more than 1.000 companies. While, the minimum variance portfolio is a mix of 50 random selected companies.

<p align="center"><img src="https://drive.google.com/uc?id=1e7UhOhpJ3EAonOOuBy9ZFG_LHun2z4wh" width="800"/></p>

In the plot above, we tried to investigate the reason behind the sharp decrease of volatility displayed in the graph "Volatility of Three Portfolios". We can observe that a rapid decrease in volatility corresponds to a increase in the number of companies available. We considered only available companies, because in several months we didn't have information for some companies (i.e. Nan values).

## Exercise 5
#### For this question, keep the same randomly selected firms from the previous point. Build an optimal portfolios with various target portfolio returns (e.g., from 2% to 16% with 2% increments). Plot the efficient frontier as well as the individual assets. Which portfolio is the most efficient in terms of Sharpe ratio?
```
Expected annual return: 2.0%
Annual volatility: 12.6%
Sharpe Ratio: 0.06

Expected annual return: 4.0%
Annual volatility: 22.8%
Sharpe Ratio: 0.12

**********************************************

Max possible return:
Expected annual return: 5.8%
Annual volatility: 47.3%
Sharpe Ratio: 0.10
```
<p align="center"><img src="https://drive.google.com/uc?id=1hihF1ZIoSLmyzzFRSksmUHthnMR2iRTR" width="800"/></p>

From the image above, we can see our Efficient Frontier in terms of mean variance. It's interesting to see how individual assets are sub-optimal compared to efficient diversificated portfolio, meaning that that they cannot provide the same level of return for a given risk.
All rational investors will invest in this frontier given their risk adversion and utility function. In order to have the highest return possible, you should invest 100% of your wealth in the asset with the higheset return.

```
*** Most efficient portfolio in term of sharpe ratio ***
Expected annual return:  4.000000000000003 %
Annual volatility:  22.777187773238214 %
Sharpe Ratio:  0.12182087050120437
```

The most efficient portfolio in terms of Sharpe ratio is the portfolio with 6% of expected annual return. However, this portfolio has a Sharpe ratio of 0.12, which is usually considered not acceptable by investors (i.e. below the "critical" threshold of 1).

## Exercise 6
#### Choose an appropriate benchmark, which should correspond to the region of your dataset. Compare the performance of your portfolios (equally-weighted, value-weighted, and minimum variance) with the benchmark. Comment on the differences.

We decided to pick as a benchmark the MSCI Emerging Markets Index, which is a selection of stocks that is designed to track the financial performance of key companies in fast-growing nations.
Then, we retrieved historical data from [this source](https://backtest.curvo.eu/market-index/msci-emerging-markets).

<p align="center"><img src="https://drive.google.com/uc?id=1Z6pxXd75JwQZWp_AVclSKuXlKDXMQJI1" width="800"/></p>

```
*** MSCI Emerging Market Index ***
Annualized Return:  0.07338925370573134
Annualized Volatility:  0.1794804317958342
Minimum Return:  -0.18549312285868358
Maximum Return:  0.16946313913526434
Sharpe Ratio: 0.3406311290599591
```

##### Results
| Statistics | Equally Weighted | Market-value Weighted | Minimum Variance | MSCI Emerging Market Index |
| --- | --- | --- | --- | --- |
| Annualized Return | 17.28% | 18.76% | 0.07% | 7.34% |
| Annualized Volatility | 18.33% | 18.55% | 13.66% | 17.95% |
| Minimum Return | -25.50% | -23.08% | -1.67% | -18.55% |
| Maximum Return | 21.59% | 21.30% | 3.38% | 16.95% |
| Sharpe Ratio | 0.85 | 0.95 | 0.05 | 0.34 |

As we can see from the table above, the MSCI Emerging Market Index has a return of 7.34%, which is massively lower compared to our Equally Weighted and Market-value Weighted portfolios, but this difference is not mirrored in the volatility, since it is just 1% point lower than the other two. This negative performance is also relfected in a lower sharpe ratio (0.34).
In conclusion, for the time period taken into account, we can state that Equally Weighted and Market-value Weighted portfolios perform better than the MSCI Emerging Market Index.

## Exercise 7
#### Compute and comment on the simple correlation between returns, volatility, size
|  | annualized_return | annualized_volatility | size | 
| --- | --- | --- | --- |
| annualized_return | 1.000000 | 0.381584 | -0.000103 |
| annualized_volatility | 0.381584 | 1.000000 | -0.005272 |
| size | -0.000103 | -0.005272 | 1.000000 |

The correlation between annualized average return and annualized average volatility is 0.38. Once again, this means that the two variables are positevely correlated.
Secondly, the correlation between annualized average return and size (in terms of market cap), and the correlation between annualized average volatility and size (in terms of market cap) are in both cases close to zero. This means that there is no correlation between these two variables and the size, therefore, the size of a company is not a good predictor for returns and/or volatility.

## Exercise 8
#### For this question, take the same 50 selected firms. You now create a minimum variance portfolio with monthly rebalancing with an additional constraint: you exclude the smallest firms (bottom tercile of the distribution of the firms’ market capitalization in month t − 1). Report summary statistics on the performance of this portfolio and comment on the differences with the minimum variance from exercise 4.

```
*** Min Variance Portfolio with monthly rebalancing of top tercile***
Annualized Return:  0.007196386382912947
Annualized Volatility:  0.13801135761830224
Minimum Return:  -0.020477771529280254
Maximum Return:  0.03776329694748181
Sharpe Ratio: -0.036636442705088444
```

<p align="center"><img src="https://drive.google.com/uc?id=1LErmoV7FjcLJKfRbgut-uJOLJJrAYbd2" width="800"/></p>

##### Results
| Statistics |Minimum Variance | Minimum Variance no bottom tercile |
| --- | --- | --- |
| Annualized Return | 0.07% | 0.72% |
| Annualized Volatility | 13.66% | 13.80% |
| Minimum Return | -1.67% | -2.04% |
| Maximum Return | 3.38% | 3.78% |
| Sharpe Ratio | -0.04 | -0.04 |

As we can see from the graph above (and also from the table), excluding the firms with the smallest market cap means excluding the firms with the highest growth potential. This is reflected in the return, since the purple portfolio has a return lower than the green one. 

At the same time, the volatility is almost the same, which means that bigger companies are not less volatile than smaller ones. Given the low return, even in this case, it would result more convenient to invest in risk free rate assets.

## Exercise 9
#### For each time period, sort firms based on size into quintiles. Create equally-weighted and value-weighted portfolios for each time period and each size quintile. Report the average returns for each quintile portfolio as well as a portfolio that goes long in the lowest quintile and short the highest quintile. Comment on your results. What can explain the relationship between returns of your portfolio and firms’ size? Repeat this exercise but sorting firms based on past stock returns. Compute past returns in month t as the cumulated return of a firms between months t − 13 and t − 1. 


### Based on Sizes
<p align="center"><img src="https://drive.google.com/uc?id=1HF6Ih2PXFvztolV9jjjms4hbUoPvzJU5" width="800"/></p>
From the histogram above, for each month, we created five portfolios, and we plotted the average return for each portfolio. We can observe that for relatively small-sized companies (first quintile) a value-weighted portfolio strategy tends to be more valuable, while for relatively big-sized companies (fifth quintile) the opposite seems to be true, namely the equally weighted strategy tends give back higher returns. A possible explanation is that in the extremes of the distribution the difference in sizes can be significant.

Contrary to what happens in the extremes, in the second, third and fourth quintiles there is no dominant strategy (Equally vs Market value weighted).

Given the correlation computed in exercise #7, we were expecting that all the quintiles would have been on the same level (i.e. similar return), but this is not the case because mentioned correlation was computed between average annualized average values, while in short-term we can see that there is a relevant correlation between size and return.

It is interesting to notice that we divided our companies into quintiles according to their size. However, we haven't taken into account any measurement scale, a proper threshold to identify which companies are actually small, mid or big-sized. For this concern <a href="https://www.merrilledge.com/article/company-size-why-market-capitalization-matters-ose">Bank of America</a> suggests three reliable thresholds:
- less than 3 billion market cap for small-sized
- between 3 and 10 billion for mid-sized
- more than 10 billion for big-sized companies. 

With this kind of measurement scale, the strategy used above would make way more sense, since we would have been sure to go long on firms with a small market cap, and therefore an higher return potential, and short sell on the firms with a big size, meaning those which already reached their plateau and therefore more subjected to potential losses.

<p align="center"><img src="https://drive.google.com/uc?id=1_ZApGOCKMwxMlA7bY8e2qVqZJAq5aGYO" width="400"/></p>

```
*** Equally Weighted Portfolio ***
Return of the strategy: -0.0766873986146018

*** Market Value Weighted Portfolio ***
Return of the strategy: -0.03888726381255231
```
The results displayed in the graph above are based on the following strategy: each month (t) we rely on the companies' size of the previous month (t-1) since we want to go long on the assets with the smallest size (first quintile) and short sell the assets with the biggest size (fifth quintile).
According to this strategy the smallest firms should drive the overall positive returns in upcoming month (t), while the firms with the biggest size should have already reached their target value and therefore they should have had negative returns in the next month (t).

However, this is not the case. As seen in the graph plotted in the previous chunck of code, high capitalized companies on average return more than the smallest ones. As a consequence, the returns of both portofolios are negative.
Addionally, we can remark that short-selling is not profitable since in the last years (i.e. time horizon taken into account) the markets have always increased, and this is also shown in the exercise #6, when we considered the MSCI Emerging Markets Index.

### Based on Returns
<p align="center"><img src="https://drive.google.com/uc?id=12OLqgn-lDcrCTH_oyRveVCLjn3HizoV-" width="800"/></p>

From the graph above, we can observe that the companies with lowest return in t-1 (first quintile) tend to outperfom the following month (t). On average, the overall returns of this strategy is lower compared to the previous one (based on sizes).
At the same time, it is relevant to highlight that the market-value weighted portoflios outperform the equally weighted ones four out of five. A possible explanation of this pattern is that large companies, which faced a negative return, are more prone to have a rebound effect.

<p align="center"><img src="https://drive.google.com/uc?id=1x_l0N8kvixau8jrUnBJRlRNT5Zi4SE6p" width="400"/></p>

```
*** Equally Weighted Portfolio ***
Return of the strategy: -0.0766873986146018

*** Market Value Weighted Portfolio ***
Return of the strategy: -0.03888726381255231
```

In the graph above, we can see that the market-value weighted portfolios, performed better compared to hte equally weighted one, in both the cases (first and fift quintiles). Once again, this pattern can be explained by the fact that larger companies tend to outperform smallest ones. This extremely relevant, since market-value weighted portfolios have almost doubled the return of equally weighted one.
Addionally, we can remark that short-selling is not profitable since in the last years (i.e. time horizon taken into account) the markets have always increased, and this is also shown in the exercise #6, when we considered the MSCI Emerging Markets Index.
Finally, it is interesting to point out how this return-sorted strategy has (in both the cases) a positive return, which is better than the size-sorted strategy.

### Based on last 12 months cumulative sum
<p align="center"><img src="https://drive.google.com/uc?id=1kKFfwZIT16b2f1gXOGZR5iBfhNK0MCyO" width="800"/></p>

In this case, we created different quintiles based on the average returns of the last 12 months. This strategy differs from the previous one (i.e. monthly based return sorted), because the average return of one year is less sensitive to monthly perfomances. Therefore, the same companies can be found more often in the same quintiles.
Once again, market-value weighted portfolios have better perfomances compared to equally weighted ones in the majority of the quintiles. Therefore, the market sizes help to drive up the returns.

```
*** Equally Weighted Portfolio ***
Return of the strategy: -0.006469398338391247

*** Market Value Weighted Portfolio ***
Return of the strategy: -0.004654537174045931
```

Also in this case, we can remark that short-selling is not profitable since in the last years (i.e. time horizon taken into account) the markets have always increased, and this is also shown in the exercise #6, when we considered the MSCI Emerging Markets Index.
