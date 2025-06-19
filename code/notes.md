Here, you can see that I'm importing a whole bunch of functions and libraries that I will use later. The imports section of any script is basically like a spoiler for what's going to happen in it.

We are going to use a library called darts, which makes it super easy to deal with timeseries data and do a whole bunch of things with them.

For this notebook, we're going to use a standard timeseries dataset. What do you think this contains?

Describe how the plotting works.

Is there a trend? Is there seasonality? Is it stationary?

Conveniently, there exists a function to check if the series is seasonal.

But if you don't trust the function output and want to see for yourself, we can extract the trend and seasonality from the data and plot them.

There is also a function to check if the series is stationary. I have no idea what it does, but I can find out if I hover over it. The important part is that the second number it returns is the p-value for the test.

The p-value tells us if a test is statistically significant or not. Right now, the details of what this means don't matter too much. If the value is below 0.05, it means that the series is stationary. If not, it's not.
In this case, the p-value is quite high, so we can say with certainity that the series is not stationary. Although we didn't need a computer to tell us that, we could see that with our own eyes. But, it's always a good idea to validate what you see, or rather, what you think you see.