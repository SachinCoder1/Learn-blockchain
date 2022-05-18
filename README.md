# Blockchain Notes with Interview Questions


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
    
    
  ## 6. What are Miners?
    Miners are computers that execute operations defined by the blockchain protocols.
    
    
  ## 7. What is public key cryptography?
    Public-key cryptography, or asymmetric cryptography, is an encryption scheme that uses two mathematically related, but not identical, keys - a public key and a private key. Unlike symmetric key algorithms that rely on one key to both encrypt and decrypt, each key performs a unique function. The public key is used to encrypt and the private key is used to decrypt.
    
    Security Benefits of Digital Signatures :-
    Assuming the private key has remained secret and the individual it was issued to is the only person with access to it, digitally signing documents and emails offers the following benefits.

    Authentication – since the individual’s unique private key was used to apply the signature, recipients can be confident that the individual was the one to actually apply the signature
    
    Non-repudiation – since the individual is the only one with access to the private key used to apply the signature, he/she cannot later claim that it wasn’t him/her who applied the signature

    Integrity - when the signature is verified, it checks that the contents of the document or message match what was in there when the signature was applied. Even the slightest change to the original document would cause this check to fail.
    
 
## 8. What is ECC ( Elliptic Curve Cryptography )?
    Elliptic Curve Cryptography (ECC) is a modern public-key encryption technique famous for being smaller, faster, and more efficient than incumbents. Bitcoin, for example, uses ECC as its asymmetric cryptosystem because it is so lightweight. The mathematical entity that makes all of this possible is the elliptic curve, so read on to learn how these curves enable some of the most advanced cryptography in the world.
    
    ECC is used as the cryptographic key algorithm in Bitcoin because it potentially can save ~90% of the resources used by a similar RSA system. It seems that each year we see more systems moving from RSA to a more modern elliptic curve approach.


## 9. What is Hashing?
    In simple terms, hashing means taking an input string of any length and giving out an output of a fixed length. In the context of cryptocurrencies like bitcoin, the transactions are taken as input and run through a hashing algorithm (bitcoin uses SHA-256) which gives an output of a fixed length.
    
    In SHA256 ( Secure Hashing Algorithm ) no matter how big or small your input is, the output will always have a fixed 256-bits length. This becomes critical when you are dealing with a huge amount of data and transactions. So basically, instead of remembering the input data which could be huge, you can just remember the hash and keep track.

  
