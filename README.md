# Blockchain Notes with Interview Questions

# Contents
<details>
<summary> Basics of blockchain </summary>

- [Basics of blockchain](#basics-of-blockchain)
- [1. What is Blockchain?](#1-what-is-blockchain)
- [2. Types of blockchain?](#2-types-of-blockchain)
- [3. What is Unspent Transaction Outputs (UTXO)?](#3-what-is-unspent-transaction-outputs-utxo)
- [4. What is Ethereum?](#4-what-is-ethereum)
- [5. What is EVM (Ethereum Virtual Machine) and why do we use it?](#5-what-is-evm-ethereum-virtual-machine-and-why-do-we-use-it)
- [6. Where does EVM stores or save data?](#6-where-does-evm-stores-or-save-data)
- [7. What are Miners?](#7-what-are-miners)
- [8. What is public key cryptography?](#8-what-is-public-key-cryptography)
- [9. What is ECC ( Elliptic Curve Cryptography )?](#9-what-is-ecc--elliptic-curve-cryptography)
- [10. What is Hashing?](#10-what-is-hashing)
- [11. What is Cryptographic hash functions?](#11-what-is-cryptographic-hash-functions)
- [12. What is Smart Contracts?](#12-what-is-smart-contracts)
- [13. What is DAPP (Decentralized application)?](#13-what-is-dapp-decentralized-application)
- [14. Difference between centralized apps and decentralized apps.](#14-difference-between-centralized-apps-and-decentralized-apps)
- [15. What do we need to manage the integrity of transaction? ](#15-what-do-we-need-to-manage-the-integrity-of-transaction)
- [16. What are Tokens?](#16-what-are-tokens)
- [17. What is  ERC and ERC20 Token?](#17-what-is-erc-and-erc20-token)
</details>
<details>
<summary> Basics of Solidity </summary>

- [1. How do we write smart contracts?](#1-how-do-we-write-smart-contracts)
- [2. What is solidity and tell some benefits of solidity? ](#2-what-is-solidity-and-tell-some-benefits-of-solidity)
- [3. How solidity language compiles the program?](#3-how-solidity-language-compiles-the-program)
- [4. What is ABI?](#4-what-is-abi)
- [5. Difference between Main network and Test network.](#5-difference-between-main-network-and-test-network)
- [6. What is Global Variable and how do we use it in solidity?](#6-what-is-global-variable-and-how-do-we-use-it-in-solidity)
- [7. What is State Variable and how do we declare it in solidity?](#7-what-is-state-variable-and-how-do-we-declare-it-in-solidity)
- [8. What are Local Variable in solidity?](#8-what-are-local-variable-in-solidity)
- [9. What is Storage in solidity?](#9-what-is-storage-in-solidity)
- [10. What is Memory in solidity?](#10-what-is-memory-in-solidity)
- [11. What is Stack in solidity?](#11-what-is-stack-in-solidity)
- [12. What is Structure (Struct) in solidity?](#12-what-is-structure-struct-in-solidity)
- [13. What are Enumeration (Enums) and why do we use it in solidity?](#13-what-are-enumeration-enums-and-why-do-we-use-it-in-solidity)
- [14. What is Mapping and why do we use it instead of array in solidity?](#14-what-is-mapping-and-why-do-we-use-it-instead-of-array-in-solidity)
- [15. What is view Keyword in Solidity?](#15-what-is-view-keyword-in-solidity)
- [16. What is pure Keyword in Solidity ?](#16-what-is-pure-keyword-in-solidity)
- [17. What is Inheritance in Solidity ?](#17-what-is-inheritance-in-solidity)
- [18. What are Abstract contract ?](#18-what-are-abstract-contract)
- [19. What are polymorphism in Solidity ?](#19-what-are-polymorphism-in-solidity)
- [20. What are visibility specifier and explain them in Solidity ?](#20-what-are-visibility-specifier-and-explain-them-in-solidity)
- [21. What are Modifier ?](#21-what-are-modifier)
- [22. What are the benefits of using Events in smart contract ?](#22-what-are-the-benefits-of-using-events-in-smart-contract)
- [23. What is Fallback Function in Solidity ?](#23-what-is-fallback-function-in-solidity)
- [24. What does Self Destruct function do in Solidity ?](#24-what-does-self-destruct-function-do-in-solidity)
</details>
<details>
<summary> Bonus </summary>

- [1. What is an ICO ( Initial Public Offering )? ](#1-what-is-an-ico--initial-public-offering)
- [2. What is Token Trade Time?](#2-what-is-token-trade-time)
- [3. What is difference between Protocol/Coin and Tokens? ](#3-what-is-difference-between-protocolcoin-and-tokens)
- [4. All Data types and there default values](#4-all-data-types-and-there-default-values)
- [5. What is IPFS (Interplanetary File System)?](#5-what-is-ipfs-interplanetary-file-system)
- [6. Difference between Content-addressed and Location-addressed? ](#6-difference-between-content-addressed-and-location-addressed)
- [7. What is Pinning? ](#7-what-is-pinning)
- [8. What is Tokenization? ](#8-what-is-tokenization)
- [9. What is proof of Work and How Does it Work? ](#9-what-is-proof-of-work-and-how-does-it-work)
- [10. What is POS (proof of Stake) ? ](#10-what-is-pos-proof-of-stake)
- [11. Gas Saving Methods in Solidity](#11-gas-saving-methods-in-solidity)
- [12. Is it possible to Random Number in Solidity?](#12-is-it-possible-to-random-number-in-solidity)
</details>

[Back To Top ⬆](#blockchain-notes-with-interview-questions)

# Basics of blockchain

 ## 1. What is Blockchain?
    Blockchain is distributed immutable ledger where:
 
     • Distributed means the blockchain is distributed all over the network.
     • Immutable means the data once stored it can't be changed or deleted. **Main benefit of blockchain**
     • Ledger means a place where transactions are stored in a block of a blockchain.
     
   
 ## 2. Types of blockchain?
    There are mainly four types of blockchain
 
     1. Public Blockchains :-
       Public blockchains are open, decentralized networks of computers accessible to anyone wanting to request or validate a transaction (check for accuracy). Those 
       (miners) who validate transactions receive rewards.
       
       
     2. Private Blockchains :-
       Private blockchains are not open, they have access restrictions. People who want to join require permission from the system administrator. They are typically
       governed by one entity, meaning they’re centralized. For example, Hyperledger is a private, permissioned blockchain.
       
       
     3. Hybrid Blockchains :-
       Hybrid blockchain are a combination of public and private blockchains and contain centralized and decentralized features. For example, Energy Web Foundation,
       Dragonchain, and R3.
    
     4. Sidechains :-
       A sidechain is a blockchain running parallel to the main chain. It allows users to move digital assets between two different blockchains and improves
       scalability and efficiency. An example of a sidechain is the Liquid Network.
    
    
 ## 3. What is Unspent Transaction Outputs (UTXO)?
    The UTXO system is like a digital recreation of a cash economy. 
    
    Bitcoin, and many protocols based on it, store data about transactions and user balances in the form of unspent transaction outputs, which are a list of “unspent”'
    Bitcoin amounts that have been sent to a user, but have not yet been sent from him/her.
    
    
    
 ## 4. What is Ethereum?
    Ethereum is a decentralized, open-source blockchain with smart contract functionality. Ethereum is an open blockchain platform that lets anyone build and use
    decentralized applications that run on blockchain technology.
     
     
 ## 5. What is EVM (Ethereum Virtual Machine) and why do we use it?
    EVM is used to create virtual machine inside computer or node.  We use it to secure the network. 
     
    Interested in learning more about EVM? visit the ethereum official website -> https://ethereum.org/en/developers/docs/evm/
    
 
 ## 6. Where does EVM stores or save data?
    • Storage :-
      1. Holds State Variable.
      2. Persistant and expensive ( It cost Gas ).
      3. It is Like a computer HDD.
    
    • Stack :-
      1. Holds Local Variable defined inside functions if they are not reference types.
      2. It is free to use and dosen't cost gas.
      
    • Memory :-
      1. Holds Local Variable defined inside functions if they are reference types but declared with memory keyword.
      2. Holds function arguments.
      3. It is Like a computer RAM.
      4. It is also free to use and dosen't cost gas.
      5. Reference types are -> string, array, struct and mapping.
    
    
  ## 7. What are Miners?
    Miners are computers that execute operations defined by the blockchain protocols.
    
    
  ## 8. What is public key cryptography?
    Public-key cryptography, or asymmetric cryptography, is an encryption scheme that uses two mathematically related, but not identical, keys - a public key and a private key. Unlike symmetric key algorithms that rely on one key to both encrypt and decrypt, each key performs a unique function. The public key is used to encrypt and the private key is used to decrypt.
    
    Security Benefits of Digital Signatures :-
    Assuming the private key has remained secret and the individual it was issued to is the only person with access to it, digitally signing documents and emails offers the following benefits.

    Authentication – since the individual’s unique private key was used to apply the signature, recipients can be confident that the individual was the one to actually apply the signature
    
    Non-repudiation – since the individual is the only one with access to the private key used to apply the signature, he/she cannot later claim that it wasn’t him/her who applied the signature

    Integrity - when the signature is verified, it checks that the contents of the document or message match what was in there when the signature was applied. Even the slightest change to the original document would cause this check to fail.
    
 
## 9. What is ECC ( Elliptic Curve Cryptography )?
    Elliptic Curve Cryptography (ECC) is a modern public-key encryption technique famous for being smaller, faster, and more efficient than incumbents. Bitcoin, for example, uses ECC as its asymmetric cryptosystem because it is so lightweight. The mathematical entity that makes all of this possible is the elliptic curve, so read on to learn how these curves enable some of the most advanced cryptography in the world.
    
    ECC is used as the cryptographic key algorithm in Bitcoin because it potentially can save ~90% of the resources used by a similar RSA system. It seems that each year we see more systems moving from RSA to a more modern elliptic curve approach.


## 10. What is Hashing?
    In simple terms, hashing means taking an input string of any length and giving out an output of a fixed length. In the context of cryptocurrencies like bitcoin, the transactions are taken as input and run through a hashing algorithm (bitcoin uses SHA-256) which gives an output of a fixed length.
    
    In SHA256 ( Secure Hashing Algorithm ) no matter how big or small your input is, the output will always have a fixed 256-bits length. This becomes critical when you are dealing with a huge amount of data and transactions. So basically, instead of remembering the input data which could be huge, you can just remember the hash and keep track.

  
## 11. What is Cryptographic hash functions?
    A cryptographic hash function is a special class of hash functions that has various properties making it ideal for cryptography. There are certain properties that a cryptographic hash function needs to have in order to be considered secure.
    
    To know more about this go to -> https://blockgeeks.com/guides/what-is-hashing/
    
    
 ## 12. What is Smart Contracts?
    Smart contract is nothing but a program that runs on blockchain. A smart contract is a self-executing digital agreement that enables two or more parties to exchange money, property, shares, or anything of value in a transparent, conflict-free way while avoiding the need for a third party.
    
    According to Vitalik Buterin (Founder of ethereum) :-
    In a smart contract approach, an asset or currency is transferred into a program and the program runs this code and at some point it automatically validates a condition and it automatically determines whether the asset should go to one person or back to the other person, or whether it should be immediately refunded to the person who sent it or some combination thereof.
     
    In easy language, smart contract is an agreement between two people. 
     
     
 ## 13. What is DAPP (Decentralized application)?
    DAPP is a decentralized application which runs on decentralized network. 
 
     • Some examples of decentralized examples are: d.tube which is decentralized version of youtube. presearch which is decentralized version of google. Same for twitter we have lbry.
     • Decentralized means that there is no central authority or person who can control it. 
     • To Make DAPP we need smart contract and frontend. 
     
     
 ## 14. Difference between centralized apps and decentralized apps.
    DAPP is a decentralized application which runs on decentralized network. 
     
     • Centralized apps :-
     
       1. These types of apps can go down. 
       2. We can't trust them because we don't know how they use our data.
     
     • Decentralized apps :-
     
       1. These types of apps are never down because it is available everywhere.
       2. We can trust DAPPs because most of applications are open source.
       
    
  ## 15. What do we need to manage the integrity of transaction? 
    1. Secure and unique account address.
    2. Authorization of transaction by the sender through digital signing
    3. Verification of the content of the transaction is not modified.
    
    
     
  ## 16. What are Tokens?
    Tokens are a type of cryptocurrency that represents an asset or specific use and resides on their blockchain.
    
    
  ## 17. What is  ERC and ERC20 Token?
    ERC stands for ethereum requests for comments. An ERC is a form of proposal and its purpose is to define standards and practices.
    
    • ERC20 is a proposal that intends to standarize how a token contract should be defined, how we interact with such a token contract and how these contract interact with each other.
    • ERC20 is a standard interface used for financial application.
    • A full compatible ERC20 token must implement 6 functions and 2 events.
  
     
# Basics of Solidity
     
 ## 1. How do we write smart contracts?
    We write smart contract on top of ethereum with the help of solidity language.
     
     
 ## 2. What is solidity and tell some benefits of solidity? 
     • Solidity is a object oriented programming language used for writing smart contracts.
     • It is case sensitive.
     • It is an high level statically typed programming language.
     
     
 ## 3. How solidity language compiles the program?
     • It uses solc which is solidity compiler to compile a program.
     • when compiling, solc splits the file into 2 parts ABI(application binary interface) and byte code (stored in blockchain).
     
     
 ## 4. What is ABI?
    Application binary interface act as a bridge between application and smart contract.

    In easy language, ABI is used to communicate between frontend and smart contract.
    
    
 ## 5. Difference between Main network and Test network.
    DAPP is a decentralized application which runs on decentralized network. 
     
     • Test network :-
     
       1. Used to test the blockchain application (DAPPs)
       2. It has fake currency which we can use to test our network. 
       3. It is very similar to main network. 
       4. For example: Ropsten and Rinkeby is a test network.
       5. Network ID of testnet is 3,4 or 42.
     
     • Main Network :-
     
       1. Used for actual transactions in blockchain application (DAPPs)
       2. We can trust DAPPs because most of applications are open source.
       3. For example: Ethereum mainnet.
       4. Network ID of testnet is 1.
    
    
 ## 6. What is Global Variable and how do we use it in solidity?
    Global variable are special variable exists in the global namespace used to get information about the blockchain.
    
    Some global variabls are :-
    1. block.coinbase -> Address payable which returns current block miner's address.
    2. block.gaslimit -> Current block gas limit.
    3. block.timestamp -> Current block time in seconds.
    4. block.difficulty -> current block difficulty
    5. block.number -> Current block number.
    6. blockhash(blocknumber) -> Hash of the given block.
    
 
 ## 7. What is State Variable and how do we declare it in solidity?
    State variable are variable which are available in all over the code. 
    
    Some points to be known about state variables :-
    • State variable cost gas because it is stored in blockchain.
    • We declare state variable using public keyword. 
    • State variable are declared very carefully.
    
    
 ## 8. What are Local Variable in solidity?
    Local variable are variable which are available in a local scope or in functions.
    
    Some points to be known about local variables :-
    • Local variable dosen't cost gas because it is not stored in blockchain.
    • We can declare any number of local variable. 
    
 
    

 ## 9. What is Storage in solidity?    
    • Storage holds state variable.
    • It is persistent (store the data permanent)
    • Cost gas because it is persistent.


## 10. What is Memory in solidity?
    • Memory holds local variables defined inside functions if they are reference type like strings.
    • It is not persistent ( It holds the data for some point of time)
    • Do not cost gas because the data is store is not permanent.
    
    
  ## 11. What is Stack in solidity?
    • Stack holds local variables defined inside functions if they are not reference type like uint.
    • Do not cost gas because the data is store is not permanent.     
    
    
 ## 12. What is Structure (Struct) in solidity?
    It is user defined data type that is used to group items of different types into a single type.
    • To create  this data type we use Struct keyword. 
    
    
 ## 13. What are Enumeration (Enums) and why do we use it in solidity?
    It is user defined data type that is used to assign names to constant or integral values.
    
    • We use enum To Increase readablity
    • enums are only used when set values are small.
    
    
  ## 14. What is Mapping and why do we use it instead of array in solidity?
    It is used to map the key to values.
    
    • We use mapping to save the memory because if we use array it uses a lot of space.
    • Array uses sequential manner to store the data which uses more space whereas mapping do not store it in sequential manner.
    
    
   ## 15. What is view Keyword in Solidity?
     When we use view keword in our functions then it gives access to functions to read state variable. 
    
    • When using view, It can't modify/update state variable in functions.
    • It don't consume any gas if it's external and called from frontend to get the data.
    
    
   ## 16. What is pure Keyword in Solidity ?
     Pure Keyword is used when we are neither reading state variable nor modifying state variable.
    
    • It is used for only creating/reading local variables.
    • If we want to change our state variable inside function then we don't use view and pure keywords.
    
    
  ## 17. What is Inheritance in Solidity ?
    Inheritance in solidity is the procedure in which one contract inherits the methods and attributes of another contract.
    
    • We use is keyword to inherit an contract.
    

  ## 18. What are Abstract contract ?
    Abstract contract are contract that have at least one function without it's implementation
    
    • To make a contract abstract, We use abstract keyword.
    • Functions without implementation must contain virtual keyword.
    
    
  ## 19. What are polymorphism in Solidity ?
    Polymorphism is a way to create same function name with different forms or arguments.
    
    • We can create many same functions name but with different arguments or differnet data types.
    

  ## 20. What are visibility specifier and explain them in Solidity ?
    There are different type of visibility specifier like public, private, internal, external.
    
|                     | Public  | Private  | Internal | External |
| -------------       |:-------:|:-------: |:-------: |:-------: |
| Outside Contract -> | True    | False    | False    | True     |
| Within Contract  -> | True    | True     | True     | False    |
| Derieved Contract-> | True    | False    | True     | True     |
| Other Contract   -> | True    | Fasle    | False    | True     |
    
 
  ## 21. What are Modifier ?
    Function modifiers are used to change or restrict the behavior of a function in a smart contract. You can use a modifier to automatically check a condition prior to executing the function.
    
    For Example :-
    
    contract Owner {
    
       modifier onlyOwner {
         require(msg.sender == owner, "Only Owner can use this");
         _;
       }
    
       function name() public view onlyOwner returns(string){
          return "Steve Wazniak"
       }
    
    }
    
    
  ## 22. What are the benefits of using Events in smart contract ?
    Events are useful in many cases like :-
    1. User Gets notified wheneve a transaction has been done.
    2. Owner of that smart contract is also notified.
    3. It has low cost storage.
    4. Can be accessed from frontend to get the all Emitted data. We can filter the data if the event is indexed.
    
    
  ## 23. What is Fallback Function in Solidity ?
    Fallback function is a function which is called by solidity when no other existing function of the contract is being called.
    
    
  ## 24. What does Self Destruct function do in Solidity ?
    Self Destruct function is used to destroy the smart contract in the case of any emergency. The money is transferred back to the manager.
    
    
# Bonus
     
 ## 1. What is an ICO ( Initial Public Offering )? 
    Before understanding an ICO first let's understand what is an IPO ( Initial Public Offering ). So basically an IPO is an initial money which a company gets from public in the exchange of some shares. Just like this in ICO people will invest in cryptocurrencies in exchange of tokens and not shares.
    
    So an ICO is much cheaper then IPO, It requires Less documentations, less time consuming, You don't require third party to maintain your ICO.
    
    
 ## 2. What is Token Trade Time? 
    Token trade time is very important for an ICO because it restrict to trade the token between certian amount of time. It means that the invester can not sell their token till the time specified.
    
    
 ## 3. What is difference between Protocol/Coin and Tokens? 
    Protocols -> Protocals are set of rules. There are so many protocols like bitcoin, ethereum. Every protocal that is created has a coin associated with it.
     Rules Are :-
     1. How participants over the network will communicate.
     2. How authentication over the network will take place.
     3. How mining will be happen and how reward will be given to the miners.
    
    Tokens -> Tokens are type of a cryptocurrency that represents an asset or specific use and resides on their blockchain.
    
 ## 4. All Data types and there default values
    • Data Types :-
       1. boolean: false
       2. string: ""
       3. int: 0
       4. uint: 0
       5. fixed: 0.0 (presumably; this type is not fully supported)
       6. enum: the first element of the enum
       7. address: 0x0000000000000000000000000000000000000000 (or address(0))
     
     • function :-
       1. internal: empty function, returning initial values (if return is needed)
       2. external: function that throws when called
       
     • Reference Types :-
       1. mapping: empty mapping
       2. struct: a struct where all members are set to initial values

     • Array :-
      1. dynamically-sized: []
      2. fixed-sized: an array of the fixed size where all elements are set to initial values
      
      
 ## 5. What is IPFS (Interplanetary File System)? 
    IPFS (Interplanetary File System) is a Protocol designed to create a permanent and decentralized method of storing and sharing files.
    • IPFS aims to replace HTTP and build a better web.
    
    • Properties :-
      1. Peer-to-Peer, decentralized, distributed file system.
      2. Data-sharing-network, Files are addressed based on their hash and not on their name.
      3. Used for saving static content.
      4. reliable, fault tolerant, zero downtime, censorship resistant.
      5. IPFS files are chunked into blocks and saved on many IPFS peers around the internet.
    
    
 ## 6. Difference between Content-addressed and Location-addressed? 
    • Location addressed -> Whoever controls that location controls the content.
    
    • Content addressed -> There is no location and no one controls the file.
    
 ## 7. What is Pinning? 
    Pinning is the mechanism that allows you to tell IPFS to always keep a given object local.
    
 ## 8. What is Tokenization? 
    Tokenization refers to the process of converting tangible and non-physical assets into blockchain tokens. These tokens act as “shares”, and are similar to non-fungible tokens (NFTs).
    
    • Tokenization is gradually finding uses on the blockchain in conventional industries like real estate, equities, and artwork.
    
    
 ## 9. What is proof of Work and How Does it Work? 
    Proof of work (PoW) is a decentralized consensus mechanism that requires members of a network to expend effort solving an arbitrary mathematical puzzle to prevent anybody from gaming the system.
    
    • Proof of work is used widely in cryptocurrency mining, for validating transactions and mining new tokens.
    • Proof of work at scale requires huge amounts of energy, which only increases as more miners join the network.
    • Proof of Stake (POS) was one of several novel consensus mechanisms created as an alternative to proof of work.
    • Due to proof of work, Bitcoin and other cryptocurrency transactions can be processed peer-to-peer in a secure manner without the need for a trusted third party.
    
    
 ## 10. What is POS (proof of Stake) ? 
    PoS is a consensus mechanism that randomly assigns the node that will mine or validate block transactions according to how many coins that node holds. The more tokens held in a wallet, the more mining power is effectively granted to it. While PoS is far less resource-intensive, it has several other flaws including a greater chance of a 51% attack in smaller altcoins and incentives to hoard tokens and not use them.
    
 
 ## 11. Gas Saving Methods in Solidity
    • There are many optimization available to save gas some of them are :-
      
      1. **immutable keyword** -> We can use immutable keyword if the variable will not change after the initialization.
      2. **View/Pure Keywords** -> Using View keyword will not consume gas because it will tell the web3.js or ethers.js that this is read only function. Same way we can use pure function which will again don't consume gas.
      3. **external Keyword** -> If the function is going to be used by frontend only then we can use external keyword instead of public. The only difference will come is you can't call the external function inside the contract. 
      4. **uint** -> Using unsigned integers like uint8 or uint32 or uint256 will cost the same gas. But this is not the case using Unsigned Integers inside structs like if use (uint32 a, uint32 b, uint c) will cost less gas then the (uint a, uint b, uint c) and sequence matter as well because it wraps the strut if it's of same.

 
## 12. Is it possible to Random Number in Solidity?
    We Can't generate a random number in solidity. At least there is no safest method to generate the random number.
    
    • Random number generation via keccak256
      The best source of randomness we have in Solidity is the keccak256 hash function.

      We could do something like the following to generate a random number:
      **Generate a random number between 1 and 100:**
      
       (
       *Code Example*
          uint randNonce = 0;
          uint random = uint(keccak256(abi.encodePacked(now, msg.sender, randNonce))) % 100;
          randNonce++;
          uint random2 = uint(keccak256(abi.encodePacked(now, msg.sender, randNonce))) % 100;
       )

     What this would do is take the timestamp of now, the msg.sender, and an incrementing nonce (a number that is only ever used once, so we don't run the same hash function with the same input parameters twice).

    It would then "pack" the inputs and use keccak to convert them to a random hash. Next, it would convert that hash to a uint, and then use % 100 to take only the last 2 digits. This will give us a totally random number between 0 and 99.
    For More on random number in smart contract See This Thread -> https://ethereum.stackexchange.com/questions/191/how-can-i-securely-generate-a-random-number-in-my-smart-contract

    
    
