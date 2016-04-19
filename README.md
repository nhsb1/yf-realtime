# rqt (yf-realtime)

![rtscreenshot1](https://github.com/nhsb1/yf-realtime/blob/master/rtq-c.png)

Reports real-time price and related information for a given ticker symbol.  Designed as a convenient quick look tool that helps you understand the context of where a stock is trading right now, without the overhead of a trading platform. The color of the realtime price is determined relative to the delay price, so you can tell at a glance if the price in increasing (green), or decreasing (red) relative to the delayed quote.  Other coloriziation should be self-explanatory. 

Provides real time, delayed price, day change, percent change, volume, average volume, percent of average volume that's occured so far today, identifies the 52-week high, the percent off the 52-week high, the 52-week low, and the percent off the 52-week low.




Install
-------

    pip install rtq

Usage
-----

    rtqinfo -t tickersymbol

Prerequisites
--------
On Windows: 

[Microsoft Visual C++ Compiler for Python 2.7](https://www.microsoft.com/en-us/download/details.aspx?id=44266)

[easy_install lxml](http://lxml.de/2.2/installation.html)

See Also
--------

For more information: https://pypi.python.org/pypi/rtq
