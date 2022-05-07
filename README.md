# Blockchain Notes with Interview Questions


# Basics of blockchain

 ## 1. What is Blockchain?
    Blockchain is distributed immutable ledger where:
 
     • Distributed means the blockchain is distributed all over the network.
     • Immutable means the data once stored it can't be changed or deleted. **Main benefit of blockchain**
     • Ledger means a place where transactions are stored in a block of a blockchain.
    
    
 ## 2. What is Ethereum?
    Ethereum is a decentralized, open-source blockchain with smart contract functionality.
     
 ## 3. What is EVM (Ethereum Virtual Machine) and why do we use it?
    EVM is used to create virtual machine inside computer or node.  We use it to secure the network. 
     
    Interested in learning more about EVM? visit the ethereum official website -> https://ethereum.org/en/developers/docs/evm/
    
    
 ## 4. What is Smart Contracts?
    Smart contract is nothing but a program that runs on blockchain.
     
    In easy language, smart contract is an agreement between two people. 
     
     
 ## 5. What is DAPP (Decentralized application)?
    DAPP is a decentralized application which runs on decentralized network. 
 
     • Some examples of decentralized examples are: d.tube which is decentralized version of youtube. presearch which is decentralized version of google. Same for twitter we have lbry.
     • Decentralized means that there is no central authority or person who can control it. 
     • To Make DAPP we need smart contract and frontend. 
     
     
 ## 6. Difference between centralized apps and decentralized apps.
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
    
    
   ## 13. What is View?
     It is used to map the key to values.
    
    • We use mapping to save the memory because if we use array it uses a lot of space.
    • Array uses sequential manner to store the data which uses more space whereas mapping do not store it in sequential manner.
    
    
   ## 13. What is Pure ?
     It is used to map the key to values.
    
    • We use mapping to save the memory because if we use array it uses a lot of space.
    • Array uses sequential manner to store the data which uses more space whereas mapping do not store it in sequential manner.
    
    
    
    
    
    
    
