# Using-NiFi-on-Yahoo-Finance

Demostrates how to use NiFi to download historical financial data from Yahoo Finance.

Synchronises the ticker data for the [Shark Algorithmic Trading Platform](https://github.com/danielneil/Shark).

Though it focuses on the ASX, it could easily be adjusted to suit any financial market and trading platform.

# Setup Instructions

1. Install ansible on your local machine.

2. Prepare a vanilla Debian server.

3. Add its IP address to the ./hosts files under [nifi-server]

4. Run: 
```
./build.sh
```
5. Navigate to https://nifi-server:8080/nifi. 
