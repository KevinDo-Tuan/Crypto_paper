# Infrastructure for the New World

**Author:** Do Pham Tuan Kevin  
**Date:** January 31, 2026

---

## Table of Contents

1. [Abstract](#i-abstract)
2. [Vision](#ii-vision)
3. [Understanding Blockchain Technology](#iii-understanding-blockchain-technology)
4. [The Automated Future and Its Inherent Threats](#the-automated-future-and-its-inherent-threats)
   - [Dependency](#dependency)
   - [Security](#security)
   - [Transparency](#transparency)
5. [Current Limitations and Evolution](#v-current-limitations-and-evolution)
6. [Conclusions](#iv-conclusions)

---

## I. Abstract

This paper examines the fundamental purpose of blockchain technology and its role in shaping the future of digital infrastructure. As artificial intelligence automates an increasing proportion of internet applications, the question of trust in all applications becomes paramount. With this concern in mind, I argue that blockchain-based decentralized autonomous organizations (DAOs) offer a superior governance model compared to centralized parties. The paper is not able to be finished without a thorough self-analysis of blockchain's core mechanisms - immutable transaction records, algorithmic governance, and transparent protocol upgrades, and importantly, the Internet Computer whitepaper: [*whitepaper.pdf*](https://internetcomputer.org/whitepaper.pdf) along with its technology.

---

## II. Vision

> "Some people want to change the world and others want to operate in simple harmony with it and savor life." - Principles, Mr. Ray Dalio.

Recently, as a breakthrough and newborn technology, Artificial intelligence has emerged as one of the most superior technologies humanity has ever created. Not only does it completely save tons of money, it also saves tons of time and human resources. In the past, there was no company that can survive with just 1 founder; yet, it is totally different now. There are many companies that not only survive but also thrive with just 1 founder, Uniswap foundation (Hayden Adams), BuiltWith (Gary Brewer),... Not only that, through "vibe coding", a report shows that 100,000+ of applications are deployed daily, compared with just 4,100 projects deployed daily pre-AI. With the ability to recognize patterns and find the most optimal solutions (Generalization for every type of model, including but not limited to XGBOOST, Decision Tree, and neural network..), AI can virtually do most of the things that humans can do, not just coding. Theoretically, any actions and decisions that humans take, AI can replicate it with 100% similarities. Yet, the most important thing that it misses is the creativity that humans have. We have the creativity to think of something that has never been made before (even though I believe that those ideas are shaped by our interactions before). Just like in the Steve Jobs book written by Walter Isaacson, he describes Steve Jobs as having "an anarchic mind-set that is great for imagining a world not yet in existence." Only humans can think of something unique and has never done before. That's why it is hopeful to believe the future will be such that humans are the thinkers and AI (eg: Generative AI, Agentic AI,...) are the executors in a matter of time. The future that is not solely built of AI but also human. The future that there is mutual symbiosis coming from both of the parties.

Yet, though inevitable as it may seem, the future cannot be brought into reality without us eliminating some of the blockage for this future first.

---

## III. Understanding Blockchain Technology

Before discussing solutions for blockage of the future, we have to first understand blockchain technology, which will be a great aid for these next paragraphs.

### Virtual Machine Architectures

Contemporary blockchain ecosystems employ three primary virtual machine architectures, each with distinct capabilities and limitations:

- **Bitcoin Virtual Machine (BVM):** The original blockchain VM, designed specifically for secure value transfer with limited programmability

- **Ethereum Virtual Machine (EVM):** The most widely adopted architecture, theoretically Turing-completed smart contracts. However, most of its use cases are in DeFi because Ethereum couldn't understand what to do with some new arbitrary compiled code.

- **WebAssembly Virtual Machines (WASM):** Next-generation architectures designed for specific purposes or enhanced functionality beyond EVM limitations. Some are event-driven and some operated on timer or heartbeat. The prime examples that operate on-chain, record everything on-chain are ICP and AO on Arweave. 2 of the examples that I believe are the epitome of next-generation cloud computing.

The distinction between these architectures reveals blockchain's expanding capabilities. EVM's event-driven nature requires external Web2 protocols to trigger smart contracts---a dependency that introduces centralization. In contrast, WASM-based blockchains like the Internet Computer can initiate smart contracts autonomously and routinely, eliminating the need for Web2 intermediaries and achieving complete decentralization. This technical evolution matters because it demonstrates blockchain's trajectory toward true autonomy---a critical requirement for an AI-automated future.

---

## The Automated Future and Its Inherent Threats

As previously mentioned, it is worth noting that in the future, our actions will increasingly be automated as intelligent agents handle tasks on our behalf. In this emerging paradigm, humans will serve as strategic thinkers while AI functions as the executor of our intentions. However, as both long-term thinkers and experienced web2 developers recognize, there are three significant threats that could potentially undermine this vision of an automated, decentralized future: dependency, security, and transparency.

### Dependency

In centralized systems---such as those we currently operate within---cloud providers (which host AI infrastructure) and software providers (offering both general software and AI services) maintain complete control over both access and pricing structures. This concentration of power creates a fundamental vulnerability that threatens the promise of an equitable, automated future.

Human nature, as history consistently demonstrates, is characterized by continual desire for advancement and, unfortunately, by a tendency toward dissatisfaction. As society becomes increasingly dependent on cloud and software providers---operating under the aforementioned model where "humans are the thinkers and AI is the executors"---these providers inevitably recognize their position of leverage. Consequently, they will likely exercise this advantage by raising costs, restricting access, or imposing unfavorable terms on users who have few alternatives.

Historical precedent strongly supports this concern through numerous concrete examples. Consider Facebook's repeated algorithm changes: the platform initially promised to connect users with friends and family, encouraging businesses and content creators to build substantial followings organically. However, once these users became dependent on the platform, Facebook progressively reduced organic reach, effectively forcing businesses to pay for advertising to reach the very audiences they had cultivated. Users who had invested years building their presence found themselves suddenly unable to reach their own followers without paying the platform---a clear example of exploitation after dependency had been established.

Similarly, cloud service providers have demonstrated this pattern of post-dependency exploitation. Amazon Web Services (AWS), for instance, has implemented numerous price increases and structural changes after companies migrated their entire infrastructure to their platform. Once businesses had committed significant resources to AWS architecture, rewritten applications to work with AWS-specific services, and trained staff on AWS tools, switching to alternative providers became prohibitively expensive and technically complex. AWS, recognizing this lock-in effect, could then adjust pricing with relative impunity, knowing that customers faced enormous barriers to leaving.

Software companies have employed comparable tactics through product discontinuation and forced upgrades. Microsoft's termination of support for Windows 7, despite its widespread use, compelled millions of users and businesses to purchase new licenses or entirely new hardware. Adobe's transition from perpetual licenses to mandatory subscription models exemplifies this pattern: users who had purchased software outright suddenly found themselves unable to access updates or support without committing to ongoing monthly payments. Those who refused faced security vulnerabilities and compatibility issues that gradually rendered their purchased software unusable.

Consider a scenario where a single entity controls the software infrastructure underlying a critical system---whether healthcare records, financial transactions, supply chain management, or AI-powered decision-making tools. Users in such a system would face potential economic exploitation with virtually no alternative solutions. The switching costs would be prohibitively high, creating what economists term "lock-in effects," where users remain captive to a provider even when terms become increasingly unfavorable.

That being said, it would be naive to assume that DAOs represent a perfect solution without their own inherent challenges. DAOs can also impose governance structures that subjectively benefit certain participants, particularly those who hold larger token quantities and consequently wield greater voting power. It is unrealistic to assume that decentralization automatically eliminates human greed or the pursuit of self-interest. Any system that concentrates influence---whether through capital accumulation, reputation mechanisms, or voting power---will inevitably attract actors who seek to exploit these power differentials for personal gain.

The crucial factor, therefore, is that DAOs must propose and implement governance mechanisms specifically designed to minimize exploitation while maintaining decentralized decision-making. The Internet Computer Protocol (ICP) has demonstrated exemplary work in addressing these challenges. Their protocol is designed with a sophisticated understanding of the problems inherent in token-based governance systems. Specifically, ICP employs a combination of staked tokens and time-weighted commitment, whereby longer lockup periods translate into proportionally greater voting power. This mechanism aligns participant incentives with the long-term health of the network, as those with the most influence are precisely those who have committed to the platform's future success.

This example illustrates that there are numerous approaches to designing protocols that users can depend upon while simultaneously minimizing the ability of malicious actors to exploit systemic vulnerabilities. The key lies in thoughtful mechanism design that accounts for human incentives and potential attack vectors.

### Security

As you may or may not be aware, centralized cloud platforms store comprehensive records of every user interaction, message, and transaction. To understand the scale of this data collection, simply consider how your messaging applications retain complete historical records of all conversations---every word typed, every image shared, every interaction recorded and stored indefinitely on centralized servers.

This comprehensive data collection creates three fundamental security concerns that threaten individual privacy and collective security.

Firstly, such extensive data aggregation enables unprecedented surveillance capabilities. In centralized systems, jokes, personal opinions, political views, or entirely innocent communications can be continuously monitored, algorithmically evaluated, and potentially weaponized against users. Whether by government agencies, corporate entities, or malicious hackers who gain unauthorized access, this centralized repository of personal information represents an existential threat to privacy and freedom of expression. Users often fail to recognize that information shared in what they perceive as private contexts can be accessed, analyzed, and used in ways entirely contrary to their interests or expectations. The reason that blockchain can solve this is that the protocol source code can be verified and every log is disseminated and immutable. As a result, there is no chance that anyone maliciously exploited users' data without being known. That being said, for some political purpose, citizens need to be put under such circumstances and on-chain applications have to implement it. However, at least for such circumstances, users have the right to know that they are monitored.

Secondly, centralized data storage creates a critical single point of failure. In inherently, there are 2 types of data breach which hackers use to exploit data on data centers. The first way is that the hackers can directly exploit the credentials of administrators and employees who are entrusted with safeguarding the infrastructure. According to IBM's X-Force 2025 report, abusing valid account credentials accounted for 30% of all incident response engagements---tied as the most common initial access vector alongside exploitation of public-facing applications. CrowdStrike's 2025 findings paint an even starker picture: credential abuse represented 35% of all cloud-related security incidents in the first half of 2024, making it the single most common method attackers used to infiltrate cloud environments.

### Transparency

Firstly, out of the fear of 2008 financial crisis---where opaque financial instruments, hidden risk exposures, and lack of regulatory oversight precipitated global economic collapse---many people have come to recognize that what society fundamentally requires is a transparent system where actions, decisions, and their consequences are visible and verifiable.

Secondly, in traditional corporate structures, executives and boards of directors make consequential decisions behind closed doors, often without meaningful accountability to those affected by these decisions. Shareholders, despite their ownership stakes, receive only limited information about decision rationales, strategic planning, or the considerations underlying major policy changes. Even in publicly traded companies subject to regulatory disclosure requirements, the actual decision-making process remains fundamentally opaque. Upgrades, policy modifications, or strategic pivots often emerge without prior public consultation, leaving stakeholders to react to faits accomplis rather than participating in deliberative processes.

Blockchain-based DAOs, by contrast, operate on fundamentally different principles across multiple dimensions of transparency and accountability:

1. **Immutable Transaction Records:** Every transaction within a blockchain network is recorded permanently on a distributed ledger, making unilateral alterations mathematically and practically impossible. No single entity---whether a system administrator, corporate executive, or government agency---can modify transaction history for personal benefit or to conceal wrongdoing. This stands in stark contrast to centralized systems, where database administrators possess the technical capability to alter records, either maliciously or as a result of security breaches where hackers gain administrative access and redirect funds or manipulate data.

2. The mathematical proofs underlying consensus mechanisms---whether proof of work or proof of stake---ensure that altering historical records would require controlling the majority of network participants, an attack vector that is both economically prohibitive and practically infeasible for established blockchains. The security derives not from trusting a centralized authority, but from the mathematical certainty that fraudulent alterations would be immediately detectable and rejected by the network.

3. **Transparent Smart Contract Execution:** Smart contracts execute according to transparent, predetermined algorithms visible to all network participants, rather than depending on arbitrary human decisions that may be influenced by personal interests, political pressures, or hidden agendas. Consider, for instance, decentralized lending platforms operating on the Ethereum blockchain: interest rates calculated automatically based on supply and demand algorithms that are publicly auditable and verifiable. Every participant can examine the exact code governing these calculations, ensuring that no entity can manipulate rates for personal advantage. The code governs impartially, applying identical rules to all participants regardless of their status, connections, or influence. Centralized lending platforms, by comparison, can adjust interest rates arbitrarily based on undisclosed criteria, potentially favoring certain users, discriminating against others, or extracting additional profit during periods when user dependency is highest and alternatives are limited. Users have no way to verify whether they are receiving fair treatment or being systematically exploited, as the decision-making algorithms and business logic remain proprietary and hidden from scrutiny.

---

## V. Current Limitations and Evolution

Transparency requires acknowledging blockchain governance's current limitations. During 2025, major DAOs experienced significant challenges:

- **Declining Participation:** Voter turnout decreased across major protocols as initial enthusiasm waned and token-only governance proved insufficient to maintain engagement.

- **Whale Dominance:** Large token holders increasingly controlled voting outcomes, concentrating power despite theoretical decentralization.

- **Scaling Issues:** Governance processes proved slow for protocols requiring rapid operational decisions, leading some to pause or restructure their DAO models.

- **Professionalization:** Governance work has become increasingly complex, requiring specialized knowledge that casual token holders lack, driving delegation to professional voters.

However, these challenges demonstrate as-mentioned-before a healthy systemic evolution rather than fundamental failure. The blockchain ecosystem is actively addressing these issues through innovations including:

- **Hybrid Governance Models:** Separating operational decisions (handled by core teams) from strategic oversight (maintained by the community)

- **Economic Alignment:** Moving beyond governance-only tokens toward models with clear value capture, ensuring participants have economic incentives to protect the system

- **Formal Entity Formation:** Establishing legal structures to clarify liability and responsibility while maintaining decentralized decision-making

- **Improved Delegation Systems:** Creating professional delegate organizations with accountability mechanisms and compensation structures. Moreover, the blockchain ecosystem actively develops solutions to power concentration, including quadratic voting, conviction voting, and reputation-weighted systems that balance stake-based influence with other factors. These innovations emerge through open governance processes---proving the system's capacity for self-improvement. => all these improvements emerged through transparent public debate and on-chain governance---proving the system's self-correcting capacity.

---

## IV. Conclusions

### 1. The Coming Architectural Shift

To make a conclusion, I can now see the future digital infrastructure followed by this architecture: data centers run blockchain protocols, and blockchain protocols run applications. This model will eventually replace standalone centralized data centers, with DAOs replacing centralized companies as the primary organizational structure.

### 2. Web3 as the Next Application Wave

Current adoption metrics support this vision's feasibility. As of early 2026, over 50 million users actively engage with Web3 applications, with decentralized finance commanding 32% of daily decentralized application users. The Web3 market is projected to reach $81.5 billion by 2030, with some projections extending to $145 billion by 2028 as real-world asset tokenization matures. bMore significantly, 46.7% of finance applications now leverage Web3 technology, and 34% of game developers are integrating cryptocurrency. These adoption rates demonstrate that Web3 has moved beyond speculation toward practical utility---precisely the foundation needed for broader infrastructure transformation. The integration of AI with blockchain technology further accelerates this transition, with combinations of AI and blockchain increasing decentralized application productivity by 30%. This synergy enables the automated, trustworthy systems that humanity needs for the coming decades.
