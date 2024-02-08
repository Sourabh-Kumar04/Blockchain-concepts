# Blockchain-concepts


## What Exactly is Blockchain?
- Blockchain is a **tamper-proof distributed digital ledger**.
- This digital ledger is safe, secure, transparent, and decentralized, which simply means that it is not controlled by a single authority.
- It is like a ledger that a bank uses to keep track of all customer transactions. However, in a bank, the ledger is controlled by the bank, and only the bank can see the transactions.
- Whereas in blockchain, there is no central authority, and the ledger runs on multiple computers and doesn’t require any single person to authenticate or settle transactions.
- Blockchain is an unchangeable digital ledger that is collectively shared, enabling the seamless recording of transactions and monitoring of assets within a network.
- Assets can encompass both **tangible items** like houses, cars, cash, and land, as well as **intangible entities** such as intellectual property, patents, copyrights, and branding.
- Virtually any valuable item can be traced and exchanged on a blockchain network, leading to decreased risks and reduced expenses for all participants involved.



## What is a blockchain node?
Blockchains consist of a group of computers known as nodes. These nodes work together to synchronize the blockchain’s data, handle transaction requests, and reach consensus on the validity of those transactions.

#### Typea of Blockchian Nodes?







## What is a Block?
- With each data transaction taking place, it is documented and stored as a data block. These blocks form a chain of data.
- Blocks are arranged in a specific order, with new blocks added at the end of the chain.
- Each block includes a ***unique identifier called a hash***, which references the previous block. This is an important security feature of blockchain technology that makes it incredibly difficult to tamper with the ledger.
- In addition to important information like the time of the transaction and the record itself, every block contains the solution to a special puzzle that requires computational power to solve.

#### Types of Block
**1. Genesis Block-->** The very first block is the genesis block. Unlike other blocks, it doesn’t have a reference to a previous block because it marks the beginning of the chain.

**2. -->**
**3. -->**




## Structure of Blockchain




## What is Smart Contract?
- Smart contracts are **computer programs** that automatically carry out predefined parameters.
- The terms are coded directly into the program’s lines. This program is stored on a decentralized blockchain network.
- When specific conditions outlined in the code are met, the smart contract is executed automatically. Once the code is run, it cannot be undone or modified.
- Smart contracts offer a major benefit by allowing transactions and agreements to happen between parties who may not fully trust each other. This means that there’s no need for a third-party authority, legal system, or external mechanism to oversee the process. It allows for anonymous execution of agreements.






## What is a Decentralised Application(dApp)?
Smart contracts, or also called as Decentralized Applications (DApps) are applications that operate on a distributed computing system, specifically a blockchain network, rather than relying on a single server.
- When defining a DApp, they are typically characterized by being Open Source, Decentralized, and Cryptographically secure.
- DApps consist of two important components: the **frontend and the backend**.
- **The frontend is responsible for user interaction, while the backend is essentially a smart contract.**

#### Advantage of DApps
The main advantage of choosing a DApp over a traditional app is that traditional apps use a centralized architecture, where data is stored on servers controlled by a single entity. This centralized setup has a single point of failure, making it vulnerable to technical issues and malicious attacks. On the other hand, DApps offer similar quality of service as regular apps while benefiting from decentralization, including high uptime and resistance to censorship and corruption.

#### Types of DApps (Decentralised Application)

##### 1. DeFi (Decentralised Finance)





####  Who are the key Stakeholders of a Blockchain?
The different parts of a blockchain can be categorized into distinct layers, with each layer involving various stakeholders.
1. **Protocol Layer -->** At the protocol layer, we have Developers, Researchers, and academia.
   - Developers have the task of designing and improving blockchain protocols, designing the architecture of blockchain systems, and possessing expertise in data structures and cryptography.
   - Researchers play a crucial role in educating others about blockchain technology’s impact and exploring its wide-ranging applications in business and society.
  
3. **Networking Layer -->** The networking layer involves stakeholders like Miners, Validatos, Industry bodies, and Traders.
   - Miners contribute to public blockchains like Bitcoin by building consensus among untrusted nodes. They add transactions to the network by solving complex mathematical problems, requiring substantial computing power and electricity.
   - Industry bodies act as intermediaries between researchers, private entities, and public institutions, advocating for blockchain technology and establishing standards.
   - Traders are entities that rely on cryptocurrencies rather than traditional fiat currency, allowing others access to blockchain protocols through cryptocurrency tokens.

