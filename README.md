# defichain vault maxi
This script is made to optimize your defichain vault rewards by maximizing the amount of loans put into the liquidity mining of dTokens.
You can define the thresholds for your collateralization ratio. if the collateral rises, the script increases LM-exposure, if it falls it automatically decreases it.

If the `reinvest` is set in the settings, it will automatically reinvest DFI rewards from the address as soon as they go over that threshold. 

Vault Maxi exists in two versions: 
* As a [python script](node-rpc) which needs a fullnode to access via rpc
* As a [typescript client](ocean-client) which uses the ocean-api. This version is made to run as a lambda in AWS

# Disclaimer / WARNING
If you don't understand what the code does and what the risks are, you will probably loose money.
Don't ever blame me for losing money yourself ;)

And of course, this is not financial advice!

# donations
If this script or parts of it help you make more rewards, feel free to give something back:

## kügi
DFI: df1qqtlz4uw9w5s4pupwgucv4shl6atqw7xlz2wn07

BTC: bc1qfdm2z0xpe7lg70try8x3n3qytrjqzq5y2v6d5n

## krysh
DFI: df1qw2yusvjqctn6p4esyfm5ajgsu5ek8zddvhv8jm
