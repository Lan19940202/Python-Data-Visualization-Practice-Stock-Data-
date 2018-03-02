# Python-Data-Visualization (Stock Data)
#### Here I use matplotlib and seaborn library to visualize the stock dataset
* The first one is a scatter plot showing the average of daily trading volumes and close price of different serval stock in 2017;
* The second one is about AABA company stock, containing 12 box plot describing the destribution of trading volumes for each year from 2006 to 2017;
* The third one is a very cute bubble chart visualize the changes of yearly avergae stock close price and average trading volumes for a certain stock. I defined a function so user could choose the stock from they are interested;
* The fourth chart compares the changes of stock close price of three technical company(APPL, GOOG, MSFT) in 2017 (Comparing through their
stock’s returns tarting from the interested period)(Return=Price(t)/Price(0)). 
* (One important thing to consider when comparing the price trend of different stocks is that since the difference between dfiierent stock absolute price is sometimes very huge, comparing their absolute price may hard to indetify any figure from the plot we get. Like here the close price of GOOGL is obviously higher than the other two. They appear much less volatile than they truly are. So here I compare their close price changes by calculating their stock's return since the beginning of a certain period.)
