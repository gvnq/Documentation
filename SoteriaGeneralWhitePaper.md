# Soteria General White Paper v1
&nbsp;


**April 23, 2018**
&nbsp;

&nbsp;

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Soteria General White Paper v1](#soteria-general-white-paper-v1)
- [_What is Soteria?_](#what-is-soteria)
	- [DEFINITION](#definition)
	- [FEATURES](#features)
		- [_Next Generation POW-based crypto consensus protocols_](#next-generation-pow-based-crypto-consensus-protocols)
		- [_Anti-ASIC Memory-based POW Mining Algorithm_](#anti-asic-memory-based-pow-mining-algorithm)
		- [_Practical Blockchain Compression and Size Reduction_](#practical-blockchain-compression-and-size-reduction)
		- [_Next Generation Privacy-Preserving Transactions_](#next-generation-privacy-preserving-transactions)
		- [_UTXO-based Transaction System_](#utxo-based-transaction-system)
		- [_UTXO-based Smart Contracts_](#utxo-based-smart-contracts)
		- [_State Channels for Interactive Micropayments_](#state-channels-for-interactive-micropayments)
		- [_Side-chain Compatibility_](#side-chain-compatibility)
		- [_Governance_](#governance)
	- [DESIGN PRINCIPLES](#design-principles)
	- [CLARIFICATION](#clarification)
- [_Why Soteria?_](#why-soteria)
	- [BACKGROUND](#background)
	- [PROBLEMS TO SOLVE](#problems-to-solve)
		- [Blockchain Scalability challenge](#blockchain-scalability-challenge)
			- [_Trade-off between throughput and latency_](#trade-off-between-throughput-and-latency)
			- [_Realistic Goal toward Scalability_](#realistic-goal-toward-scalability)
			- [_Toward Full Network Capacity Blockchain protocols_](#toward-full-network-capacity-blockchain-protocols)
				- [_Bitcoin-NG_](#bitcoin-ng)
				- [_SPECTRE_ and _PHANTOM_](#spectre-and-phantom)

<!-- /TOC -->
&nbsp;


# _What is Soteria?_

## DEFINITION

Soteria is the code name for the umbrella of protocols that IOCT is built upon. Soteria is the foundation of IOCT. Soteria is not a single computer network protocol or even a set of protocols at that - it is the aggregate of protocols, roadmaps and governance rules that expand to the future - it is a social contract. Soteria is built with cryptographic as well as game theoretic mechanisms to strike a balance among different incentives in a dynamic, heterogenous network comprised of autonomous and intelligent agents.

Nonetheless, Soteria is as much a rigorous computer protocol set as any other such protocol(s). Soteria is self-governed by a flavor of its own ELEOS smart contracts.



## FEATURES

Some of the key features of Soteria are:

### _Next Generation POW-based crypto consensus protocols_

Soteria will implement (in two stages) Full Network Capacity Scalable POW (Proof-of-Work) based consensus protocols - fist Segregated Linear Mining (like Bitcoin-NG), then Recursive Block Voting DAG (SPECTRE) together with Ordered blockDAG (PHANTOM).

### _Anti-ASIC Memory-based POW Mining Algorithm_

ASIC (Application Specific Integrated Circuits) mining is considered by many as the cancer for POW based crypto-mining - it erodes fairness. Soteria will adopt a computer memory-based POW algorithm called Cuckoo Cycle to mitigate the threat of ASIC Minings.

### _Practical Blockchain Compression and Size Reduction_

A scalable blockchain requires the ability to deal with rapid growth in size - e.g., growing into gigabytes or even terabytes in terms of days or months rather than years like Bitcoin - Soteria will adopt cryptographically sound blockchain compression protocols such as MimbleWimble and Bulletproof.

### _Next Generation Privacy-Preserving Transactions_

Privacy-preserving transactions are at the core of a truly autonomous digital economy - Recent advancement in this field enables Soteria to integrate strong privacy-preserving transactions into its technology stack: Confidential Transaction protocols such as MimbleWimble, Bulletproof; noninteractive trustless zero-knowledge proof: Bulletproof, zkSPARKS.

### _UTXO-based Transaction System_

An UTXO-based transaction system is essential to Soteria’s highly scalable, privacy-preserving blockchain architecture. Soteria follows the Bitcoin tradition in adopting an UTXO-based transaction system.

### _UTXO-based Smart Contracts_

An UTXO-based transaction system does make the design and implementation of a smart contract scheme somewhat difficult (but not impossible) - Soteria solves this problem by adopting next generation technologies such as Covenant, Decentralized Superscalar VM (Virtual Machine). Soteria also vastly increases the robustness of its smart contracts by adopting Functional Reactive, Formal Logic Proof programming paradigms for its ELEOS smart contract language.

### _State Channels for Interactive Micropayments_

Soteria is a vertical scalable stateless blockchain that will find its utility in many financial and economic applications. Nonetheless there are certain application scenarios that could benefit from a horizontal scalable solution - stateful interactive transaction channels - e.g., for coffee shop open tabs. Therefore Soteria will also implement its own state channel protocol - much like Bitcoin’s Lightning Network.

### _Side-chain Compatibility_

Soteria has no innate need for a side-chain solution for scalability. However, we are living in a world of blockchains. Value exchanges between blockchains are sometimes necessary. Soteria shall implement necessary features (such as atomic swap locks) to enable cross-chain transactions as well as connecting to inter-chain protocols such as Cosmos and Polkadot.

### _Governance_

The blockchain community has realized that Decentralization is not something that can be fully achieved in vitro (within the protocol). Therefore, a blockchain’s success depends on governance as much as on technical merits. Soteria adopts an active, forward looking governance model - mandatory hard forks every 6 months (like Monero) enforced by its own flavor of smart contracts - only after features past vigorous testing and garnered enough community votes (also governed by smart contracts) will they get pushed into the next release.



## DESIGN PRINCIPLES

Soteria positions itself as the concrete foundation for IOCT - stability and robustness trump everything else. Soteria follows battle-tested engineering best practices and guides its development as such - especially when cryptography is involved. Therefore as a principle Soteria shall not invent its own cryptography protocols (or at least in its early stages of development and deployment) per se, unless it is absolutely necessary (such as in its implementation of smart contracts). Soteria does adopt innovative next generation technologies/protocols - but only reputable ones with sound academic and engineering merits.



## CLARIFICATION


This white paper describes the technology principles and design considerations toward a fully implemented and deployed Soteria software stack. It is the intention of the author to include adequate details of the Soteria technology stack - but be informed that the goal of this white paper is aimed at assisting initial comprehension rather than comprehensive coverage of Soteria - its emphasis is on design principles, not theoretic and implementation details. Please look forward to our subsequent technical white papers for such details. Furthermore, as with any software engineering endeavor, Soteria will also undergo many revisions, iteration cycles and evolution phases to reach utility and maturity. That said, please refer to IOCT’s roadmaps for our aggressive development milestone schedule.


&nbsp;


# _Why Soteria?_

## BACKGROUND

At the time of this writing (mid-April 2018) there are over 1500 cryptocurrencies listed on [coinmarketcap.com](coinmarketcap.com) with a total market cap of over 300 billion USD. Since the advent of Bitcoin almost ten years ago, cryptocurrencies modelled after Bitcoin with its core technology had blossomed and brought many innovations - people wanted to use the technology to do low-cost international remittance, create liquid digital assets, and even carry out online elections enforced by cryptocurency enabled digital contracts.

Among the plethora of cryptocurrencies, the one that started them all - Bitcoin - has the biggest market cap, about 40% market cap share at the time of this writing.  Occupying second place on [coinmarketcap.com](coinmarketcap.com) is a cryptocurrency called Ethereum, worth around 50 billion USD, and a 15% market cap share. Toghether these top two cryptocurrencies occupy over 55% of the total market cap. Althought market cap cannot represent transaction volume, it did show the relative weight people engage their cryptocurrency related activities with.

We should also emphasize that the cryptocurrency market is very volatile - in fact, at the time of this writing (mid-April 2018) we'd just been through a phenomenal cryptocurrency inflation and correction period all within just 6 months (mid September 2017 to mid-April 2018). During the height of this cryptocurrency boom the strength of these two top cryptocurrencies all got a heavy dose of stress tests in the real world - which lead to demonstrate some of the pressing problems concerning the future of cryptocurrencies. It's not the purpose of this white paper to concern too much about the cryptocurrency market - but it helps to understand some of the issues that get discussed here.

These pressing issues are:

* the blockchain scalability challenge
	- trade-off between throughput and latency
	- containing blockchain size inflation with high transaction volume
* true anonimity in a public blockchain
* trade-off between participation fairness and energy conservation
* secure, privacy-preserving smart contracts
* governnace - managable path toward evolution

So let's talk about them.

## PROBLEMS TO SOLVE

DECLARATION - In this General White paper we will approach our problems, methods in a descriptive or rather intuitive way, instead of a more theoretic and formal way. The later shall be delegated to a separate, subsequent technical white paper, as stated in the first chapter of this document.

### Blockchain Scalability challenge
<!--
The bitcoin scalability problems

blockchain and nakamoto consensus protocol that we liked

so far all other solutions are by dropping essential features of the nakamoto protocols

we want a solution that adhere to the original nakamoto consensus

We need to pop the TPS bubble and settle the score

-->
#### _Trade-off between throughput and latency_

As cryptocurrencies such Bitcoin (and others such as Ethereum) get popular their transaction volumes shot to roof (compared to early days). Bitcoin was designed to generate one block every 10 minutes (roughly - as the block generation time is controlled indirectly by the bitcoin protocol's cryptopuzzle difficulty), which, compounded by Bitcoin's 1MB blocksize limit, amounts to only about 3 TPS (Transactions Per Second). Ethereum does not fare much better either, with a similar blockchain protocol to that of Bitcoin's, it only achieves about 7 TPS.

There are seemingly obvious solutions to this transaction throughput limitation - namly, (1) reduce the block creation time (e.g., from ~10 minutes to 1 minute or even seconds, like some altcoins did); (2) increase block size (e.g., from 1MB to 8MB, like Bitcoin Cash, a forked Bitcoin cryptocurrency, did). However, these two parameters are correlated and are bound by Nakamoto Blockchain's innate assemptions regarding security.

However, the Nakamoto Blockchain - the backbone on top of which Bitcoin, Ethereum and many other cryptocurencies are built, assumes (explicitly and implicitly) that (1) majority of honest nodes must be backed by adequate computation, storage and network capacity to be able to process transactions and create new blocks; (2) any node must be permitted to join or leave the network freely. These assumptions are the main premises to back Nakamoto Blockchain based cryptocurrencies' secure and Decentralized nature. Arbitrarily or inconsiderately tweaking block creation time or block size may lead to breaching of the Nakamoto Blockchain's, as well as the underlying cryptocurrency's security and trust model, or worst, its total collapse.

Tweaking the block creation time and block size affect the Nakamoto Blockchain like this: (1) reduce latency - reducing block creation time limits the spreading of blocks to reach adequate nodes of the network, which would lead to more conflicting blocks being created and discarded and frequent blockchain reorganization; (2) increase raw throughput - increasing block size could make bigger blocks taking more time to reach adequate nodes of the network, which would lead to the same situation as in (1). This situation creates a natural road block for cryptocurrencies adopting the native Nakamoto Blockchain desgin to scale easily.

Therefore better cryptocurrency protocol designs cannot just achieve scalability by simply tweaking between these two parameters. They also must NOT seek to scale the Nakamoto Blockchain by (often implicitly) breaking its security and trust assumptions.

#### _Realistic Goal toward Scalability_

With the above discussed concerns, we must ask ourselves - what is the realistic goal for scalability with Nakamoto Blockchain based cryptocurrencies?

In Nakamoto Blockchain based cryptocurrencies such as Bitcoin, nodes that assemble new broadcast transactions from the network into blocks are called _**miners**_. Miners are rewarded with per-transaction fee as welll as newly "minted coins" to compensate for their work - and as the network nodes grow and transaction volumes increase miners put in more computing resources: (1) processing power (for solving cryptopuzzles); (2) storage capacity (for storing blockchain data); (3) network bandwidth (for downloading new transactions and send out new blocks). Of those computing resources, their relative power change over time with different rate. We can list this change rate in descending order - processing power, storage capacity, network bandwidth. To give some perspective:

1. Processing power - this is mainly used to solve the cryptopuzzle and the measure is called the hasrate. From the early CPU and GPU mining to the special ASIC mining of late (2017-18), the hasrate has increased at least a hundred million fold. The variance among nodes - very high, as ASICs are out of the range of home computer owners - mining becomes a syndicated business.

2. Storage capacity - around the time Bitcoin first appeared (2009), the prevalent home computer hard drive storage capacity is around 500GB ~ 1 TB. Up until recent (2017-18), the average home computer hard drive is still around 1 ~ 2TB but it is not prohibitively expensive to harness a home computer with 5~10 TB of extra storage. So let's say we have a 10 fold increase in storage capacity. The variance among nodes - medium, as it is easier to obtain storage capacity than running ASIC operations. Also, full Bitcoin node only need to store ~200GB of blockchain data, far below the average storage capacity of an average home computer.

3. Network bandwidth - around 2009-10 broadband service had finally started to penetrate into most devleoped nations where Bitcoin is gaining popularity. However the broadband speed varies a lot among providers - let's assume the average speed is around 1Mb/s back then. Nowadays (2017-18) in developed nations the broadband service could reach 100Mb/s downlink for most users if they so choose but the variance is high - let's assume the average speed (downlink) is 10Mb/s. So there is an estimated 10 fold increase in network bandwidth. However, most home network's uplink speed is capped at around 5 - 10Mb/s depending on ISPs. Since a miner node usually need to broadcast their new block to at least 8 neighbors, an increase in block size would throttle home network bandwidth very easily.

The increased variances among nodes' computing resources is not a good thing for the decentralzed nature of a Nakamoto Blockchain. So we need to keep these variances in check in our new blockchain protocol design. We shall discuss the ways to mitigate the variances of the first two computing resources - processing power and storage capacity in later sections.

In the previous section we have shown that the limiting factor for Nakamoto Blockchain scalability is the trade-off between block creation time and block size and they are mostly related to network bandwidth (not of the single node though - the bandwidth of the entire network). This is understandable since Blockchain network is a distributed system that needs to reach consensus among many heterogenous, dynamic and sometimes unpredictable nodes.

Since many miners are creating new blocks at roughly the same time it is very easy to have _**forks**_ in the network, which is when two miners create new blocks with the same parent block in the blockchain. Nakamoto Blockchain protocol resolves _**forking**_ by making all miners add blocks to the longest chain they know, and if there are multiple "longest" chains of the same size, the protocol picks one at random. Obviously forking is undesirable. However, in the Bitcoin network the two network trade-off parameters are chosen with a large margin to make forking a rareity event: with 1MB block size limit new blocks could reach the whole network usually within seconds, this together with a block creation time of around 10 minutes, would reduce forking frequencuy to about every 60 blocks. In comparison a shorter forked chain's probability of catching up the longest tapers off exponentially and transactions are considered confirmed in only 6 blocks (Bitcoin).

Therefore we can see that Bitcoin makes its blockchain secure by choosing a large block creation interval (~10 minutes) that is much larger than the full network block propogation time (couple seconds). If we optimize this discrepancy between the block creation interval and the block propogation time, by either (1) reducing block creation interval or (2) increasing block size thus increasing block propagation time - we would trade security (we risk frequent forking - as frequent forking makes the blockchain unstable) with faster block creation and higher transaction throughput. If somehow we can design protocols to mitigate the risk and side effects of forking we can approach the optimization limit - where the discrepancy is zero - which is to say we can create a blockchain that reaches consensus among nodes that is only limited by the bandwidth of individual nodes and latency limited by the propagation time of the network [1] - We call this **Full Network Capacity Scalability**.

#### _Toward Full Network Capacity Blockchain protocols_

So now we understand that we need to find ways to deal with forking when the discrepancy between block creation interval and block propagation time gets smaller. There are several proposals to solve the forking problem. For our purpose here we will consider and implement two of them: Bitcoin-NG [1] and SPECTRE [5] together with PHANTOM [6]. As this optimization is crucial to solve the Nakamoto Blockchain scalability problem, our pursuit of the ideal protocol should not stop here just. Should there be ways to improve the state of the art approach, we shall follow suit and implement them in later software upgrades.

##### _Bitcoin-NG_

Bitcoin-NG [1] proposes to make the Nakamoto Blockchain _**Full Network Capacity Scalable**_ by dividing time into _**epochs**_, which correspond to Bitcoin's block creation time (actually the same thing) and utilizes two kind of blocks - _**key block**_ and _**microblocks**_.

A _**key block**_ is created in the same way as a Bitcoin block - finding the solution to a cryptopuzzle (called Proof-of-Work, PoW). However, _key block_ only contains one transaction - the coinbase transaction, which is used to award the miner of the block. _Key block_ also contains a public key that will be used to sign subsequent _microblocks_. In comparison, a Bitcoin block does not have this kind of key. In Bitcoin-NG a _key block_ is used to elect a "leader" for an epoch (one _key block_ | leader per epoch), which will sign subsequent _microblocks_ using the public key contained in the key block (and the leader's private key). In one epoch, all _microblocks_ are created (and signed) by assembling incoming transactions by the elected leader.

_Microblocks_ contain transaction entries similar to a Bitcoin block, but without any PoW. So we can see that in Bitcoin-NG a miner that gets elected (by PoW and randomly) could create many cheap (since there is no expensive PoW) small blocks (_microblocks_) on the fly as they come - this is how Bitcoin-NG achieves Full Network Capacity Scalability.

Because of Bitcoin-NG's separation of the roles of mining blocks and non-mining blocks, we call this _**Segregated Linear Mining**_.

There are rules baked into the Bitcoin-NG protocol to prevent a "leader" behaving badly. There are _microblock_ size limit as well as minimum _microblock_ generation time limit to prevent a bad leader to create massive number of microblocks. There is also a special transaction called the "poison transaction" embeded in _microblocks_ at specific location of the blockchain to deter a malicious leader from generating fake or double spending transactions. Every transaction carries a fee - the current block leader splits transaction fees with the next leader by 40/60 - this is to prevent the next leader cut short of previous leader's _microblock_ transaction set.

Aside from defend against bad leaders, there are concerns of attacks against the elected leader (such a DDoS attack agains the leader) to choke the Bitcoin-NG network. However, in the Bitcoin-NG protocol, the leader is identified by the public key, not an IP address so defense strategies could be devised to prepare fot these kind of attacks.

Bitcoin-NG is mostly compatible with Bitcoin (an epoch is ~10 minutes, the same as Bitcoin's average block creation time) with the same security feature as Bitcoin, yet scales to _**Full Network Capacity**_ of a single node. It is a natural evolution step of the Nakamoto Blockchain protocol - which makes engineering and reasoning about the blockchain's security much straight forward and continuous in relation to Bitcoin. This last fact is important as we want to tackle into the accumulated rich codebase and engineering know-how of Bitcoin - the most understood, mature Nakamoto Blockchain based cryptocurrency.

##### _SPECTRE_ and _PHANTOM_

_SPECTRE_ and _PHANTOM_ is the protocol proposed by the talented Israel researcher duo Yonatan Sompolinsky and Aviv Zohar, who were among the first to delve into the relationship between Nakamoto Blockchain/Bitcoin's block creation interval/block size trade-off and blockchain forking. Over the past few years (as early as 2013) they presented analysis toward this problem and proposed solutions such as Inclusive blockchain, GHOST - the lastest being _SPECTRE_ and its improvement _PHANTOM_.

Yonatan and his colleagues had observed that Bitcoin had been designed to avoid chain forking by giving large margins to the block creation interval and block size parameter, together with a (wasteful but effective) longest chain settling rule. This design decision gives Bitcion blockchain a good safety margin toward security (probability of block reversal drops off exponentially as an advancing longer chain grows  - a transaction only need to wait for the blockchain to grow a couple more blocks to be considered confirmed) but considerable low throughput and very limited scalability.

In the trustless Nakamoto Blockchain network, security is achieved by the aggregation of honest nodes' computing power - as Proof-of-Work is the only deterrance that attackers cannot bypass. However, Bitcoin's longest chain block picking (and fork arbitration) rule is very wasteful - many times the discarded orphan blocks (those are not really "orphan" blocks since they have parants - just abandoned) weigh more than the blocks on the longest chain - meaning that the accumulated Proof-of-Work computations are just wasted - not being used to secure the network.

Following these observations Yonatan and his colleagues made improvement to the original Bitcoin's longest chain rule - they utilized trees, and acyclic graphs (DAG) structure to take into the contribution of blocks mined on branches other than the longest chain, as well as orphan blocks. These approaches reduce the waste of mined blocks (blocks mined by PoW but discarded under the longest chain rule of Bitcoin), giving room to reduce the margins of safty against block reversal attacks by malicious or selfish miners while increasing block creation speed and throughput.

Their earlier protocols such as inclusive block chains and GHOST and their variants had been adopted into some popular cryptocurrencies, such as Ethereum. Ethereum's block rewards are not just awarded to the blocks belonging to successful longest chains but also blocks on related branches, such as uncle blocks - this design is a variant of the GHOST protocol.

 Their latest protocols following this line of thinking are called _**SPECTRE**_ and _**PHANTOM**_, all block DAG based.

 Here we have to make clear that in all their protocols based on DAG, those DAG data structures are block DAGs - meaning that the nodes in these graphs are blocks and eventually those DAG blocks would finalized into a blockchain, just like in Bitcoin or Ethereum. Contrasting this to some other prominent DAG cryptocurrencies, for example, IOTA - the basic data unit in IOTA's DAG is transaction, there is no block or blockchain in IOTA.

<!-- _SPECTRE_ is a block DAG protocol that utilizes _Recursive Block Voting_. -->
_SPECTRE_ is a cryptocurency protocol that converges to the Nakamoto Consensus and is secure under high throughput with _**Full Network Capacity Scalability**_. _SPECTRE_ achieves this by evolving their earlier inclusive block chain idea, which is reducing the waste of forked mined blocks. In _SPECTRE_, they pushed this _inclusive block_ idea even further - they want not only "reducing" waste of forked (orphaned - a misnomer in Bitcoin parlance) blocks but also "counting" all mined blocks, forked or not - this is tenable since they utilize a block DAG, not a single chain structure. We can see that if this is really achievable then their claim to reach _Full Network Capacity Scalability_ is true.

To achieve this kind of faster block inclusion they devised a _Recursive Block Voting_ mechanism to filter out misbehaving and malicious blocks. Note that this is not miner of the block voting but the block itself voting algorithmically. A block votes both ways - its predecessor blocks as well as its successor blocks. The votes are recursive because a block's votes are determined by other block's votes and their immediate neighbors, so on and on. We won't list the voting rules here (as they are quite complicated) but it suffices to say that this voting system is very fast and responsive in finding conflicting transactions in blocks, as well as blocks that are suspicious in behaving badly. As the authors pointed out, Bitcoin's longest chain rule can also be seen as a kind of block voting - the longest chain is the chain that has more voted blocks.

How does _SPECTRE_ compare to _Bitcoin-NG_? Both _SPECTRE_ and _Bitcoin-NG_ are Nakamoto Consensus protocols that are _Full Network Capacity Scalable_. However, Bitcoin-NG generates key blocks (the block with PoW) infrequently (every 10 minutes, same as Bitcoin), therefore, athough Bitcoin-NG's throughput is very high, its block confirmation time does not improve much from Bitcoin. On the other hand, _SPECTRE_, by utilizing _Recursive Block Voting_ mechanism, generates honest block set very fast - therefore achieving a much higher (quicker) block confirmation time than Bitcoin-NG.

Of course, from an engineering point of view, _SPECTRE_ is way too complicated compare to Bitcoin-NG, therefore we plan to implement Bitcoin-NG at our first stage of consensus protocol implementation.

_SPECTRE_'s block DAG data structure and recursive block voting rules make it lacking a strict global linear order - which makes it difficult to work with certain smart contracts that require the strict order of event records in the blockchain, especially those require strict order of inputs. This brings us _**PHANTOM**_.

_PHANTOM_ is also a block DAG cryptocurrency protocol that converges to Nakamoto Consensus. It relates and similar to the _SPECTRE_ protocol (in "nature | spirit" only, not protocol | algorithm wise), is also secure under high throughput and has _Full Network Capacity Scalability_.

_PHANTOM_ works by recognizing blocks mined honestly in the DAG structure and put them into a cluster. The protocol then turn DAG's natural ordering into a topoligical ordering for the honest block cluster so it can penalize the blocks outside this cluster (misbehaving blocks). With the ordering of blocks the protocol could then check the consistency of transactions inside blocks.

The advantage of the _PHANTOM_ protocol is that it provides a topological ordering - which can be used on smart constracts that require strict ordering.

By pursuing strict ordering _PHANTOM_'s block confirmation time suffers as a result, this is not very optimal compared to _SPECTRE_, which has very high block confirmation time, but no strict ordering.

We plan to implement a combination of _SPECTRE_ and _PHANTOM_ protocols in our second stage of consensus protocol implementation.
