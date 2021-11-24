# Uniswap Price Monitor

Monitors the relative price of the PEOPLE/ETH price pair on Uniswap.

2 methods of price collection:
MainWSS -> Collects live-time prices when they change.
MainHTTP -> Collects live time prices.
To change the method simple change the final line of code on index.js to methodname(); -> Example: mainWSS();

### Note

Add HTTPS and WSS endpoints to connect to blockchain, in `.env` file.
1. Go to https://infura.io/
2. Sign up and create and ETH Project
3. Collect Endpoints for mainnet and put them in the respective space in the .env file.

