[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

> Code:

```
def generate_random_number(num):
    random_number = []
    for _ in range(num):
        random_number.append(random.random())
    return random_number

random_list = generate_random_number(1000)

pmf = thinkstats2.Pmf(random_list, label = 'PMF')
thinkplot.pmf

cdf = thinkstats2.Cdf(random_list, label = 'CDF')
thinkplot.Cdf(cdf)
```
