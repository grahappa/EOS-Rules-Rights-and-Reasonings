# EOS Blockchain Rules, Rights and Reasonings
For `chain_id`: aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906

## Preamble 

**We The Vested Account Holders of the EOS Blockchain,** 

* In order to form a more perfect distributed ledger of transactions, 
* Using cryptographically secured accounts, structured actions, 
* Ricardian and automated smart contracts,
* Built on a globally decentralized platform of free expression,
* That is without jurisdiction or censorship,

**Establish these Rules, Rights and Reasonings for the EOS Blockchain.**

**H**erein represents the human-readable intent of the underlying source code protocol of the EOS Blockchain which enables Block Producers to;  

* Discern which code to execute and which code not to execute, 
* Identify the difference between bug and feature,  
* Guide the community on what fixes are proper or improper when errors occur.

**T**his governing document is to be considered a peer-to-peer, time-infinite, binding multi-party contract.

**E**very transaction broadcast on the EOS network shall incorporate the hash of this document as part of the signature, thereby explicitly binding the signer to this contract.


## Rules

### Article XXX - Block Producer Role  
From an infinite pool of candidates, the top twenty one Block Producers determined by a EOS Token Holder vote of staked tokens, shall execute code that creates an operating system-like construct based on accounts, authentication, automated contracts, databases, asynchronous communication, and scheduling, across many CPU cores or clusters, resulting in a feeless scalable decentralized blockchain architecture upon which applications and their services can be built.

### Article XXX - Delegated Proof of Stake
Block Producers shall execute code that defines a collective decision making process to validate transactions thru a decentralized consensus algorithm known as Delegated Proof of Stake(DPOS), which shall be considered Byzantine Fault Tolerant(BFT) by it's capacity to coordinate strategic responsiveness to system fault or attack. 

### Article XXX - Block Producer Voting
EOS Token Holders shall elect Block Producers through a continuous approval voting system based on thier ability to effectively produce blocks, contribute to the EOS ecosystem and operate in accordance to this governing document.  EOS Token Holder votes shall decay approximately 1% per week.

### Article XXX - Native Unit of Utility
The EOS token shall be the native unit of value representing access to utility resources on the EOS Network including but not limited to; 

* Bandwidth and Log Storage (Disk), 
* Computation and Computational Backlog (CPU) and
* State Storage (RAM).

### Article XXX - Sanctity and Governence of Contract
Block producers shall not freeze or modify contracts, except;

* When Block Producers deem a contract not operating as intended. The determination of the intent of code by Block Producers shall consider code, human-readable and machine-redable Ricardian Contracts, user interfaces, and actual use. If there is a dispute over the intent of code, then intent shall be determined by a super majority vote of elected Block Producers. A super majority is defined as 15 of the 21 elected Block Producers.  This super majority may, at their discretion, freeze a smart contract during an active dispute until such time as code to amend the smart contract is available and vetted. The parties to the dispute must produce proposed replacement code to the smart contract. Block Producers may charge a reasonable fee and/or place other reasonable requirements upon the parties to the dispute.  Ricardian contractual terms that cannot be enforced by properly functioning code are beyond the scope of the producers authority to evaluate and enforce.

### Article XXX - Self Liability
Contributors to this system including smart contract developers and authors of governing documents are not liable for damages caused by unintentional bugs in code or unintentional effects of governing documents.  All Parties are responsible for auditing smart contracts and their equivalent Ricardian contract before use.

### Article XXX - Ricardian Contract Disclosure
All service providers facilitating the construction and signing of transactions on behalf of EOS Account Holders shall present the full Ricardian Contract terms of this governing document and all other referenced smart contracts.

### Article XXX - Ricardian Contract  Acceptance
A Ricardian Contract is deemed accepted when a transaction based on that contract is incorporated into the blockchain.

### Article XXX - No Fiduciary Relationships
No Party shall have a fiduciary responsibility to support the value of the EOS token. 

### Article XXX - No Representation
No Party shall be authorized to hold assets, borrow, speak nor contract on behalf of EOS token holders or the blockchain collectively. This blockchain shall have no owners, managers, or fiduciaries.

### Article XXX - No Jurisdiction
No Party shall claim a seat of governance or jurisdiction for the EOS Blockchain.

### Article XXX - Token-Weighted Common Accounts
EOS accounts held in common to all EOS Account Holders and in proportion to their tokens include the following;

* eosio.names,
* eosio.ramfee, 
* eosio.saving.

### Article XXX - Voluntarily Consent
All Parties voluntarily consent for all other Parties to permanently and irrevocably retain, copy, analyze, and distribute all broadcast transactions and derivative information. Use of the blockchain shall constitute consent to its terms.

### Article XXX - On-Chain Referendums
Referendums must be submitted on-chain either in full text or as a hash of the referendum text. A Referendum is considered approved for execution once 

* at least 15% of issued tokens have staked and registered a vote for a specific referendum,

