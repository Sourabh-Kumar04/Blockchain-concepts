# Blockchain-2-Keywords

## Blockchain
- Blockchain is alinear ,chronological structure
- Blockchain consists of block of data(transaction) that are chained together.
- A blockchain is a transaction database shared by all
nodes participating in a network.
- Blockchain are the **Internet of Value**. Thisvalue can be crypto assets of Bitcoin & Monero or tokenised version of real world assets like airplane,carbon credits,real estate etc
- It enables the movement of values. Thus increase transparency and reduce the **need of intermediaries in financial use casses.**
-  ![image](https://github.com/Sourabh-Kumar04/Blockchain-2-Keywords/assets/155216316/33d31061-bdf6-4c78-b50e-a5036971f888)
- ![image](https://github.com/Sourabh-Kumar04/Blockchain-2-Keywords/assets/155216316/1f39aa36-1b52-4262-a625-e0eb334ac5b0)


## Why Blockchain??
- Decentralised
- Tokenisation
- Smart contracts
- Transpancy
- Immutability
- Crypto Assets
- Security

  
## Distributed Ledger Technologies(DLTs)
- 
- DLTs can havedifferent structures
  + Graph e.g IOTA
  + Mesh e.g Holochain
  + Tree e.g Corda
- DLTs use cases
  + Supply Chain MAnagement
  + Identity and Verification
  + Healthcare
  + Goverment and Public Services
- ** All Blockchain are DLTs ,but**
- ** All DLTs are not B;ockchains.**



## Blockchain Nodes 
- A node is a computer that runsthe blockchain's software to validate & store the history of the transaction.
- A full copy of a blockchain contains every transaction ever executed in the native coin(ETH) & tokens(BAT) created on the the blockchain.
- Transaction are bundledin **Blocks**
- Each block contains a records of some/all the recents transactions.
- Each block also contains a reference to the block that comes immediately before it.
- Blockchain nodes constantly exchange informationon new transaction & blocks.
- ![image](https://github.com/Sourabh-Kumar04/Blockchain-2-Keywords/assets/155216316/821b3319-e3c4-4b57-ad27-dfdab0b0cd31)


### Types of Blockchain Nodes
1. **Archival Full Nodes:-** They host the entire blockchain,validate blocks &maintain consensus. They are the most important.
2. **Pruned Full Node:-** A Pruned Full node first download the entire blockchain & then deletes blocks beginning with thw oldest block till it holds only the most recent tranastion upto its size limit set by the operator.
3. **Master Node:-** Users run masternodes to earn network rewards. Some amount of the native tokens have to "locked" by masternode operators.
4. **Light Nodes:-** A light node does not hold the full copy of the blockchain. It saves download time & storage space by only downloading block headers.
5. **Cold Nodes:-** They are used for signing tranastions offline and storing private keys awatsfrom the network.
6. **Lightning Nodes:-** They reduce the load on the network by enabling off-chain tranastions. These nodes enables faster & cheaper Tranaction.





## Mining 
- Mining is the process of completing to be the next  tofind the answer that "solves" the current block.
- In a *Proof of Work*blockchain like *Bitcoin*,each block also containsan answer to a diffcult-to-solve *Mathematical Puzzle*.
- New blocks cannot be submitted to the network without the correct answer.
- The mathematical problem ineach block is very difficult to solve,but once a valid solution is found,it iseasy to verify.
- Each block contains a *hash of the previous block.*
- This creates a chian of blocks from the first(genesis) block to the current block.
- It is extremely difficult to modifya block once it has been in the blockchain for some time because every block after it would alos have to be generated.



## Layers of a Blockchain Network
##### Layer 0: Infrastructure or Physical Layer
This consist of the hardwar, software,& network that enable the functioning of the
blockchain.

##### Layer 1: Logical Layer 
Thisconsist of the protocols, rules and standars that define the functioning of theblockchain.

##### Layer 2: Application Layer 
this consist of the protocols, applications, and service that build on the top of the basic building blocks provided by layer 1.

##### Layer 3: User Interfacew Layer 
This concist of thr interfaces, applications, and  services that enables users to interact with the blockchain and acces its underlying functionality.

 ![image](https://github.com/Sourabh-Kumar04/Blockchain-2-Keywords/assets/155216316/448ba4fb-bf87-4645-a0eb-e4d95d5f9825)





## Types of Blockchains

### Layer 0 Blockchain
- It enables developers to create custom blockchains.
- **Polkadot** enables the creation of soverign blockchains with their owntokens.
- These parachains plug into a single base platform called the **Relay Chain** which is responsible for shared security, consensus & cross-chain interoperability.
- Examples of layer 0  are **Cosmos and Horizon**
- Layer 0 blockchain are different fromblockchain Framework like **Multichain** & **Hyperledger Fabric**.
- Framework the open source software that enable Developers to create custom Blockchains.
- **Layer 0 Blockchain are *network* while Framework are *Software Program* .**


### Layer 1 Blockchains
- Layer 1 blockchain **validate & execute transactions** without the need for any external network. Examples: Bitcoin, Ethereun Mainnet.


### Layer 2 Blockchains
- Layer 2 blockchains are **Sidechains** built on the top of Layer-1 blockchain.
- The underline Layer-1 (e.g. Ethereum Mainnet) provides decentralisation & security, while the layer-2 (e.g. Polygon PoS) provide the scalability.

### Permission-less Blockchains
- Anyone can Participate on public/permission-less blockchains without restricitions. Examples: Bitcoin, Litecoin, Ethereum.

### Permissioned Blockchains
- Various controls can be set in a private/permissioned blockchain.
- Examples: Hybrid Finance Blockchain(HYFI) where permission such as connect, send, receive, issue, create, mine, activate, and admin can be set.

### Federated Blockchains
- In a Federated/consortium blockchain network, the validate processis controlled by a select set of nodes.

### EVm-compatible Chains
- Ethereum Virtual Machine(EVM) is the the environment in which all the Ethereum accounts and smart contracts live.
- Smart co0ntracts are theprograms that run automatically whensome pre-defined conditions are met.
- EVM compatibility is the ability to write& deploy smart contract code that are:
  1. Compatible with EVM,and
  2. Can be recognisedby Ethereum nodes.
- Examples of EVM compatible Blockchainare are **Avalanche, Binance Smart Chain, Fantom, and Polygon.



## Blockchain Consensus Mechanisms 
- Consensus algorithms are the **Hearth of the Blockchains.**
- Today there are over 75 consensus algorithms including:
1. **Proof-of-Work(PoW):**
   - This was the world's first consensus algorithm.
   - Miners "solve" mathematical puzzles by investing in electricity and computational power e.g. **Bitcoin**


2. **Proof of Stake(PoS):**
   - Holders "lock" a number of coins as a "stake" and are randomly assighned validation rights for a new block e.g. **Algorand**
     
     
3. **Hybrid PoW / Pos:**
   - This brings together the security of Proof of Stake and the governance & energy efficiency of Proof of Stake e.g. **Decred**
     

4. **Proof of work Time (PoWT):**
   - This features a variable blocktime that scales with mining power.
   - The blockchain speeds up with power increases. This mechansim scales the blockchain well and increases transaction speed with power.
     

5. **Proof of Meaningful Work (PoMW):**
   - The Energy investedby miner's is used for calculations that benefit public scientific reserach projects (e.g. medical reasearchfor cure,chemical research, andastrophysical simulations).
     

6. **Proofof Elapsed Time (PoET):**
  - Each node goes to sleep for a random "wait time" generatedby thenetwork. The node with the shortest wait time wake sup first and commits a new block e.g. **Hyperledger Sawtooth**
   

8. **Proof of Replication (PoRep)**
  - Storage miners prove 2 things:
     1. That they are using space to store replicas of data,
     2. That the data can easily br accesses.
  - They are rewardsin exchange for their storage space e.g. **Filecoin**.


9. **Delegated Proof of Stake (DPoS):**
    - Holders 'lock' a number of coins as a'stake' but outsource validation to 'delegates' selected  based on reputation and trustworthiness e.g. **Bitshares**.


10. **Proof of the Spacetime (PoSt):**
    - Randomly selected minors prove that theyhave been physically storing datafor a certain period of time e.g. **Filecoin**.


11. **Proof ofBurn (PoB):**
    - Miners reach out a consensus by snding coins to anj 'eaters' or 'burn' address.
    - This permanently eliminates coinsfrom circulation, reduces inflation, and validates transaction e.g. **Slimcoin**.


12. **Proof of Authority (PoA)**
    - Identified, known, and credible validates produce blocks in this system.
    - It ismeant for private & enterprise Blockchains.

![image](https://github.com/Sourabh-Kumar04/Blockchain-2-Keywords/assets/155216316/13c94e20-64a3-4f36-85eb-4750145488e4)




## **Blockchain Bridges**
- Ethereum Mainnet and Terra areindependent Blockchains. They have different rules and consensus mechanims. The native tokens of Ethereum Mainnet is ETH while that of Terra is LUNA.
- Now suppose that you have a bunch of LUNA on Terra, but want to use it on the Ethereum Mainnet. How do you do that?
- that's where a Blockchain Bridge comes into the picture. You could use the **Terra Bridge** to buy **Wrapped Luna (WLUNA) which ia an ERC-20 token native to the Ethereum mainnet.
- In simple terms,here's how atypical bridge works:
  1. It receives one type of crypto e.g. LUNA.
  2. It looks this LUNA as a deposit.
  3. It 'minit' an equal amount of another crypto e.g. Wrapped LUNA and releases it on another blockchain e.g. Ethereum Mainnet.


#### **Hacking Blockchain Bridgres**
- Because bridges hold a ton of crypto, they are juicy 
targets for hackers.
- And because writing the code for bridges is insanely 
complex, hackers are having a field day plundering 
them.
- When a bridge gets attacked, the hacker withdraws 
crypto from one side of the bridge, e.g. Wrapped LUNA, 
without depositing anything on the other side e.g. 
LUNA.
- 


      
 















  
