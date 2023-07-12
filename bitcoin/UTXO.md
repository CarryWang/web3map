# UTXO

## 介绍

***

未花费的交易输出（Unspent Transaction Output/UTXO），它是中本聪最早在比特币中采用的一个具体技术方案。未花费的交易输出是比特币交易中的基本概念，当我们要计算用户的剩余资产时，我们需要通过计算UTXO来得到。

**花费与未花费**的概念：举个简单的例子，你手上有一笔现金，未花费就说明现金属于你，花费了就说明现金不属于你。在比特币世界中，如果你有一笔未花费的交易输出，那么它就是你的资产。

> 在交易过程中，对方向你转账，我们把转入到对应地址的过程称为交易输出，如果你没花费转入的金额，那么说明这个交易输出未花费，仍旧是你的资产。

值得注意的是，当你把未花费的交易输出进行花费时，不论这笔交易输出是否超过了所需的金额，这笔未花费的交易输出都会被销毁。溢出的金额会被“**找零**”，重新回到你的账户下，并且存放在一个新的地址。

## 与UTXO相关知识

***

1.[比特币交易](bitcoin_transaction.md)