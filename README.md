Aman Behera --- Submission for VLG-Open-Project-2023/24 ---
# Optiver-Trading-at-the-close

![image](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/dd735ea6-12be-43eb-aed0-3b10d6863e5d)

Implemented a simple LightLGM model capable of predicting the closing price movements for hundreds of NASDAQ listed stocks using data from the order book and the closing auction of the stock.for Optiver's Trading at the close competition.

# Dataset description
Understanding the terminologies mentioned in the dataset's description became quite essential for attempting the problem statement. This dataset contains historic data for the daily ten minute closing auction on the NASDAQ stock exchange. The challenge is to predict the future price movements of stocks relative to the price future price movement of a synthetic index composed of NASDAQ-listed stocks.

![dataset_description](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/8cd6281b-e6ce-4925-be18-1ae063679ad6)

![11](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/26411a69-e0cd-4c60-903f-1682c4aed035)

![12](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/7d56a87f-b292-4b1d-832c-03ed8a1999f9)

# Explanation of some essential terminologies
Many different terminologies like order book, auction book, market maker (like optiver, jane street), wap required explanations. Although theoritical explanations can be accessed from google or any other source, the following images serve to give a working insights into how trading at close happens. Lastly since I had used quartiles for outlier detection an image explaning the same has also been added.
![1](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/2d479b6b-70eb-4962-8853-1147fde80fed)

![2](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/0d3a85b7-d322-446a-a0e7-bc26dbf3ca5b)

![3](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/a92660f4-fe47-4e6c-8898-76bdb64f91df)

![4](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/d64d5b8d-7df6-4c29-a3f8-0645ff46b6d5)

![5](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/ddf7d0aa-b31d-4352-b972-8aebc0bfae25)

![6](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/343c0a65-4003-49e8-91d8-8a35b55a1efa)

![7](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/fe55a4ca-a01a-4e71-99ca-3e8a881c453e)

![8](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/045745e2-4e39-47ec-a489-e7913677f102)

![9](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/f3835726-8d1c-4bee-8e36-4f3ccab1e35d)

# Essential Resources
Here are some of the resources I personaly used to get myself familiar with the terminologies and to understand the workings of trading at the close.

1. Market Making
   - https://blog.quantinsti.com/market-making/
   - https://www.investopedia.com/ask/answers/06/brokerandmarketmaker.asp
2. Order types and order books
   - https://www.investopedia.com/terms/o/order-book.asp
   - https://www.investopedia.com/investing/basics-trading-stock-know-your-orders/
   - https://www.schwab.com/learn/story/3-order-types-market-limit-and-stop-orders
3. Auction price decision framework
   - https://www.investopedia.com/terms/a/auctionmarket.asp
   - https://www.nyse.com/article/parity-priority-explainer
4. Trading at close terminologies
   - https://www.nasdaqtrader.com/content/productsservices/Trading/ClosingCrossfaq.pdf
     
     ![13](https://github.com/beingamanforever/Optiver-Trading-at-the-close/assets/121532863/77c3f25d-1a35-41a2-ad55-60710aa71090)

Refer to the official documentation of Nasdaq to understand the terminologies associated with close

- Like what is close?
- Why doesn't trading happen 24x7 ?
- Why market makers bring liquidity to the table?
- What is buy sell disparity?
- And other questionable terminologies

For understanding how stock market works do refer the following resources:
- https://youtu.be/p7HKvqRI_Bo?si=o_11VZY7VvDQ0_F2
- https://www.youtube.com/watch?v=ZCFkWDdmXG8
- https://youtu.be/Vb8JA3Y7aoE?si=_0ZtPnfJvIrKMohp
- https://youtu.be/WZlApjlzrfY?si=-wt21aI0o8NttKsA
