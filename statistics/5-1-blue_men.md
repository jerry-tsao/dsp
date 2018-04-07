[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

34.27% of the U.S. Male population is in the 5'10" - 6'1" range.
```
lower = scipy.stats.norm(loc=178, scale=7.7).cdf(70*2.54)
upper = scipy.stats.norm(loc=178, scale=7.7).cdf(73*2.54)
print(upper - lower)
0.34274683763147457
```
