# eth_python_tracker
Welcome! This is a Python-based Dash app meant to track whale activity in buy / sell walls on GDAX. Thanks to a recent update (curtesy of great community feedback and guest contributions), we now have an ETH/BTC ratio whale watching view as well as the main ETH/USD view. It is set to update every 10 seconds but this can be changed easily in the code if you want to make the refreshes faster / slower. 

The idea for this app came to me while looking at buy and sell walls on GDAX. While you can see large walls, you cannot see how much of these are due to individuals vs. group clustering. This difference is quite important, as it impacts how quickly walls can be pulled, etc., so having buy / sell-wall information at the Ethereum address level can prove quite valuable for traders. This simple app allows you to access just that information, by focusing on individual limit orders that constitute large walls, and particularly emphasizing the largest orders. Also, I filter out all orders less than 1 ETH in size.

Anyone interested with Python installed on their computer can download this and run it locally, just check to be sure you have the few required modules installed.

A screenshot of what it should look like when running is included. Buys / sells are color-coded, and the size of each observation is deteremined by the square root of the volume of that particular order. 

This is my first Python / Dash app, and I hope it is of use to many of you! I may publish it online in the future, but presently it is computationally easiest to run your own local version. ETH donations appreciated: '0x966796A6334EA1302d9Edb03072dB55241145401'

