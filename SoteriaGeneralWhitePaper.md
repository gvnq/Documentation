# Soteria General White Paper v1
&nbsp;


**April 14, 2018**
&nbsp;

---
&nbsp;

<!-- TOC -->

- [What is Soteria?](#what-is-soteria)
  * [DEFINITION](#definition)
  * [FEATURES](#features)
    + [Next Generation POW-based crypto consensus protocols](#next-generation-pow-based-crypto-consensus-protocols)
    + [Anti-ASIC Memory-based POW Mining Algorithm](#anti-asic-memory-based-pow-mining-algorithm)
    + [Practical Blockchain Compression and Size Reduction](#practical-blockchain-compression-and-size-reduction)
    + [Next Generation Privacy-Preserving Transactions](#next-generation-privacy-preserving-transactions)
    + [UTXO-based Transaction System](#utxo-based-transaction-system)
    + [UTXO-based Smart Contracts](#utxo-based-smart-contracts)
    + [State Channels for Interactive Micropayments](#state-channels-for-interactive-micropayments)
    + [Side-chain Compatibility](#side-chain-compatibility)
    + [Governance](#governance)
  * [DESIGN PRINCIPLES](#design-principles)
  * [CLARIFICATION](#clarification)

&nbsp;


# _What is Soteria?_

## DEFINITION

Soteria is the code name for the umbrella of protocols that IOCT is built upon. Soteria is the foundation of IOCT. Soteria is not a single computer network protocol or even a set of protocols at that - it is the aggregate of protocols, roadmaps and governance rules that expand to the future - it is a social contract. Soteria is built with cryptographic as well as game theoretic mechanisms to strike a balance among different incentives in a dynamic, heterogenous network comprised of autonomous and intelligent agents.

Nonetheless, Soteria is as much a rigorous computer protocol set as any other such protocol(s). Soteria is self-governed by a flavor of its own  ELEOS smart contracts.



## FEATURES

Some of the key features of Soteria are:

### _Next Generation POW-based crypto consensus protocols_

Soteria will implement (in two stages) Full Network Capacity Scalable POW (Proof-of-Work) based consensus protocols - fist Checkpoint GHOST (like Bitcoin-NG), then Recursive Block Voting DAG (SPECTRE).

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
