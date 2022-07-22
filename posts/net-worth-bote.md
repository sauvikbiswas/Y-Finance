$ post_id : net-worth-tracker
$ post_title : 02: A simple back-of-the-envelope calculation
$ post_group : 04: Tracking your net worth
$ post_last_update: 2022-07-22

# Getting a feel of your assets

Before we dive deep into the world of spreadsheets, it is important to get a rough estimate of where you stand. Start by making a list of every kind of asset you own.

The simplest asset would be cash reserves. This is the money that would be lying in your savings account. If you have followed these articles, most of it would have some purpose by now. The liquidity factor is 1.0--i.e., you will get the entirety of the asset if you withdraw it from the bank. The liquidity time-scale would be instant for anything that is within the ATM withdrawal limits specified by the bank. For anything greater than that, you might have to at most wait for the next working day to visit the bank, fill up a withdrawal form and get the money in your hand. Pragmatically speaking, you can assign a liquidity time-scale of 7 days--i.e., in the worst-case you would need a week to liquidate your savings account.

If you are a salaried employee, you would already have some sort of Provident Fund. If your company's strength is more than 20 people, it is mandatory for them to contribute to Employee Provident Fund(EPF). The liquidity factor of that would depend on the duration for which the account is active. If it is less than 5 years, you will have to pay tax on the withdrawal. The withdrawal limits and taxes depend on the duration of the fund as well as your age, your employment status and certain key events. I would advise you to put a liquidity factor of 0.1 and a liquidity time-scale of 1 month. This would make your estimate very conservative.

You might have also opened a Public Provident Fund(PPF) account along with that. If it is not matured (i.e. completed 15 years), you can set a liquidity factor of 0.8 and a liquidity time-scale of 1 month. This assumes that you will pay a tax of 20% on the corpus. If it is matured, you can bump up the liquidity factor to 1.0. If your income falls in the 30% tax bracket, set the liquidity factor to 0.7.

You might have some Fixed Deposits(FD). Often, there is a penalty on premature liquidation. For most nationalised banks, it is usually around 1%. You can set the liquidity factor to 0.99 for the principal. For the interest, it would be taxed based on your income bracket--set the liquidity factor to either 0.8 or 0.7 depending on the bracket. Liquidation of FD is relatively easy, so liquidity time-scale can be set to 7 days.

You might also have mutual funds and publicly traded stocks. I assume that most of them would have been with you for at least one year. In such a case, figure out how much is the gain and put a liquidity factor of 0.9 on the gain and a liquidity factor of 1.0 on the actual purchase cost of these assets. Overall, if you have made a loss, you can treat the loss as negative gain and put a liquidity factor of 1.0 on that. This assumes that you are paying long term capital gains tax of 10% on the gains made. The liquidity time-scale can be set to 7 days.

You can do the same for gold, too. In the worst case, you can consider a 3% loss on selling the gold and thus the liquidity factor would be 0.97. Even in this case, the liquidity time-scale can be set to 7 days. On a side note, I hope that you are not counting gold jewellery as an asset. Although, technically they are, it is best to buy physical 24 carat gold coins or bars and store them in their sealed state with certification number embossed.

Now let us look into some immovable assets.

The first and the most common one would be real estate. The liquidity factor is 1.0 on the original buying value and 0.8 on the appreciation as the long term capital gains on real estate stands at 20% as of today. The tricky thing is to estimate how long would it take for you to sell the asset at the estimated current price. This is a case where the the appreciation value is a function of the liquidity time-scale. At this point, it's best not to get into complicated formulas. You are still doing a back-of-the-envelope calculation. Just guesstimate the appreciated value and put a liquidity time-scale of 6 months.

The same is true for privately held stocks. It is difficult to liquidate them unless you have someone ready to buy them from you. The other questions to ask would be--What valuation would the company have during the selling of the stocks? At what stock price are you ready to let them go? There is no way other than guesstimating the appreciated value. I would say that it is best to put a liquidity time-scale of 12 months.

>& Make a list of all assets that you own. Set a liquidity factor and a liquidity time-scale against all assets.

# What about your liabilities?

Your liabilities would be mostly from loans. The idea is that how much would you have to pay off to close the loan within a given amount of time. For all liabilities, set your liquidity time-scale to 7 days. The rational behind it is that in the worst-case scenario, you would need to get rid of all debts as fast as possible. Assuming that you have the corpus, the exercise of closing a loan wouldn't take you more than a week.

One of the common liabilities is a home loan. Fortunately, if you pay off the outstanding principal amount you can foreclose the loan without incurring any penalty. Set your liability amount to the outstanding principal amount with a liquidity factor of 1.0.

What if you have a personal loan that has a foreclosure penalty of 10%. Your liability amount would be equal to the outstanding principal but this time the liquidity factor would be 1.1. If you have other loans like car loan, education loan, etc., compute them in the same fashion.

>& Make a list of all your liabilities. Set a liquidity factor for each of them.
