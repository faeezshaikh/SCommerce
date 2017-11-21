# SCommerce
A Blockchain-Based Decentralized Trustless Reputation building Escrow Protocol.
November 15, 2017





## Overview
SafeCommerce is a blockchain-based decentralized escrow protocol that aids and incentivizes blockchain transactors and Decentralized app (Dapp) developers to safely transact and leverage their transactions to build reputation on the blockchain. It eliminates the need for developers to build complex trust enabling payment settlement systems into their Dapps.

## Problem

* **_Pseudonymity Issues_** : The pseudonymous nature of the blockchain while advantageous in many respects also poses several limitations and barriers in transacting business on the blockchain. The current ecosystem requires blind trust in one or both of the transaction participants. These parties possess no known identity other than their respective blockchain addresses (hashes). While this may be advantageous in some cases, the lack of any information about the account holder is a huge deterrent in doing business on the blockchain. In its current nascency the blockchain lacks a completely autonomous decentralized reputation system, that can provide assurance while still retaining anonymity on the blockchain.

* **_Complex payment settlement systems_** :  In absence of such a decentralized service, Dapp developers are forced to code complex payment settlement solutions into their Dapps. In a majority of cases, such payment settlement solutions are an evil necessity for these Dapps that take away precious development time which could be otherwise devoted to solving real world business problems by the developers. In reality, since the advent of blockchain protocols like Ethereum, developers of decentralized apps (Dapps) have always struggled to create or integrate some sort of online service that can be used to manage trusted commerce between two parties.


Let’s say that Kathy and Bob want to transact business with each other on the Ethereum blockchain. Kathy wants to remotely sell Bob her camera for 5 ETH. Bob needs the camera to be as good as described by Kathy, and Kathy needs to be sure she gets paid as agreed. Thus, no one wants to make the first move.
In the current landscape, the above transaction may only be possible through custom Dapps. Although the Dapps in this case may enable peer to peer trading, the payment settlement has to occur through the Dapp. In essence, the payment settlement is not decentralized and the users have to trust the Dapp to settle their debts. Likewise, if Kathy wishes to purchase an item of jewelry she likes through another Dapp, she will have to repeat the payment through the new Dapp and trust this new Dapp to settle the payments on the blockchain. Moreover, the Dapps provide no incentive or reward for her track record of settling payments on the blockchain on time and as promised.
The Dapp developers are forced to write custom payment settlement modules for these Dapps, which may not be the critical feature of the Dapp. The Dapp may be a commercial shopping platform like amazon.com focused on enabling peer to peer merchandise trading.

## Solution

SafeCommerce is a global open platform that provides a reputation and loyalty based escrow service. It is a transparent and audit-friendly safe protocol that leverages the full potential of the Ethereum decentralized consensus ecosystem. 

In its standalone mode, the SafeCommerce platform can be used by individual traders to safely conduct peer to peer trading in a safe and guaranteed manner while still retaining anonymity on the blockchain. The platform’s APIs can be used by other Dapp developers to to facilitate commerce in their decentralized applications. Developers no longer have to reinvent the wheel every time by building a payment settlement system into their Dapps. The SafeCommerce protocol abstracts the intricacies of complex debt settlement and Dapp developers can simply leverage the protocol by invoking APIs for the platform.

The SafeCommerce platform provides guaranteed assurance of debt settlement by allowing users to build reputation on the blockchain while retaining anonymity.


## How it Works

Going back to the above example,  with SafeCommerce, Kathy and Bob’s account both escrow an amount of value (an agreed upon “Declared Value” aka DV) that will be used both as a custodian for the transaction and as a payment for Kathy’s Camera. 

So, both Kathy and Bob will escrow 5 ETH + 0.3 ETH (6% of Declared value) + 0.05 ETH (1% of Declared value) for a total of 5.35 ETH into the SafeCommerce platform. This process makes use of our “multi-sig” digital smart contracts, this means the funds can only be unlocked if both Kathy and Bob agree that the terms were completed.

Once the SafeCommerce transaction has been funded and locked by both parties, Kathy will provide/ship the camera to Bob. Upon receipt Bob checks that it looks as described and that it works fine. If it meets all the advertised specs and performs as it should, both parties move forward to complete the SafeCommerce agreement, at which time the agreed upon amounts are disbursed as per the terms in the smart contract.

After checking the camera Bob signs the payment transaction with his private key at which point Kathy is notified and will have to do her part and sign.

Kathy then signs the transaction herself. Since both parties have signed, funds are immediately unlocked. Kathy receives her 5 ETH of escrow + the price of the camera she just sold (5 ETH) from Bob’s account. Bob receives his camera and 5 ETH is deducted from his account. Simultaneously the fee of 1% is now deducted and released from both accounts to SafeCommerce. (0.05 ETH x 2 = 0.1 ETH). The remaining 6% (0.3 ETH) stays in both customer’s respective accounts to build up their future reserve and reputation in the SafeCommerce system.
TODO:  Add diagram to describe the above transactions.

### Reputation Scoring (Rating) system:

In the above example, the 6% of the Declared Value (0.3 ETH) that was deposited by the participants, remains in the SafeCommerce platform in the participant’s account as a future reserve balance. This reserve balance is a critical component for building a reputation score for the account holder. The score is calculated as follows:
 
![alt text](https://drive.google.com/file/d/1B836mJX881eqVQloJnaWa7volYWo-bzW/view?usp=sharing "Formula")




SCTS
The number of blockchain transactions
 accounts (addresses) the user has registered with SafeCommerce under his/her SafeCommerce primary account.
SCAA
SafeCommerce account age. Initiated with first transaction.
Claims
The number of claims made by the account holder against his/her SafeCommerce account.
Score
A numeric value that translates into a reputation score.

| Term	        | Description	|
| ------------- |:------------- |
| SCTS		| The number of blockchain transactions the user has registered with SafeCommerce under his/her SafeCommerce primary account.| 
| SCAA	        | SafeCommerce account age. Initiated with first transaction.      |   
| Claims	| The number of claims made by the account holder against his/her SafeCommerce account.      |    
| Score		| A numeric value that translates into a reputation score.      |    


## Standalone mode:

The following depicts the various transaction scenarios between two participants Kathy and Bob.

1 ) Kathy downloads the free SafeCommerce mobile app from the appStore (iOS or Android)
2) She signs in with any of the popular Web Identity Providers (Google, Amazon, Facebook, Github)
3) Once logged in, she creates a new ‘Agreement’ inside the app.
4) For creating a new Agreement, Alice has to enter the following details:
	* Account address (public key) of Bob (the party with which Alice is entering into an agreement)
	* The ‘Declared Value’ (the escrow amount)
	* The agreement deadline date
	* The funding deadline (date)
	
	
## SafeCommerce Plans and Loyalty Program:
TBD

### Monetization
TBD
		TREX Tokens:
Milestones
Lorem ipsum
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
Dolor sit amet
Lorem ipsum dolor sit amet, conse`78actetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
Consectetur adipiscing elit
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.

[\
