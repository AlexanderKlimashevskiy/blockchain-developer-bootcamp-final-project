# Crypto Lottery
1. People sends any amount of ETH to contract
1. Contract grabs latest gas price
1. Contract calculates probablity within range 0...1000000
1. If probability less or equal to gasPrice then contracts sends everything to sender of this transaction
