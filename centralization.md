#Centralized cryptocurrencies
 
This article is highly inspired by recently visited [conference](http://www.osp.ru/iz/blockchain), my discussions with colleagues and ideas how to improve blockchain systems. Most of conference speakers were from big Russian banks and their speech were about blockchain use cases, mainly as database or smart contract platform. None of them where able to answer the question, why do they really need blockchain. Correct answer for this question came recently from R3 consortium: ["no blockchain because we don't need one"](https://twitter.com/Beautyon_/status/834152812405735425?ref_src=twsrc%5Etfw). Blockchain is not needed for banks, it is needed instead of banks. It is required for decentralized systems only, applications with trusted party wil always be more efficient, simple, etc.

  Meaning of decentralization was widely discussed earlier (see, for example, post from [Vitalik Buterin](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274#.x5k6j4cxg)) and is the only real purpose of blockchains. In this paper I'm going to discuss degree of centralization of existing cryptocurrencies and reasons leading to it. 
 
##Governance and development centralization 

Let's start from non-technical topic. It is nice to think that no-one control blockchain: network participants (miners) acts as a decentralized community and chose direction of development. In fact, everything is much worse.

First source of centralization here, is source of improvement protocol. Only small group of **core developers** is able to accept changes to source code or even understand some proposals. No-one work for free and organization that pays money to core team in fact control cryptocurrency source code. For example Bitcoin developement is controlled by Blockstream, and this organization have it's own interests. **Treasury system** like one in [Dash](https://iohk.io/research/papers/dash-governance-system-analysis-and-suggestions-for-improvement/) or proposed to [Ethereum Classic](https://www.scribd.com/document/339563725/Ethereum-Classic-Treasury-System-Proposal-Google-Docs) may be a solution here, however a lot of questions are still open there (for example 78 pages of ETC treasury proposal are quite complicated and Dash treasury was developed even without any documentation and analysis). 

Next centralization risk in governance is **cult of personality**. While Vitalik tells in his [post](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274#.x5k6j4cxg), that no-one control cryptocurencies, his opinion is so important for Ethereum community, that most of them accepted bailout, that breaks basic principles of cryptocurrencies.

Finally, there are a lot of interested parties in cryptocurrency, and opinion of some of them (like regular users) is usually **ignored**. Anyway, cryptocurrency development is mainly a part of social consensus, and it is good to have manifesto, declaring it's purposes from start.

##Services centralization 

One of the biggest problems in existing cryptos is centralization of services. Blockchain **processing is heavy** (e.g. Ethereum processing from genesis may take weeks of time) and regular users that just want to send some coins **trust to centralized services**. Most of Bitcoin users trust [blockchain.info](http://blockchain.info/), Ethereum users trust [myetherwallet](https://www.myetherwallet.com/) and so on. Compromising of most popular wallets will lead to sufficient lost of user funds. Moreover, most of users trust in blockchain explorers and never checks that blocks in it are correct. What is the meaning of "decentralized" social network Steem, if almost none of it's users ever downloaded blockchain and believe that data on [steemit.com](https://steemit.com) is correct? 

Moreover, usually all cryptocurrency infrastructure is centralised in the place or is controlled by the same people. Imagine, that blockchain.info is compromised: attacker can steal all users money from wallet, hide stealing transactions and shows user-created transactions in blockchain explorer and the attack will be unnoticed for a long time. 

Thus, trust in centralized services produce **single point of failure**, allows **censorship** and put user coins in **jeopardy**.

##Mining centralization 

In popular cryptocurrencies **hardware requirements are high** even just for blockchain validation. Even if you own modern hardware able to process block fast, your network channel may not be wide enough to download created blocks fast enough. This leads to situation, where only few amount of high end computers are able to create new blocks that leads to mining centralization. Being open by design, Bitcoin mining power is now concentrated in a limited group of miners, that can easily meet and agree to perform 51% attack (or just censor selected transactions or blocks). Mining pools even worsen the situation, e.g. in Bitcoin just 5 mining pools control more than 50% of hash rate (at least if you believe [blockchain.info](https://blockchain.info/pools)). Another option for miners is to skip transaction processing and produce empty blocks, that also makes blockchain meaningless. 

Proof-of-Stake is usually regarded as more hardware-friendly, however really popular blockchain requires wide network channel to synchronize network anyway. Also it is usually unprofitable to keep mining node in PoS and just small per cent of coins is online that makes network valuable. This is usually fixed by delegating mining power to someone else, that also leads to **small amount of mining nodes**. 

##Centralization as a solution

The most scaring point of this paper, is that more and more often centralization is regarded as a solution for some problems for cryptocurrencies. To fix scalability issues, cryptocurrencies propose to use limited number of trusted ["masternodes"](http://dashmasternode.org/what-is-a-masternode/), ["witnesses"](https://byteball.org/Byteball.pdf), ["delegates"](https://bitshares.org/technology/delegated-proof-of-stake-consensus/), ["federations"](https://blockstream.com/2017/01/16/strong-federations-paper-released-liquid.html) and so on to "fix" too big amount of mining nodes in network. Number of this trusted nodes may vary, but trying to fix scalability issues they also destroy decentralized nature of currency. Eventually this leads to cryptocurrency with **only one performing node**, that process transactions very efficiently, without confirmation delays and forks, but suddenly blockchain is not needed for it like in R3 research.

Unfortunately, most of users are not able to determine lie in crypto description and like this centralized blockchains more and more, because for sure centralized way is (and will always be) more simple and user-friendly.

##Conclusion

In current blockchains setup we are going to more and more centralized cryptocurrencies, that will inevitably lead to mass disappointment in blockchain technology, because it is not needed for centralized solutions. It is still a user choice, whether to believe beautiful and fast web interface or to use trustless, but harmful software, requiring to download blockchain data and process it. 

Most of centralization risks may be fixed, if trustless full-nodes, wallets, explorers will be chip to launch, easy to use and user friendly. I'm not going to propose solution in this paper, but I hope it is coming soon!
 
 
 
 
 
 
 
 