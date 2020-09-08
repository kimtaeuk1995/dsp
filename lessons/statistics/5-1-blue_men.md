[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

> Code:
```
mean = 178
sigma = 7.7
dist = scipy.stats.norm(loc=mean, scale=sigma)

dist.cdf(185)-dist.cdf(178)
```
