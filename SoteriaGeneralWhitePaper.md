# Soteria General White Paper v0.1
&nbsp;


**May 16, 2018**
&nbsp;

&nbsp;


<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Soteria General White Paper v0.1](#soteria-general-white-paper-v01)
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
		- [Side Effect of High throughput - How to Store All That Blockchain?](#side-effect-of-high-throughput-how-to-store-all-that-blockchain)
			- [_SPV (Simplified Payment Verification)_](#spv-simplified-payment-verification)
			- [_Pruned Mode_](#pruned-mode)
			- [_MimbleWimble - Permanently Pruning the Blockchain_](#mimblewimble-permanently-pruning-the-blockchain)
		- [How to Recover Satoshi's Dream of Fairness](#how-to-recover-satoshis-dream-of-fairness)
			- [_Criteria for Choosing ASIC Resistant cryptopuzzle Algorithms_](#criteria-for-choosing-asic-resistant-cryptopuzzle-algorithms)
			- [_Memory Latency Based Cryptopuzzle Algorithm - Cuckoo Cycle_](#memory-latency-based-cryptopuzzle-algorithm-cuckoo-cycle)
		- [The plight of a public ledger - How to maintain anonymity and fungibility?](#the-plight-of-a-public-ledger-how-to-maintain-anonymity-and-fungibility)
			- [_Confidential Transactions to the Rescue_](#confidential-transactions-to-the-rescue)
		- [All is Fair in Love and War and Smart Contracts?](#all-is-fair-in-love-and-war-and-smart-contracts)
			- [_Predicate Extended UTXO-based State Transition Model for Smart Constract_](#predicate-extended-utxo-based-state-transition-model-for-smart-constract)

<!-- /TOC -->
&nbsp;


# _What is Soteria?_

## DEFINITION

Soteria is the code name for the umbrella of protocols to build a scalable, privacy-preserving versatile cryptocurency. Soteria is not a single computer network protocol or even a set of protocols at that - it is the aggregate of protocols, roadmaps and governance rules that expand to the future - it is a social contract. Soteria is built with cryptographic as well as game theoretic mechanisms to strike a balance among different incentives in a dynamic, heterogenous network comprised of autonomous and intelligent agents.

Nonetheless, Soteria is as much a rigorous computer protocol set as any other such protocol(s). Soteria is self-governed by a flavor of its own ELEOS smart contracts.



## FEATURES

Some of the key features of Soteria are:

### _Next Generation POW-based crypto consensus protocols_

Soteria will implement (in two stages) Full Network Capacity Scalable POW (Proof-of-Work) based consensus protocols - first Segregated Linear Mining (like Bitcoin-NG), then Recursive Block Voting DAG (SPECTRE) together with Ordered block DAG (PHANTOM).

### _Anti-ASIC Memory-based POW Mining Algorithm_

ASIC (Application Specific Integrated Circuits) mining is considered by many as the cancer for POW based crypto-mining - it erodes fairness. Soteria will adopt a computer memory-based POW algorithm called Cuckoo Cycle to mitigate the threat of ASIC Minings.

### _Practical Blockchain Compression and Size Reduction_

A scalable blockchain requires the ability to deal with rapid growth in size - e.g., growing into gigabytes or even terabytes in terms of days or months rather than years like Bitcoin - Soteria will adopt cryptographically sound blockchain compression protocols such as MimbleWimble and Bulletproof.

### _Next Generation Privacy-Preserving Transactions_

Privacy-preserving transactions are at the core of a truly autonomous digital economy - Recent advancement in this field enables Soteria to integrate strong privacy-preserving transactions into its technology stack: Confidential Transaction protocols such as MimbleWimble; noninteractive trustless zero-knowledge proof: Bulletproof.

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

Soteria positions itself as the concrete foundation for a new generation of cryptocurency - stability and robustness trump everything else. Soteria follows battle-tested engineering best practices and guides its development as such - especially when cryptography is involved. Therefore as a principle Soteria shall not invent its own cryptography protocols (or at least in its early stages of development and deployment) per se, unless it is absolutely necessary (such as in its implementation of smart contracts). Soteria does adopt innovative next generation technologies/protocols - but only reputable ones with sound academic and engineering merits.



## CLARIFICATION


This white paper describes the technology principles and design considerations toward a fully implemented and deployed Soteria software stack. It is the intention of the author to include adequate details of the Soteria technology stack - but be informed that the goal of this white paper is aimed at assisting initial comprehension rather than comprehensive coverage of Soteria - its emphasis is on design principles, not theoretic and implementation details. Please look forward to our subsequent technical white papers for such details. Furthermore, as with any software engineering endeavor, Soteria will also undergo many revisions, iteration cycles and evolution phases to reach utility and maturity. That said, please refer to the roadmaps for our aggressive development milestone schedule.


&nbsp;


# _Why Soteria?_

## BACKGROUND

At the time of this writing (mid-April 2018) there are over 1500 cryptocurrencies listed on [coinmarketcap.com](coinmarketcap.com) with a total market cap of over 300 billion USD. Since the advent of Bitcoin almost ten years ago, cryptocurrencies modelled after Bitcoin with its core technology had blossomed and brought many innovations - people wanted to use the technology to do low-cost international remittance, create liquid digital assets, and even carry out online elections enforced by cryptocurency enabled digital contracts.

Among the plethora of cryptocurrencies, the one that started them all - Bitcoin - has the biggest market cap, about 40% market cap share at the time of this writing.  Occupying second place on [coinmarketcap.com](coinmarketcap.com) is a cryptocurrency called Ethereum, worth around 50 billion USD, and a 15% market cap share. Toghether these top two cryptocurrencies occupy over 55% of the total market cap. Althought market cap cannot represent transaction volume, it did show the relative weight people engage their cryptocurrency related activities with.

We should also emphasize that the cryptocurrency market is very volatile - in fact, at the time of this writing (mid-April 2018) we'd just been through a phenomenal cryptocurrency inflation and correction period all within just 6 months (mid September 2017 to mid-April 2018). During the height of this cryptocurrency boom the strength of these two top cryptocurrencies all got a heavy dose of stress tests in the real world - which lead to demonstrate some of the pressing problems concerning the future of cryptocurrencies. It's not the purpose of this white paper to concern too much about the cryptocurrency market - but it helps to understand some of the issues that get discussed here.

These pressing issues are:

* the blockchain scalability challenge
	- trade-off between throughput and latency
	- blockchain size inflation with high transaction volume
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

By pursuing strict ordering _PHANTOM_'s block confirmation time suffers as a result, this is not very optimal compared to _SPECTRE_, which has very speedy block confirmation time, but no strict ordering.

We plan to implement a combination of _SPECTRE_ and _PHANTOM_ protocols in our second stage of consensus protocol implementation.

### Side Effect of High throughput - How to Store All That Blockchain?

The purpose of a blockchain scalability solution is to vastly increase the throughput of cryptocurency transactions while maintain the security model of the Nakamoto Blockchain that the cryptocurency is based upon. For example, currently the Bitcoin blockchain grows by adding 144 blocks a day (because Bitcoin's 10 minute block creation interval produces 6 blocks every hour - so 144 blocks every 24 hours) - with a block size of 1MB, that's 144MB per day - and about 80 GB a year. At the time of this writing (late April 2018), the Bitcoin blockchain size is approximately 156 GB for almost 10 years of existence (It took quite some time for Bitcoin to reach the 1MB per block size limit) - A comtemporary home computer could accomodate the whole Bitcoin blockchain - Although it is still not convenient for simple transaction nodes.

The current Bitcoin processing speed amounts to about 3 transactions per second - a meager processing speed. If we were to increase the Bitcoin processing speed to match that of the VISA's - about 4000 transactions per second on average - we need to increase the Bitcoin throughput by a thousand fold. Suppose we achieve this scalability feat for Bitcoin - we face another challenge - the Bitcoin blockchain size will increase a thousand fold as well - so 144MB daily increase in blockchain size could easily become 144 GB - and tens or even hundreds of terabytes more of hard drive storage space will be needed each year to accomodate the blockchain size growth. This huge growth in storage space for high throughput blockchain makes running a full processing node in the cryptocurency network untennable for anyone who could not afford to run a modern datacenter. This increase in transaction throughput does not only increase storage capacity requirement - it also makes verifying the huge amount of transactions a challenge as well - so more powerful processing units are needed as well to accomodate the situatoin.

There had been ways proposed and implemented to deal with the blockchain storage space problem - with varying degrees of usefulness:

#### _SPV (Simplified Payment Verification)_

In the original Bitocin white paper Satoshi Nakamoto discussed ways to simply transaction processing - he devised a solution for running a simple transaction node - called SPV (Simplified Payment Verification) - this kind of node can verify payments without running a full network node (participating in creating new blocks). Satoshi indicated that SPV is venerable to fabricated invalid blocks when attackers overwhelme the network. In that case the SPV node still need to download the whole blockchain to verify the transactions, just like a full node.

#### _Pruned Mode_

Inn more recent versions of the Bitcoin software a "pruned mode" was introduced - in this "pruned mode" you can choose how much disk storage space is allocated to the Bitcoin node software - as in this mode verified transaction data can be thrown away to save disk space. However this is still full node software - one still needs to download and verify every transaction on the blockchain ever made at first before throwing away verified transaction data.

As we can see that neither _**SPV**_ nor _**Pruned Mode**_ could render the full node obsolete - full nodes are still needed (and in sufficient numbers) to secure the Bitocin/Nakamoto Blockchain.

Is it possible to permanently discard some of the blockchain data to save space? This was considered to be impossible - until someone proposed an exotic and radical method to do just that -

#### _MimbleWimble - Permanently Pruning the Blockchain_

_**MimbleWimble**_ is a Bitcoin-like cryptocurrency primitive that provides much better scaling and privacy properties than Bitcoin but keeps Bitcoin's security model. It provides a unique way of drastically pruning Bitocoin transaction records in the blockchain while at the same time improves privacy - a seemingly impossible task - but we'll see that pruning transaction records is closely related to its ability to provide privacy. Here we shall focus on the pruning part, and leave the discussion of privacy and other topics to later sections (such as scripts and smart contracts).

In Bitcoin, transactions take two forms around UTXO (Unspend Transaction Output): (1) regular transactions that destroys UTXO - so every transaction destroys an old UTXO and creates a new one with a new key; (2) special transactions that do not destroy old UTXO - they are called _**coinbase**_ transactions and are generated as the rewards for miners - this is the way new "coins" are created in Bitcoin. So the Bitcoin blockchain is a ledger book containing all UTXOs ever created (and destroyed) since the _**genesis block**_. In order to verify a transaction one has to verify all transactions all the way back to the _genesis block_ to really make sure there is no excess coins created or coins created by inflation.

In _MimbleWimble_, we don't deal with regular transactions like that in the Bitcoin, instead transactions are constructed as "Confidential Transactions" (CT), which is a technology that allows the encryption of an amount using _Homomorphic Commitments_. Basically as in Bitcoin, a _MimbleWimble_ transaction centers around (1) _Inputs_, (2) _Outputs_, (3) _Kernel_, and (4) _Kernel Signature_ [#Reference#]:

1. _Inputs_ are just references to old _Outputs_.

2. _Outputs_ are CT (Confidential Transaction) _Outputs_, which are _Algebraic Geometric Group Elements_ that correspond to points on _elliptic curves_, which _blinds_ and _commits_ to amounts (which obscure the true amounts for privacy), plus _**range proofs**_ (for verifying amounts within a range without revealing the true amounts, again for privacy).

3. _Kernel_ is the algebraic difference on the _elliptic curve_ between _Inputs_ and _Outputs_. Due to the scheme of _blinds_ and _commits_, the _Kernel_ is actually a _multi-signature key_ for all transacting parties.

4. _Kernel Signature_ is used for a _Kernel_ to sign itself to ensure there is no tampering of the transaction. By signing other blockchain data using the _Kernerl Signature_ we can add functionalities to extend the original _MimbleWimble_ primitive (to be discussed in other sections).

_Kernel_ and _Kernel Signature_ are very important to what we are discussing here - drastically reducing the blockchain data to gain massive scalability improvement. As we mentioned above, _Kernel_ corresponds to the algebraic difference between _Inputs_ and _Outputs_ on the elliptic curve utilizing _Homomorphic Commitments_. It turns out that by treating _Inputs_ and _Outputs_ this way we can actually remove those cancelling out transactions in the blockchain, and only keep the UTXO transactions and _Kernels_, and still be able to verify the transaction history of UTXOs, which are the only part necessary to maintain the integrity of the blockchain. We can even merge transactions across blocks directly, only keeping the UTXO Transactions and _Kernels_. Please be noted that the verificaiotn of the _Kernels_ are a full validation of the blockchain, just as in Bitcoin. But in Bitcoin all transactions are chained and you can't do full verification with a pruned blockchain - while in _MimbleWimble_ you can - because in _MimbleWimble_ the _Kernels_ keep the integrity of all UTXOs of the blockchain.

Therefore we can see that in _MimbleWimble_ the privacy-preserving design of transactions are a first consideration while blockchain pruning is a welcome (but powerful) side effect. Actually to achieve privacy, _MimbleWimble_ added _range proof_ for CT (_Confidential Transactions_), which increases the Bitcoin-like transaction from 250 bytes to 2.5k bytes - a 1000 fold increase in size - consequently a Bitcoin blockchain of 100GB would be reaching 1TB if CT feature is added, like the _MimbleWimble_ Blockchain. However, since by merging transactions we can drop cancelling out transactions and their _range proofs_, by doing this we can achieve a drastic reduction in blockchain size, again by almost 1000 folds (a 1TB blockchain could be pruned to around 16GB, without the _range proof_ data, which if retained, is around 100GB). Furthermore, since the _MimbleWimble_ blockchain could be pruned to only retaining the UTXO transactions the size growth of the blockchain could be controlled in a much manageable way - with horizontal scaling solutions such as the Lightning Network we can even incentivize people to reduce UTXO transactions on the main chain, thus achieving even greater blockchain size scalability.

As we can see, _MimbleWimble_ primitive brought us a highly scalable blockchain togother with strong privacy preserving properties with the same Bitcoin security model. Therefore we will incorporate the _MimbleWimble_ primitives into our blockchain implementation.

<!-- By controlling UTXO production it is even possible to make the blockchain size growth at 0 -->

### How to Recover Satoshi's Dream of Fairness

In Satoshi Nakamoto's Bitcoin blockchain design, security is achieved by building cryptopuzzles into blocks - no one can forge or recreate the blockchain without repeating the same amount of work of solving a puzzle - that is the essence of PoW - Proof of Work. Proof of Work amounts to solving cryptopuzzles. Bitcoin's PoW algorithm or cryptopuzzle inherits that of HashCash, an earlier attempt of digital cash before Bitcoin - which is to find a "nounce" - a number - which when fed into a hash function would yield a number smaller than some predefined number - the so called Bitcoin minors all compete to find this "nounce" to claim the next block reward. The predefined number is used by Bitcoin to control the difficulty of mining.

Bitcoin's hash function is from a family called SHA256, which is computation bound with a small memory footprint. It's a relatiely simple hash function and thus susceptible to optimization by special hardware called ASIC (Application Specific Integrated Circuits), which is a computer chip just like CPU but highly optimized to do one thing well - in this case solving SHA256 hash function cryptopuzzle. As of this writing (April 2018), for Bitcoin's current difficulty level (this difficulty level is increasing since more computation resources are entering Bitcoin mining) the comtemporary home or server CPU's hash rate (how many hashes attempted to solved the SHA256 cryptopuzzle per second) is well below 100 hashes/second (h/s), with top of the line CPUs (those sells over 1000 dollars) overclocked over 4G Hz reaching 300 ~ 400 h/s - whereas Bitcoin mining ASICs such as Bitmain's S9 reaching 14 Tera h/s - some 10 million times faster than CPU mining. Nowadays Bitcoin mining is long past practical for average individual miners - it has become a large scale business with mining farms operating hundreds or even thousands of specialized ASIC mining rigs. Not just computation power - these mining operations consumes huge electricity, they often establish their mining equipments near low cost electricity sources, such as hydro-electricity power generator stations. Satoshi's "one CPU one vote" fairness ideal had been shattered, ironically, following Bitcoin's increasing popularity.

Many consider Bitcoin's massive mining energy consumption a waste - but this energy or external entropy is needed to secure Bitcoin's permissionless, decentralized consensus blockchain integrity, we only need to make it more efficient. Also when Bitcoin mining shifted from individuals to big Bitcoin mining pools, fairness suffers. The concentration of ASIC mining power creates instability for the Bitcoin network - we've witenessed a plethora of selfish mining and other destablizing behaviors from big centralized mining pools over recent years (such as manipulating cryptocurrency prices by deliberately rasing and reducing massive mining power among several cryptocurrency mining operations that have same POW mining algorithm - SHA256).

Therefore we need to find a PoW mining algorithm that is resistant to ASIC mining.

Of course over the years many ASIC-resistant PoW mining algorithms have alrady been developed. Such as Scrypt, CryptoNight - for other cryptocurencies such as Litecoin, Monero, etc. They have achieved somewhat limited success. They are all much complicated than SHA256 - combining mixed computation and memory bound operations. But there is a limit in designing these algorithms, too - because PoW results need to be verified by transaction parties - and the ideal cryptopuzzle algorithm should be hard to compute but easy to verify - SHA256 satisfies this requirement - as it can be made really difficult to compute yet always easy or trivial to verify the result. Other algorithms fall in between - some achieved certain level of ASIC-resistance by making optimized ASIC design of their complex algorithms harder, but suffers on the verification end - it's always a trade off. Easy verification is important because the harder the verificaiton process, the harder the ease of use of the cryptocurrency for everyday transactions suffer.

#### _Criteria for Choosing ASIC Resistant cryptopuzzle Algorithms_

Let's examine the Bitcoin's SHA256. To make it simple, we would pick the time frame of mid 2018. We will compare the hash rates of CPU, GPU and ASIC based mining setups with a budget of $3000 for one mining device, under current difficulty levels (mid 2018). As we have found out - a $3000 CPU mining rig in mid-2018 could probably get 300 h/s; a $3000 GPU mining rig could get 30 M(illion) h/s; while a new Bitmain S11 ASIC mining rig (assuming a ~$3000 price tag) would get 30 T(era) h/s. So the hash rate differnces are - CPU : GPU : ASIC - 1 : 100,000 : 100,000,000,000. Of course the estimate is a simplication but good enough to illustrate the situation. This ratio shows how bad the Bitcoin mining situation is for faireness.

The goal of a good ASIC resistant cryptopuzzle algorithm should try its best to reduce the above ratio.

The ultimate ASIC resistant cryptopuzzle algorithm would be able to reduce the above ratio to 1 : 1 : 1 or close (or within one order of magnitude) - which seems untennable - but we do seem to have just the one - Cuckoo Cycle.

#### _Memory Latency Based Cryptopuzzle Algorithm - Cuckoo Cycle_

_**Cuckoo Cycle**_ is a cryptopuzzle algorithm presented by John Tromp in 2015 [#Reference#]. It's the first Graph-theoretic PoW cryptopuzzle system that is asymmetric in that it is non-trival to proof but trivial ro verify. The method involves finding subgraphs in large pseudo-random graphs - this is what the main Proof-of-Work based upon.

We will not delve into the details of _**Cuckoo Cycle**_ here. We only need to know that it has very good _memory bound_ properties as a PoW cryptopuzzle algorithm [#Reference#].

1. A memory footprint that is big enough to NOT fit into one memory chip

2. It hits the memory in a truly random memory access way

3. The computation associated with each memory access is neglectable

4. No feasible way to trade memory for time

Property 1-3 are easy to understand and self-explanatory. Property 4 needs some explaining - unlike HashCash kind of computation bound PoW systems such as SHA256, memory bound PoW algorithms face a potential attack vector: trade off computation time to reduce memory usage - if the computation time for finding the cryptopuzzle solution is not too bad - then memory usage reduction undermines the PoW system. Thus to satisfy property 4, we need to be reasonably confident that no feasible way exists to achieve this trade off between time and memory - for example, attempts to reduce memory usage would result in "unbearable" increase in computation time.

It's been demonstrated that _**Cuckoo Cycle**_ empirically upholds those _memory bound_ properties list above - so we'll adopt _**Cuckoo Cycle**_ as our memory bound PoW system.

### The plight of a public ledger - How to maintain anonymity and fungibility?

Bitcoin's privacy model is said to be pseudo-anonymous, which reveals the public key that signs the transaction but not the participant's identification information - such as IP addresses. Since the blockchain is a permanent public ledger, such measure (public keys as the only identifying informaiton concerning participants) is a necessary protection of privacy - and it is still way ahead of privacy mechanisms of the centralized regime (banking) where participnats must trust a third party to protect their privacy and often times private and sensitive information gets leaked and nothing further could be done to stop the leaking - as in the digital world information is compromised forever once it is revealed.

However, Bitcoin's privacy protection scheme stops short at this pseudo-anonimity - as everything else - the whole transaction history is made public - the very nature of a public ledger! And as it turns out - even this pseudo-anonimity isn't quite the protection participants think it is - there are many ways to match and link the patterns of transactions of suspicious addresses to real world identities and once this thin layer of protection - key addresses - are revealed and gone, Bitcoin is but an open book.

Bitcoin is not only weak in the privacy aspect - but also in the original goal of its existence - digital cash. For a long time in history cash is the main form of money that is both ubiquitous and fungible - meaning every unit of money should be indistinguishable from each other. The fungibility of cash is also a protection mechanism of privacy - cash has no memory. This runs against the nature of Bitcoin or any blockchain based cryptocurency - the blokchain has all the memory. As Bitcoin's addresses can be tracked and their associated transactions matched - it weakens Bitcoin's role as a fungible digital cash. There are already cases that people pay premiums seeking recent coinbase Bitcoins - which are coins just created and thus considered "cleaner".

#### _Confidential Transactions to the Rescue_

Because of these weaknesses of Bitcoin regarding privacy and fungibility people have been trying to find ways to mitigate the situation. Methods such as Greg Maxwell's CoinJoin, which allows users to hide the transaction amount by merging two or more transactions, and Monero, a cryptocurrency with strong privacy protection mechanisms in its design, employs stealth adresses, ring-signatures and ring confidential transactions. As we discussed in previous sections - Greg Maxwell's _**Confidential Transactions**_ and subsequent improvement by _MimbleWimble_ utilize _Homomorphic Commitments_ and _Range Proofs_ to implement a fully anonymous and fungible cryptocurrency design - the result blockchain almost hides everything related to a transaction - transaction parties, transaction amounts, etc - to an observer all you see in the blockchain are just universally random curve points.

The _MimbleWimble secure blockchain design really hits two bird with one stone - as we discussed in an earlier section, cancelled out inputs and outputs could be dropped from the blockchain completely and the blockchain can still be fully validated - this not only reduces the blockchain size but also has implication for privacy - by dropping majority of transactions the blockchain itself achieves a great deal of privacy - since after pruning most of the transaction history is gone (while the blockchain can still be fully validated) and there is no transaction detail to leak from.

With true anonimity and fungibility we would have a strong _**privacy-preserving transaction**_-based blockchain and cryptocurrency.

Usually the priacy-preserving protection of a blockchain stops at transactions. But with the powerful primitives from _MimbleWimble_ we can extend the privacy-preserving protection to smart contracts. We'll discuss this aspect in the next section.

### All is Fair in Love and War and Smart Contracts?

The _Nakamoto Blockchain_ is a public ledger with transactions of amounts - these amounts reflect how people use the blockchain and the associated cryptocurrency. In the beginning cryptocurrency such as Bitcoin aims to be a digital cash system. Cash is simple, powerful and stateless. Yet when Satoshi Nakamoto first built the Bitcoin software he added something not in his famous white paper - scripts. In Bitcoin each transaction output is described by a script - or we can say that each output is predicated on a script. Scripts in Bitcoin provide complex rich functionalities - such as _multi-signature_.

However, Satoshi didn't make Bitcoin scripts an expressive - he even rolled back features - mainly to prevent DDOS attack on these scripts. This is because more expressive and complex scripts would make checking bounds on these scripts impossible - thus a "fat" scripts may deplete computing resources, resulting in cerntain outcomes that might jeopardize the blockchain itself.

These scripts are what has been called _**Smart Contracts**_, which was first brought up by Nick Szabo in the 1990s. In our context _Smart Contracts_ refer to special computer fragments (little programs) carrying cryptographic primitives to produce outputs in a blockchain transaction. In Nick Szabo's vision _Smart Contracts_ can act like a digital form of legal judgement and are described as being able to enforce "Law of Code" in the digital world similar to judicial devices such as a real legal contract in the physical world.

Bitcoin scripts are inherently limited in order to protect the blockchain from Denial of Service attacks. Even so Bitcoin scripts are still quite powerful in implementing many crucial crypto mechanisms such _multi-signature_, _atomic swap_, _payment chennels_, etc.

Efforts have been invested ever since Bitcoin started the _Smart Contract_ era. Ethereum, another major prominent cryptocurrency after Bitcoin, bid itself as the engine to drive ubiquitous _Smart Contracts_, not merely as digital cash, but also digital assets, as well as arbitrary decentralized applications called DApps - in that sense Ethereum calls itself a "World Computer". Ethereum boasts the implementation of a fully decentralized _**Turing Complete**_ language for writing and running _Smart Contracts_, which means it can support advanced computer language features such as conditional branching, recursion and function reentrancy. These features made Ethereum powerful, and dangerous.

The powerful _**Turing Complete**_ language made Ethereum _Smart Contract_ vulnerable to ill-formed _Smart Constract_ implementation. There had been incidents that lost millions of coins by ill-constructed _Smart Contracts_ that power DApps managing large amounts of coins (which worth hundred of millions of US Dollars). It seems that _**Turing Complete**_-ness is a double edged sword - self-inflicted wounds are almost unavoidable. The power of _**Turing Complete**_-ness concentrated on a single blockchain managing values, in the hands of often immature DApp developers, makes Ethereum very sensitive to even simple programming errors. This low programming fault tolerance is a crucial weakness for Ethereum to be a "system" language for developing DApps that manage values.

Ethereum's low throughput (~30 TPS) doesn't help it being the "World Computer" either - it got choked a lot when popular DApps such as those lauching cryptocurrencies based out of Ethereum _Smart Contracts_ (the so called ERC-20 _Smart Contract_) suddenly released and overwhelme the Ethereum network. Other examples include a very popular, first of its kind decentralized blockchain game called _**CryptoKitties**_. Of course this phenomenon is not directly related to the design of Ethereum's _Smart Contract_ engine but it did compounded the symptom.

So what are the features of Soteria that would solve or at least improve on the current generation of _Smart Contract_ design?

Soteria's _Smart Contract_ design would focus on the following issues:

1. Simplified state processing model in accordance to Soteria's block DAG architecture
2. Privacy-perserving _Smart Contracts_ in accordance with Soteria's _MimbleWimble_ transaction construction model
3. Alternative to _**Turing Complete**_ _Smart Constract_ language and virtual machine primitives

#### _Predicate Extended UTXO-based State Transition Model for Smart Constract_

<!-- Ethereum: heavy chains light client; Soteria: Light chains heavy client -->

In general a blockchain runs like this:

1. Blockchain is a replicable state machine and transactions update the states.
2. In each state the blockchain consensus protocol determines if a transaction is valid given some rules.
3. miners sequence the valid transactions into blocks and get rewards

Blockchain is a replicable state machine since it is replicated by all network full nodes and all the replicated state machines are kept in sync by the blockchain consensus protocol.

And _Smart Contracts_ are the rules that each full node user relies on to determine if transactions are valid (or not).

We can further abstract these rules into a _**predicate**_ that must evaluate to be true to have the transacton included into a block.

This model describes both Bitcoin and Ethereum - the differences between the two are subtle and are within the transaction itself (beyond transactions are blocks and consensus protocols which are quite similar in structure for both Bitcoin and Ethereum for now):

Bitcoin - Bitcoin has the _**UTXO**_ model: each transaction contains a list of _**UTXOs**_ to represent different states; each _**UTXO**_ unit has an input (received from another output), which is an amount in units of Bitcoins, and an output, which is a sequence of script code that would produce an output in the amount of units of Bitcoins. Transaction changes states by executing the scripts. _**UTXOs**_ can be created and destroyed. The states are limited to amounts of Bitcoins associated with some addresses.

Ethereum - Ethereum has the _**Constracts**_ model: each transaction contains a list of _**Contracts**_ to represent different states; each _**Contracts**_ has an account balance in units of _Ether_ (the cryptocurrency unit for Ethereum) and a sequence of program code which when executed would change the transaction states. New _**Contracts**_ can be created and old destroyed. States in Ethereum transactions do not only concern account balance but arbitrary variables representing values (other than _Ethers_).

Ethereum _**Contracts**_ has the form of a _**Turing Complete**_ program but actually is not - to prevent those programs that never terminate due to intent or bug, Ethereum has implemented a _**Gas**_ sysetm - every _**Contracts**_ is bound by the total _**Gas**_ limit as well as individual _**Gas**_ limit. Therefore every Ethereum _**Contracts**_ will always terminate within a predetermined bound, making it _**Non-Turing Complete**_.

Nonetheless, Ethereum's _**Smart Contract**_ is considered to be very expressive, so much that many think it is too dangerous to handle money and assets. Many lost millions due to simple programming errors and bugs in software libraries.

On the other hand Bitcoin's script system is considered to be quite safe and robust yet limited in expressive power. It can do somethings very straightforwardly and others tricky to implement or too difficult to figure out even by experts.

Let's go back to our simple and general blockchain model in the beginning of this section - that we can abstract the rules in a transaction to a _**predicate**_ which is another saying for "condition" in formal logic parlance. _**Predicates**_ are not as expressive as functions but with some tweak can be easily made so. We can add arbitrary function inputs to transactions to make _**predicates**_ as expressive as functions.

If we define computable functions on natural domain N that are defined by a  Turing machine, lambda calculus  term or general recursion, we can then further define computably enumerable (C.E.) _**predicates**_ on N. Now we have this _**C.E. predicates**_ that are the broadest class of predicates that we can programmatically define [#Citation - Emil Post]. By utilizing _**C.E. predicates**_ we can have _Turing-complete_ equivalent predicates and reducing validating these predicates to simpler predicates with a _**witness**_. a _**witness**_ is also a kind of condition for our special domain _**predicate**_. There are several types of _**witness**_ we can choose for our _**predicate**_, for example, we can have a _Gas-based_ _**witness**_, such as in Ethereum. We can also have a _Trace-based_ _**witness**_, which encodes the sequence of all intermediate states within a transaction. The benefit of a _Trace-based_ _**witeness**_ is that it is very simple and flexible but could have redundancies. So we should design our blockchain languae somewhere in between (_Gas-based_ and _Trace-based_).
