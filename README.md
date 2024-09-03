# KuCoin Trade Bot
### This is an old bot from years ago that I used to buy / trade $coins on the KuCoin platform
### Still useable, but I've moved on from this years ago
### Yes, I wrote this in node #horror

kucoin trade bot based on node

Base features
-----
Simple buy/sell bot based on a very simple calculation

Analyze market trends, determine high/low valued buys

Sells at 24h based highs, buys at 24h based lows

Does not buy if some amount of a currency is already owned

to do
-----
add better price determinations based on the kucoin api

e.g. lower interval price fluctuation calculations

add orderbook evaluations on sell/buy walls to beat whales selling off, this helpfully prevents stalling on the ordering</br>

outbid for buys / underbid for sales by .0001 sats on existing orderbooks once an acceptable price is reached, to sell off more quickly

implement the buy/sell api to start experimentally trading small amounts once the above is complete

experimental features to do
-----
add market swaps of coins between btc/eth/neo based on best price
