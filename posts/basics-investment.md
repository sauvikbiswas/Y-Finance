$ post_id : basics-investment
$ post_title : 02: Understanding investments
$ post_group : 03: Creating an investment plan
$ post_last_update: 2021-05-20

## Time-horizon of an investment

Planning an investment requires three things--namely, an understanding of the duration for which the investment will be made, the average growth of the investment during the said duration, and the variation of the growth.

If you invest in a fixed deposit for a 2-year term, you can be certain that the amount you had invested would have a predictable growth. You would also know the value at maturity upfront. (The bank would have mentioned it on their website.) You can compute how much you would get if you decide to liquidate it prematurely after one year. Every last bit of it is predictable. The variation is zero.

The story with debt funds is similar. Let us look at the evolution of the net asset value of a debt fund that only invests in 3-4 year maturity bonds.

![NAV of a Debt Fund](NAV-Debt-Fund.svg)

The evolution is predictably linear. The R-square value--that shows how well the evolution follows the linear trend--is close to 1.0. It would have been 1 if it had no variation. Still the variation is negligible.

What about the evolution of money invested in equity? You can be almost sure that if you invest some amount in the market for 10-20 years, you will get positive returns. Please note that I use the word "market" and not any particular company--i.e., you invest in all companies that constitute say, Nifty 50, in proportion to their sizes. (Here size refers to their market capitalisation.) This is the evolution of the value of market index between the same period.

![NIFTY 50 Evolution](NIFTY50-Index-Value.svg)

The trend line is a poor excuse for a linear fit. The innumerable jitters in the graph points to the huge variation that this index experiences as the market goes up and down. Instead of making sense of these numbers, let us do a different exercise. What would have happened if you had invested 10,000 rupees in 2011 and liquidated it in 2021? What about investing in 2012? What about the next year? And the next? The following graph shows how much would 10,000 rupees invested on January of each year from 2011 to 2020 become in January 2021.

![How 10k changes](Value10k-DOI.svg)

Let's say you had invested 10,000 rupees in the market in 2011 and your neighbour had invested 10,000 rupees in 2012. You both liquidate the money in 2021. You will be jealous of the fact that your neighbour managed to rake in 30,233 rupees in 9 years while you were left with 22,766 rupees, and that too when you had it in the market for an additional year. This is because there was a significant fall in the market from January to December 2011. There is a very less chance that either you or your neighbour could have accurately predicted that event. It might be that you had some money to invest in 2011 while your neighbour could only scrape that money for investing in 2012 after working really hard in 2011. To that you should say, "Lucky him!"

Did you know what would have happened if you had invested 10,000 rupees in the market in January 2015 and decided to liquidate it after one year? You would get back 9,613 rupees. Ouch!

I am sure you would have guessed where I am going with this. There is a set of thumb rules that can help you decide what kind of instrument you should invest in depending on how long you would want to invest for.

| Time-period of investment | Possible investment instruments                             |
|---------------------------|-------------------------------------------------------------|
| <2 years                  | Cash reserve, Short-term bonds, Fixed Deposit, Liquid Funds |
| 2-5 years                 | Fixed Deposit, Long-term bonds, Debt funds                  |
| 5-10 years                | Hybrid Funds                                                |
| >10 years                 | Equity Funds, Index Funds, Stocks                           |

Please keep in mind that the type-breaks at 2, 5, and 10-years are not hard and fast. These boundaries are fuzzy. You can have cash reserve for some purpose that would materialise after 3 years. You can also have investments in Equity Funds for another event that's 9 years away.

Actually, the above information is neither complete nor concrete. There is another truth that must be addressed before you start investing.

## Your target gets closer everyday

> What good is a rate of return if you do not have the corpus when you need it?

> --Ancient jungle proverb

Imagine that you need a couple of lakhs for your child's college when she turns 16. You wouldn't hope that the market would do well on her 16th birthday, would you? That would be wishful thinking. A sudden catastrophe like the recent pandemic can crash the value of your entire investment the day before you had decided to liquidate it to fund her education.

The way to mitigate this lies in the information provided in the earlier table. On her 1st birthday, the goal is 15 years away. In case there are ups and downs and sudden jumps in the market, there's enough time for your investment to recover and give good returns. On her 14th birthday, the goal is only 2 years away. At this point you would not want the fluctuations in the market to affect your investment. It would be good if you had your investment in a debt instrument. That way, you are sure that you will get your corpus when she turns 16.

Between these two extreme ends lies the actions that you must perform. As your goals get closer, you must systematically move your money from equity instruments to debt instruments, culminating in a situation where 2-3 years before your goal, your only exposure is in debt instruments.

You can choose any way to taper it. The following chart shows a linear taper where you start your equity exposure at 80% and ramp it down to 0% by the end of the 14th year. As evident from the graph, it's 100% debt exposure for the 15th and the 16th year.

![Exposure taper linear](Exposure-time-linear.svg)

If you want to play it safer, you might want to choose a logarithmic taper. In this case, the equity exposure declines much more rapidly. This is how the exposure curves would look like--

![Exposure taper log](Exposure-time-logarithmic.svg)

Personally, I use the logarithmic taper as I am more risk-averse than most people. If you are a risk-averse person like me, you should use the same.
