# Dataset & Main Goals

I chose to investigate the Loan Data From Prosper.
My main goals was to investigate what variables were most impactful in predicting estimated returns.

## Key Findings

1)There are a very large range of values, from about -20% at the lowest, to about 30% at the highest but the general shape of the graph is close to a normal distribution. However, the curve ramps up starting at around 4%, peaks at around 8% then slowly slopes down to 17.5%. There are a few abnormal peaks and valleys on the way down. All of this is represented in a histogram.

2)Lender yields has the general shape of a normal distribution except at around 30%-31% there is a massive spike in quantity of loans at those rates. I thought that may be due to restrictions set by the state, but evidence in my exploratory analysis did not lend credence to that belief.

3)A heat map between the categorical variables surprisingly showed that the length of a loan had little impact on the estimated effective yield and employment status had little correlation with estimated loss.

4)Prosperity score was the best indicator of what yield was going to be on a loan. Since people with higher prosperity typically lead to less losses (chargeoffs), lenders are willing to lend to them for a lower yield. Additionally, although the lowest prosper score had the highest estimated loss, it still had the highest predicted yield.
The highest group of lending rates is around 30%.

### Sources
I used Udacity's lessons as the primary resource for the creation of this project.


```python

```
