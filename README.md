# Torch-network

> We think the existing Defi project is not cool at all.The function is relatively single,the market value is too large, and there is no perfect deflation mechanism. Therefore, we designed the Torch network.

>> Team : 

>> Kevin Hunter  Data Analyst/Development Engineer →_→

>> Edmund Young  Development Engineer

>> Antony Bronte  Planning Manager

***

+ Torch-network is derived from DefiPie. We are a group of blockchain enthusiasts. We have seen that DefiPie has many advantages, but it also has imperfect economic models.
So we decided to improve this defect, and Torch-network was born. In addition to all the features of Defipie, it also adds other features that we think are cool :)

  - LUCKY SYSTEM
    + If a Defi project does not design an excellent deflation model, it will be imperfect. Therefore, we designed a cool Lucky system for Torch. This will very well encourage users to hold TOC for a long time instead of trading it frequently.
    + Torch Token (TOC) will consume 3% of the user's transfer amount for each transfer. For this reason, we designed the Lucky system, which is the most interesting feature we think! So far, it should be the most complete token deflation destruction mechanism in the world! The lucky system not only encourages more people to hold the torch for a long time, but also provides extra torch income for many lucky people.
    
  - NEW DEFI
    + Users will be able to borrow relatively little collateral on Torch, and even enjoy borrowing or even unsecured loans.
    
  - MORE PRIVATE
    + Using Torch and Ethereum eliminates the need for a third party to participate, thus simplifying investment and financial management and making it more private.
    
  - ENVIABLE HIGH YIELD
    + Liquidity providers can provide assets to existing pools and obtain annualized returns of up to 115%.
    
  - BIG STAKING
    + Users can mortgage PoS-based assets in the existing pool according to existing agreements to earn bets. Torch pool will add major PoS assets such as Cosmos, Tezos, Polkadot, Cardano, Kusama and Celo.
    
  - CUSTOM POOLS
    + PaaSPool is a service. Users can create custom pools with fixed interest rates for lending. Of course, creating a custom pool requires a certain amount of TOC.
 ***
 
 #### Timestamp 
 
 1. Build smart contracts（20200901）
 2. Start Ganache on（20200902）
```
truffle console --network cheshire //Ropsten
truffle(cheshire)> torchCore = KittyCore.at('0xd49F624B3C938d7C85288e1bA9061E6f26A60fd1')  
truffle(cheshire)> torchCore.getKitty(1)
```
