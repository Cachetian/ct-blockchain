# ct-blockchain

https://rubygarage.org/blog/how-blockchain-works
https://zhuanlan.zhihu.com/p/97212450

wallet can be created offline by offline rule,

create a rsa, use public key as address, keep private key.

you can earn money by create blocks.

e.g. create new block earn N coin, next coin N/2 coin, so in total N + N/2 + N/4 ... = N(1-(1/2)^n)/(1-(1/2)) = 2N

With this fomula, in the block chain world, total 2N coins. (however this can be controlled by distributor)

if I want to get more coin, I can make more blocks.

assume a block can store 5 transactions
