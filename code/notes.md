Here, you can see that I'm importing a whole bunch of functions and libraries that I will use later. The imports section of any script is basically like a spoiler for what's going to happen in it.

We are going to use a library called darts, which makes it super easy to deal with timeseries data and do a whole bunch of things with them.

For this notebook, we're going to use a standard timeseries dataset. What do you think this contains?

Describe how the plotting works.

Is there a trend? Is there seasonality? Is it stationary?

Conveniently, there exists a function to check if the series is seasonal.

But if you don't trust the function output and want to see for yourself, we can extract the trend and seasonality from the data and plot them.

Wth does that mean?
So, we can think of a time series as a combination of many series: the trend, the seasonality and the noise, which is basically whatever is left. This combination can either be additive, or multiplicative.

How to check which one we used? Hover.

There is also a function to check if the series is stationary. I have no idea what it does, but I can find out if I hover over it. The important part is that the second number it returns is the p-value for the test.

##### Minor explaination about p-values

In statistics, you normally start out with an assumption (which is also called the null hypothesis). You then do some sort of test, and calculate the probabilty of observing what you observed **assuming the null hypothesis is true**. This probability value is called the p-value. The p-value tells us if a test is statistically significant or not. If the value is below 0.05, it means that the series is stationary. If not, it's not.

A p-value of 0.05 means, that given the null hypothesis, in this case, the series is not stationary, there is a 5% chance of seeing what you're seeing. So, this means that either what you're seeing is extremely rare, or more likely, the null hypothesis is false.

In this case, the p-value is quite high, so we can say with certainity that the series is not stationary. Although we didn't need a computer to tell us that, we could see that with our own eyes. But, it's always a good idea to validate what you see, or rather, what you think you see.

Now, we can transform our series and make it stationary.

##### Do a model world tour

This meeting could have been an email? More like this cell could have been a function.

Get them to make the MAE as low as possible for like 10 min?