* ‘affirmative’ tokens exceed the number of ‘negative’ staked tokens by a difference of no less than 10% of total percentage of registered votes (i.e. 55% yes, 45% no). 

* These requirements must remain satisfied above the minimum requirements for a period of at least 30 consecutive days within a 120-day sustainment period per Referendum. Should a Referendum not be approved for execution within the 120-day period, it is considered expired and must be resubmitted if another vote is desired. The 120-day period starts when the transaction which includes a referendum is appended to the blockchain. EOS tokens issued during the 120-period are counted toward the total issued amount calculation.  Referendums may then be enacted by a super majority of Block Producers defined as 15 of the 21 elected Block Producers.

### Article XXX - Block Producer Nomination
Block Producer `{{ producer }}` candidates shall nominate themselves and register their intent to produce blocks on the EOS Blockchain by executing the `{{ regproducer }}` contract.

### Article XXX - Block Producer Key Control
Elected Block Producers shall produce blocks by executing signed `{{ eosio }}` contracts with their unique cryptographic private `{{ producer_key }}` and attest to maintain the secrecy of this key under their sole control.

### Article XXX - Block Producer Non-Performance
Block Producers shall resubmit the `{{ regproducer }}` contract with a `{{ producer_key }}` of `{{ null }}` if they are unable to perform obligations of the `{{ regproducer }}` contract.

### Article XXX - Objective Validity
Block Producers shall acknowledge that a block is considered 'Objectively Valid' if it conforms to the deterministic blockchain rules in force at the time of its creation, and is 'Objectively Invalid' if it fails to conform to those rules.

### Article XXX - Block Producer Keys
Block Producers shall only use their {{producer_key}} to sign messages under the following scenarios:

* Proposing an objectively valid block at the time appointed by the block scheduling algorithm.
* Pre-confirming an objectively valid block produced by another producer.
* Confirming a block for which {{producer}} has received pre-confirmation messages from more than 2/3 of the 21 active Block Producers.

### Article XXX - No Double-Signing
Block Producers shall not double-sign for a timestamp or block number.

### Article XXX - Block Production Violations
Block Producers shall not;
    
* Sign two different block proposals with the same timestamp with {{producer_key}} 
* Sign two different block proposals with the same timestamp with {{producer_key}} 
* Sign any block proposal which builds off of an objectively invalid block 
* Sign a pre-confirmation for an objectively invalid block 
* Sign a confirmation for a block which they do not possess pre-confirmation messages from more than 2/3 of the 21 active Block Producers.

### Article XXX - Voting Process Violations
Block Producers shall not interfere with the Block Producer or Referendum voting by;

* Processing all vote transactions that occur in blocks they create,
* Signing all objectively valid blocks they create that contain vote transactions,
* Signing all pre-confirmations and confirmations necessary to facilitate transfer of control to the next set of Block Producers as determined by the system contract.

### Article XXX - Block Producer Disqualification
Elected Block Producers may disqualify another {{ producer }} by a vote of 15 of 21 Elected Block Producers, in the event the {{ producer }} is unable to produce blocks or is unable to be reached based on criteria agreed to among Block Producers.

### Article XXX - Active Block Producer Obligations
Block Producers earning rewards shall;

* Provide a public endpoint allowing at least 100 peers to maintain synchronization with the blockchain and/or
* Submit transactions to be included into the blockchain.
* Maintain at least 1 validating node with full state and signature checking.
* Publically report any objectively invalid blocks produced by the active Block Producers via a publically reported method to be agreed upon among Block Producers.

### Article XXX - Block Producer Peer Authentication
Block Producers shall authenticate peers as necessary to prevent abuse and denial of service attacks without discriminating against non-abusive peers.

### Article XXX - Block Production Order and Billing
Block Producers shall process transactions on a First-In-First-Out best-effort basis and to honestly bill transactions for measured execution time.

### Article XXX - Block Production Falsification
Block Producers shall not derive profit by manipulating;
    
* The order in which transactions are included into a block,
* The hash of any block produced.

### Article XXX - Block Producer Beneficiary Disclosure
Block Producers shall disclose all ultimate beneficiaries of their organization who own more than 10% and all direct shareholders.

### Article XXX - Block Producer Cooperation
Block Producers shall cooperate with other Block Producers to carry out their respective and mutual obligations under this contract, including but not limited to maintaining network stability and a valid blockchain.

### Article XXX - Block Producer Disclosure
Block Producers shall maintain a website hosted which contains up-to-date information on all disclosures required by this contract.

### Article XXX - Block Producer Server Location
Block Producers shall set a server location that minimizes latency between both previous and next peers within the round-robin block producing schedule. 

### Article XXX - Block Producer Time Synchronization
Block Producers shall maintain time synchronization within 10 ms of global atomic clock time using a method agreed to among Block Producers.

### Article XXX - Block Production Scheduling
Block Producers shall not produce blocks before their scheduled time unless they have received all blocks produced by the prior scheduled Block Producer.