## 10. What is Cryptographic hash functions?
    A cryptographic hash function is a special class of hash functions that has various properties making it ideal for cryptography. There are certain properties that a cryptographic hash function needs to have in order to be considered secure.
    
    To know more about this go to -> https://blockgeeks.com/guides/what-is-hashing/
    
    
 ## 11. What is Smart Contracts?
    Smart contract is nothing but a program that runs on blockchain. A smart contract is a self-executing digital agreement that enables two or more parties to exchange money, property, shares, or anything of value in a transparent, conflict-free way while avoiding the need for a third party.
    
    According to Vitalik Buterin (Founder of ethereum) :-
    In a smart contract approach, an asset or currency is transferred into a program and the program runs this code and at some point it automatically validates a condition and it automatically determines whether the asset should go to one person or back to the other person, or whether it should be immediately refunded to the person who sent it or some combination thereof.
     
    In easy language, smart contract is an agreement between two people. 
     
     
 ## 12. What is DAPP (Decentralized application)?
    DAPP is a decentralized application which runs on decentralized network. 
 
     • Some examples of decentralized examples are: d.tube which is decentralized version of youtube. presearch which is decentralized version of google. Same for twitter we have lbry.
     • Decentralized means that there is no central authority or person who can control it. 
     • To Make DAPP we need smart contract and frontend. 
     
     
 ## 13. Difference between centralized apps and decentralized apps.
    DAPP is a decentralized application which runs on decentralized network. 
     
     • Centralized apps :-
     
       1. These types of apps can go down. 
       2. We can't trust them because we don't know how they use our data.
     
     • Decentralized apps :-
     
       1. These types of apps are never down because it is available everywhere.
       2. We can trust DAPPs because most of applications are open source.
     
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
    
 
 ## 6. What is State Variable and how do we declare it in solidity?
    State variable are variable which are available in all over the code. 
    
    Some points to be known about state variables :-
    • State variable cost gas because it is stored in blockchain.
    • We declare state variable using public keyword. 
    • State variable are declared very carefully.
    
    
 ## 7. What are Local Variable in solidity?
    Local variable are variable which are available in a local scope or in functions.
    
    Some points to be known about local variables :-
    • Local variable dosen't cost gas because it is not stored in blockchain.
    • We can declare any number of local variable. 
    

 ## 8. What is Storage in solidity?    
    • Storage holds state variable.
    • It is persistent (store the data permanent)
    • Cost gas because it is persistent.


 ## 9. What is Memory in solidity?
    • Memory holds local variables defined inside functions if they are reference type like strings.
    • It is not persistent ( It holds the data for some point of time)
    • Do not cost gas because the data is store is not permanent.
    
    
  ## 10. What is Stack in solidity?
    • Stack holds local variables defined inside functions if they are not reference type like uint.
    • Do not cost gas because the data is store is not permanent.     
    
    
 ## 11. What is Structure (Struct) in solidity?
    It is user defined data type that is used to group items of different types into a single type.
    
    • To create  this data type we use Struct keyword. 
    
    
 ## 12. What are Enumeration (Enums) and why do we use it in solidity?
    It is user defined data type that is used to assign names to constant or integral values.
    
    • We use enum To Increase readablity
    • enums are only used when set values are small.
    
    
  ## 13. What is Mapping and why do we use it instead of array in solidity?
    It is used to map the key to values.
    
    • We use mapping to save the memory because if we use array it uses a lot of space.
    • Array uses sequential manner to store the data which uses more space whereas mapping do not store it in sequential manner.
    
    
   ## 14. What is view Keyword in Solidity?
     When we use view keword in our functions then it gives access to functions to read state variable. 
    
    • When using view, It can't modify/update state variable in functions.
    
    
   ## 15. What is pure Keyword in Solidity ?
     Pure Keyword is used when we are neither reading state variable nor modifying state variable.
    
    • It is used for only creating/reading local variables.
    • If we want to change our state variable inside function then we don't use view and pure keywords.
    
    
  ## 16. What is Inheritance in Solidity ?
    Inheritance in solidity is the procedure in which one contract inherits the methods and attributes of another contract.
    
    • We use is keyword to inherit an contract.
    

  ## 17. What are Abstract contract ?
    Abstract contract are contract that have at least one function without it's implementation
    
    • To make a contract abstract, We use abstract keyword.
    • Functions without implementation must contain virtual keyword.
    
    
  ## 18. What are polymorphism in Solidity ?
    Polymorphism is a way to create same function name with different forms or arguments.
    
    • We can create many same functions name but with different arguments or differnet data types.
    

  ## 19. What are visibility specifier and explain them in Solidity ?
    There are different type of visibility specifier like public, private, internal, external.
    
|                     | Public  | Private  | Internal | External |
| -------------       |:-------:|:-------: |:-------: |:-------: |
| Outside Contract -> | True    | False    | False    | True     |
| Within Contract  -> | True    | True     | True     | False    |
| Derieved Contract-> | True    | False    | True     | True     |
| Other Contract   -> | True    | Fasle    | False    | True     |
    
 
  ## 20. What are Modifier ?
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
    
    
  ## 21. What are the benefits of using Events in smart contract ?
    Events are useful in many cases like :-
    1. User Gets notified wheneve a transaction has been done.
    2. Owner of that smart contract is also notified.
    3. It has low cost storage.
    
    
  ## 22. What is Fallback Function in Solidity ?
    Fallback function is a function which is called by solidity when no other existing function of the contract is being called.
    
    
  ## 22. What does Self Destruct function do in Solidity ?
    Self Destruct function is used to destroy the smart contract in the case of any emergency. The money is transferred back to the manager.