3. ** Application Layer -->** The application layer encompasses entrepreneurs, end-users, corporations, and venture capitalists or investors.
   - *Entrepreneurs* develop applications, products, or services that make use of blockchain protocols and networks. While profitability is a common goal for entrepreneurs, those in the blockchain space often have an anti-establishment approach and a lack of trust in traditional systems.
   - *End-users* are individuals who utilize blockchain applications, products, or services, and their preferences greatly influence the decision-making of other stakeholders.
   - *Corporations* aim to solve business problems and develop new strategies using blockchain technology, recognizing its value in areas like trust, transparency, data security, sustainability, and ethical sourcing.
   - *Venture capitalists or investors* provide capital to establish the blockchain infrastructure. They have opportunities to invest in blockchain protocols directly or support companies that provide essential services and infrastructure for the blockchain ecosystem


## Use Case of Blockchain
- In addition to its growing adoption in established industries such as Government and Public Sector, Manufacturing, Supply Chain, or Healthcare, blockchain technology has also given rise to several new industries and use cases. 
- These include cryptocurrency, NFT (Non-fungible token), DeFi (Decentralized Finance), DAO (Decentralized Autonomous Organization), and the Metaverse.



## What is a Private Blockchain?
- A private blockchain or permissioned blockchain is a type of blockchain or distributed ledger that operates within a closed network controlled by a single entity or a closed group.
- A private blockchain restricts access to only authorized participants. This means that new participants must go through a verification process to join the network, and the participation in the consensus process is limited to certain individuals.
- Private blockchains are typically used within the internal network of an enterprise. They are designed for the specific needs of the organization and rely on trust among the employees or partners within that organization. Unlike public blockchains that are decentralized, a private blockchain is centralized because it is controlled by a single entity or a closed group.










## Why do we Need Blockchain?
## Double Spending?
## Proof of Work?
## Difference Between Bitcoin , Cryptocurrency , Blockchain, Digital Signature & Cryptography etc.
## What is Ledger?
## What is Timestamp?
## Conenses Algorithm?
## What is Hash?
## SHA - 256 
## What is Majority in Bitcoin (1 CPU--> 1 Vote not 1 IP --> != 1 Vote)
## What is Nonce?
## What are Incentative in Bitcoin/Blockchain?
## What is Transaction Fee?
## How Inflation Is Controlled in Bitcoin?
## Merkle Tree?
## How Disk Spacew is Reclaimned in Bitcoin?
## Moore's Law?
## Double Spending?
## What is Simplified Payment Verification(SPV)
## 51% attack?
## Combining& Spiliting Value 
## What is Minning (Bitcoin/Cryptocurrency)?
## What is Public & Private Key  and their use (in increasing Privacy & Security)
## Binomial Random Walk
## Gambler's Ruin Problem
## Poisson Distribution


## Encrytion

#### 1. Introduction to Encryption 
- In cryptography, ***encryption*** is the process of encoding information. This process converts the original representation of the information, known as ***plaintext***, into an alternative form known as ***ciphertext***.
- Ideally, only authorized parties can decipher a ciphertext back to plaintext and access the original information. Encryption does not itself prevent interference but denies the intelligible content to a would-be interceptor.
- For technical reasons, an encryption scheme usually uses a ***pseudo-random encryption key*** generated by an algorithm.
- **It is possible to decrypt the message without possessing the key but, for a well-designed encryption scheme, considerable computational resources and skills are required**. An authorized recipient can easily decrypt the message with the key provided by the originator to recipients but not to unauthorized users.
- Modern encryption schemes use the concepts of ***public-key*** and ***symmetric-key***. Modern encryption techniques ensure security because *modern computers are inefficient at cracking the encryption.*


#### 2. History of Encrytion technology
- One of the most famous military encryption developments was the **Caesar Cipher**, which was a system in which a letter in normal text is shifted down a fixed number of positions down the alphabet to get the encoded letter. A message encoded with this type of encryption could be decoded with the fixed number on the Caesar Cipher
- Around 1790, **Thomas Jefferson theorized a cipher to encode and decode messages** in order to provide a more secure way of military correspondence. The cipher, known today as the Wheel Cipher or the Jefferson Disk, although never actually built, was theorized as a spool that could jumble an English message up to 36 characters. The message could be decrypted by plugging in the jumbled message to a receiver with an identical cipher
- A similar device to the Jefferson Disk, the **M-94**, was developed in 1917 independently by US Army Major Joseph Mauborne. This device was used in U.S. military communications until 1942.
- n World War II, the Axis powers used a more advanced version of the M-94 called the Enigma Machine. The Enigma Machine was more complex because unlike the Jefferson Wheel and the M-94, each day the jumble of letters switched to a completely new combination.


