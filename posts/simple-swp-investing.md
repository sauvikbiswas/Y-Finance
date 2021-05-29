$ post_id : simple-swp-investing
$ post_title : 05: A simple systematic withdrawal-based investment template
$ post_group : 03: Creating an investment plan
$ post_last_update: 2021-05-29

## Creating a systematic withdrawal plan

Not all goals have a target date. Some require regular withdrawal after a maturity date in order to sustain something. The simplest example would be your retirement plan. You would need a steady flow of money every year in order to survive. For all practical purposes, you would also need to adjust your withdrawals for inflation.

Have a look at this spreadsheet--[link](https://docs.google.com/spreadsheets/d/1eXnMavUq3408k825HEOifM8UYNlJvXJcDagvwKoaxkY/edit#gid=0). It is modified from the simple goal-based investment template that we have encountered earlier. There is a new section in the "Data" worksheet that takes the withdrawal parameters.

![Simple SWP-based investment settings](SWP-based-investment-settings.jpg)

There is a parameter which lets you fix when would the withdrawal start, another that let's you set what would be the first withdrawal amount and a third one that allows you to set how the withdrawal should change year-on-year. The third parameter is especially useful for use-cases like retirement as your expenses would be affected by inflation.

This is how our modified spreadsheet looks like--

![Simple SWP-based investment spreadsheet](SWP-based-investment-chart.jpg)

There can be an overlap in the investment and withdrawal timelines. I would suggest that you play around with the parameters in the "Data" worksheet and see how the spreadsheet evolves.

## How long can you sustain?

The spreadsheet gives you some data to visualise how the corpus evolves with time. Using the above data, we can compute that our corpus will sustain us for 32 years after we have stopped investing.

![Corpus vs Year with withdrawal](Corpus-vs-Year-withdrwal.svg)

In fact, there is no need for us to taper our equity exposure to zero. You can set a date for *"Year when equity % = 0"* that is far beyond the date that would exhaust our corpus. For example, setting it to 2080 would extend our corpus to 38 years after we have stopped investing. Please note that you will still have to do a rebalancing every year to hit your target equity and debt ratios.

![Corpus vs Year with non-zero equity](Corpus-vs-Year-non-zero-equity.svg)

This is a good place to stop and reflect if you can sustain yourself or your family after retirement. This is where the exercise where you had computed a minimum survival cost would come very handy. I had also asked you to document the lifestyle associated with it. In the **Financial Independence / Retire Early** (FIRE) community, this state characterised by a frugal lifestyle is known as *Lean-FIRE*.

Let us look at a realistic Lean-FIRE scenario. It is possible for me and my family to survive on 20,000 rupees a month in 2021. However, I would have to go back to my hometown and trade off a number of facilities that comes with living in a fast-paced city and its higher standards of living.

Let me assume that I would work for 10 more years. How much would I need to invest every year in order to achieve this? Let us assume some of the following parameters:

| Parameter                                   | Rate  |
|---------------------------------------------|-------|
| Average returns from equity                 | 12%   |
| Average returns from debt                   | 6%    |
| Inflation / Yearly increment in withdrawal  | 8.75% |

While I would need 2,40,000 rupees in 2021, accounting for an 8.75% inflation, I would need about 5,55,260 rupees in 2032. If I invest 2,40,000 rupees in 2021 with an increment of 10% per year for the next 10 years and an equity that tapers to zero in 2080, I would survive for 11 years after retirement with that corpus. Ouch! That is definitely not a pleasant situation to be in.

![Corpus vs Year with non-zero equity: Example 1](Corpus-vs-Year-non-zero-equity-example-1.svg)

There are two things that inhibit the growth of the corpus. Firstly, the inflation is much higher than debt returns. Since the reliance on debt instruments is more during retirement, the corpus is bound to shrink. What if we can keep a higher exposure to debt? By setting a *Year when equity % = 0* to 2250 and the taper as linear, our corpus can sustain us for 15 years. During the entire lifetime of the corpus, equity exposure tapers from 80% to 70%. This way we are allowing the market to reward us more but at the cost of higher risk.

![Corpus vs Year with non-zero equity: Example 2](Corpus-vs-Year-non-zero-equity-example-2.svg)

Secondly, we aren't creating a large-enough corpus to sustain us. Even if we take the above example, our total investment is 44,47,480 rupees over a period of 11 years. The corpus grows to a maximum size of 84,48,363 rupees in its 17th year. Thus, even with an aggressive equity exposure (70%-80%), it is impossible to sustain a retirement with a small corpus. At the start of the 18th year, right after the corpus hits its peak value, the withdrawal is 10% of the corpus. This is definitely not sustainable. What if we double the investment and re-adjust our taper so that the equity exposure tapers from 80% to 70% during the lifetime of the corpus? (*Year when equity % = 0* is set to 2400) This time our corpus can sustain us for 35 years. That is a significant improvement.

![Corpus vs Year with non-zero equity: Example 3](Corpus-vs-Year-non-zero-equity-example-3.svg)

This study begs for a question--"Can we plan for perpetuity?"
