# ct-blockchain

https://rubygarage.org/blog/how-blockchain-works
https://zhuanlan.zhihu.com/p/97212450
https://www.zhihu.com/question/31112808

wallet can be created offline by offline rule,

create a rsa, use public key as address, keep private key.

you can earn money by create blocks.

e.g. create new block earn N coin, next coin N/2 coin, so in total N + N/2 + N/4 ... = N(1-(1/2)^n)/(1-(1/2)) = 2N

With this fomula, in the block chain world, total 2N coins. (however this can be controlled by distributor)

if I want to get more coin, I can make more blocks.

assume a block can store 5 transactions

## relationships

bigger block size, more entries of transaction per block, per packing. however too big mean slower packing interval.

## points

same block is stored in every worker publicly.

worker can talk communicate to each other within scope, the scope is among winners or participiant. assume each round has multiple winners. a transaction will recoginzed as correct if >50% workers agree.

the win condition decided how hard it is to win, too hard waste of time, too easy too many winners.

how much is bonus designed, the total amount sum should reach limit, not unlimit. should be realistic, too much means too huge number, too small not enough to use, should be fair.