#### 3. Types of Encryption in Cryptography
###### 1. Symmetric Key
In symmetric-key schemes, the ***encryption and decryption keys are the same***. Communicating parties must have the same key in order to achieve secure communication. The German Enigma Machine utilized a new symmetric-key each day for encoding and decoding messages.
![image](https://github.com/Sourabh-Kumar04/Blockchain-concepts/assets/155216316/deaf489b-0b80-469e-88bd-0da7b0d02a8c)


###### 2. Asymmetric Key (Public Key)
- In public-key encryption schemes, the encryption key is published for anyone to use and encrypt messages. However, only the receiving party has access to the decryption key that enables messages to be read.
- Public-key encryption was first described in a secret document in 1973; beforehand, all encryption schemes were symmetric-key (also called private-key). Although published subsequently, the work of Diffie and Hellman was published in a journal with a large readership, and the value of the methodology was explicitly described. The method became known as the Diffie-Hellman key exchange.


###### 3. RSA (Rivert-Shamir_Adleman)
RSA (Rivest–Shamir–Adleman) is another notable public-key cryptosystem. Created in 1978, it is still used today for applications involving digital signatures. Using number theory, the RSA algorithm selects two prime numbers, which help generate both the encryption and decryption keys
![image](https://github.com/Sourabh-Kumar04/Blockchain-concepts/assets/155216316/fce76994-7b97-4e7a-9bc6-b20874715f35)


###### 4. Pretty Good Privacy (PGP)
A publicly available public-key encryption application called Pretty Good Privacy (PGP) was written in 1991 by Phil Zimmermann, and distributed free of charge with source code. PGP was purchased by Symantec in 2010 and is regularly updated.


 

#### 4. Data Erasure
- Conventional methods for permanently deleting data from a storage device involve overwriting the device's whole content with zeros, ones, or other patterns – a process which can take a significant amount of time, depending on the capacity and the type of storage medium.
- Cryptography offers a way of making the erasure almost instantaneous. This method is called ***crypto-shredding***.
- An example implementation of this method can be found on iOS devices, where the cryptographic key is kept in a dedicated 'effaceable storage'.Because the key is stored on the same device, this setup on its own does not offer full privacy or security protection if an unauthorized person gains physical access to the device.



#### 5. Limitation of Encryption
- The ***length of the encryption key is an indicator of the strength of the encryption method***.
- For example, the original encryption key, **DES (Data Encryption Standard), was 56 bits**, meaning it had 2^56 combination possibilities. With today's computing power, a 56-bit key is no longer secure, being vulnerable to brute force attacks.
- **Quantum computing** utilizes properties of quantum mechanics in order to process large amounts of data simultaneously. Quantum computing has been found to achieve computing speeds thousands of times faster than today's supercomputers.
- This computing power presents a challenge to today's encryption technology. For example, RSA encryption utilizes the multiplication of very large prime numbers to create a semiprime number for its public key.
- Decoding this key without its private key requires this semiprime number to be factored, which can take a very long time to do with modern computers. It would take a supercomputer anywhere between weeks to months to factor in this key.
- However, quantum computing can use quantum algorithms to factor this semiprime number in the same amount of time it takes for normal computers to generate it. This would make all data protected by current public-key encryption vulnerable to quantum computing attacks.
- Other encryption techniques like elliptic curve cryptography and symmetric key encryption are also vulnerable to quantum computing.
- While quantum computing could be a threat to encryption security in the future, quantum computing as it currently stands is still very limited.
- Quantum computing advancements will be able to be utilized in favor of encryption as well. The National Security Agency (NSA) is currently preparing post-quantum encryption standards for the future.
- Quantum encryption promises a level of security that will be able to counter the threat of quantum computing.
- Most applications of **encryption protect information only at rest or in transit, leaving sensitive data in clear text and potentially vulnerable to improper disclosure during processing, such as by a cloud service for example**.
- **Homomorphic encryption** and **secure multi-party computation** are emerging techniques to compute on encrypted data; these techniques are general and Turing complete but incur high computational and/or communication costs.


































## DES
## AES
## TwoFish
## ChaCha20-Poly1305
## Serpent




















