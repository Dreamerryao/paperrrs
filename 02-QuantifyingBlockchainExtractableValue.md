# Quantifying Blockchain Extractable Value: How dark is the forest?

## 第一遍

从摘要和题目里可以看出来这篇文章是首次定量研究BEV的实际风险，对里面提到的一些攻击还挺感兴趣的，但之前也一直都没了解过

这篇文章属于看第一遍都有些困难的文章...

还不太知道 Blockchain Extractable Value 是什么，根据参考文找到了一篇《Flash Boys 2.0: Frontrunning in Decentralized Exchanges, Miner Extractable Value, and Consensus Instability》，以及Google到了一篇《Miners as intermediaries: extractable value and market manipulation in crypto and DeFi》先补一下这方面的知识

《Miners as intermediaries》用很入门级的语言介绍了MEV：矿工利用决定打包哪些交易以及确定交易的执行顺序来为自己获取的额外利益。
正常情况下，矿工应该按照给出的gas费用大小来对交易进行排序，但矿工可以在dex（去中心化交易所）的大额交易前后夹杂两个自己的交易，以此套取利益。
由于区块链上的交易数据是公开的，因此这些操纵市场的行为也可以被发现。

这篇文章就是在量化已经产生的BEV，从而揭示这个市场的危机。

按照第一遍的逻辑浅读下来，这篇文章属于在学术界**首次定量分析**BEV的文章。”我们在对49691种加密货币和60830种链上市场的11289个地址进行分析后估计，在32个月的时间里，BEV获得了5.4054亿美元的利润。我们发现的最高BEV实例总额为410万美元，是挖矿奖励的616.6倍。“

主要贡献点有三个：
1. 定量分析BEV的危害。
2. 提出通用交易重放算法，允许克隆和抢先运行受害者交易，而无需了解受害者交易的底层逻辑。
3. 对新的BEV系统（BEV中继器 如flashbots）进行分析，发现新型系统加剧了区块链共识层攻击。

整篇文章完整性很高，对攻击有比较详细的威胁模型介绍。隶属于区块链，DeFi模块。值得一读。

## 第二遍

ing
