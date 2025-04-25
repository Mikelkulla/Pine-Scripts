# Here you can find the Pine-Script codes for my investing strategies

## 1. TOTAL MTPI 
Direction of the overall market
### 1.1 TOTAL MTPI (Default) 
This is the default MTPI for the TOTAL Crypto Marcet cap index. It gives the direction of the overall market.
- total-mtpi-strat-m_k-v1.0.pine
### 1.2 TOTAL MTPI test THRESHOLD
This is TOTAL MTPI (Same as above) but with an adjusted range for signal smoothing when there is noise in the market, or signals being more agressive when needed
- total-mtpi-strat-m_k-test-threshold-v1.0.pine
### 1.3 TOTAL MTPI WITH ADF ADJUSTED RANGE
This is TOTAL MTPI (Same as above) but the signals are filtered based on the ADF. When there is a ranging market detected the signals are ignored and the strategy position is none. 
- total-mtpi-strat-m_k-with-adf-adjusted-range-v1.0.pine
## 2. Conservative Trend
Which major asset is aoutperforming?
### 2.1 ETHBTC MTPI
This is strategy to detect if Ethereum is performing better realtive to Bitcoin. So when the whole market is going up (TOTAL MTPI Positive) we allocate to the best performing asset
- ethbtc-mtpi-v1.0.pine
### 2.2 SOLBTC MTPI
This is strategy to detect if Solana is performing better realtive to Bitcoin. So when the whole market is going up (TOTAL MTPI Positive) we allocate to the best performing asset
- solbtc-mtpi-v1.0.pine
### 2.3 SOLETH MTPI
This is strategy to detect if Solana is performing better realtive to Ethereum. So when the whole market is going up (TOTAL MTPI Positive) we allocate to the best performing asset
- soleth-mtpi-v1.0.pine
## Trash Tend
Is the altcoin market going up? So we can continue with Shitcoin analysis to allocate a small part of the capital to them
### OTHERS.D MTPI
This is the Others.D MTPI for Others.D Market Index. It gives the direction of the altcoin market.
- others.d-mtpi-v1.0.pine