### Article XXX - Block Production Timing
Block Producers shall not publish blocks with timestamps more than 500ms in the future unless the prior block is more than 75% full by either CPU or network bandwidth metrics.

### Article XXX - Block Producer RAM Requirements
Block Producers shall cease producing blocks if they are unable to provide the RAM as shown in the system parameters and approved by 15 of 21 Elected Block Producers.

### Article XXX - Block Producer RAM Overstatement
Block Producers shall not set their RAM supply parameter to more RAM than their nodes actually contain.

### Article XXX - Block Producer Compensation
Block Producer shall be compensated for services provided by an automated 1% rate of inflation to the EOS token and transferred from the `{{ eosio.vpay }}` account to their account submitted to the `{{ regproducer }}` contract.

### Article XXX - Open Source Software
Block Producers shall only execute code that is offered under an open source software license.

### Article XXX - Authentication Credentials
Block Producers shall not be responsible for maintaining the authentication credentials of EOS Accounts, including but not limited to the secrecy of private keys, except for their own accounts or those they control while fulfilling their role of Block Producer as defined in this document.

### Article XXX - Block Producer Scope of Operations
Block Producers shall review, test, implement, optimize, and upgrade the code defining the active EOS blockchain codebase.  Block Producers shall not alter any governing document or execute actions that may alter the current state of any tokens considered common to EOS Accounts without prior authorization obtained through Referendum as defined in this document.

### Article XXX - Proxy Vote Delegation
Block Producers shall execute code that permits EOS Account Holders to delegate their right to cast Referendum or Block Producer votes to an EOS Vote Proxy of their choice.  Proxied votes of any kind, shall decay at the same rate as direct EOS Token Holder votes as defined in this governing document.

### Article XXX - Proxy Registration
EOS Vote Proxies shall register their intent to proxy the votes of other EOS Account Holders by executing the `{{ regproxy }}` contract.  

### Article XXX - No Service Provider Favor or Discrimination
Block Producers shall execute no code that discriminates or favors any service provider over another.

### Article XXX - Block Producer Stand-bys 
Block Producers shall execute no code that denies, abridges or impairs the Stand-by Block Producers in preparing to produce valid blocks.

### Article XXX - No Vote Buying or Trading
Block Producers shall not offer nor accept anything of value in exchange for a vote of any type, nor shall any Member unduly influence the vote of another.

### Article XXX - Scope of This 
All actions executed on the EOS Blockchain are bound to the entirety of this governing document including those made directly by EOS Account Holders and any service providers on thier behalf.

### Article XXX - Entire Agreement
This agreement represents the entire understanding between the parties with respect to its subject matter and supersedes any previous communication or agreements that may exist.

### Article XXX - Amendments to This Governing Document
This governing document may be amended by a direct vote Referendum in which all EOS Token holders may vote per proposal as prescribed in this document. Referendums proposing amendments to this governing document shall be considered ratified when 15 of 21 Block Producers execute code accepting the amended governing document. 

## Rights

### Article XXX - Freedom of Expression
Block Producers shall execute no code that favors, abridges or denies Actions based on their content.

### Article XXX - Freedom of Privacy
Block Producers shall execute no code that diminishes, invalidates or impairs the strength of encryption that may protect accounts, contracts, or any aspect of the system.

### Article XXX - Freedom From Discrimination
Block Producers shall execute no code that denies, abridges or impairs an account based based on race, color, religion, sex, or national origin or political affiliation.

### Article XXX - Freedom to Transact
Block Producers shall execute no code that freezes, invalidates or deletes accounts or their associated resources, including but not limited to processing power, network bandwidth and memory.

### Article XXX - Freedom From Impersonation
Block Producers shall execute no code that seizes or transfers or executes any transaction without the explicit consent of the account holder.

### Article XXX - Freedom to Proxy
Block Producers shall execute no code that denies, abridges or impairs the direct or proxied vote of either Block Producer or Referendum. 


## Reasonings

### Article XXX - YYY clause
Voluptatum illo tempore natus dignissimos est nisi. Ut quod eos pariatur et quisquam voluptate quis. Amet occaecati enim rerum nam veniam autem ut recusandae. Quam qui repudiandae molestiae incidunt quibusdam minima officiis. Voluptatum exercitationem qu…

### Article XXX - YYY clause
Voluptatum illo tempore natus dignissimos est nisi. Ut quod eos pariatur et quisquam voluptate quis. Amet occaecati enim rerum nam veniam autem ut recusandae. Quam qui repudiandae molestiae incidunt quibusdam minima officiis. Voluptatum exercitationem qu…

### Article XXX - YYY clause
Voluptatum illo tempore natus dignissimos est nisi. Ut quod eos pariatur et quisquam voluptate quis. Amet occaecati enim rerum nam veniam autem ut recusandae. Quam qui repudiandae molestiae incidunt quibusdam minima officiis. Voluptatum exercitationem qu…







