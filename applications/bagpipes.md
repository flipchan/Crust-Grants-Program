# Crust Grant Proposal

* **Project Name:** Bagpipes    
* **Team Name:** Rust Syndicate LLC
* **Payment Address:** Ethereum address 
* **Receivable Token:** CRU or USDT


### Overview

Bagpipes is a web3 drag and drop DApp builder, allowing anyone to design and build web3 flows and business logic that interacts with the blockchain, without needing to learn programming. So far, Bagpipes has integrated over 17 chains, allowing users to cherry pick the best features from each chain, allowing users to create powerful cross-chain applications. We now want to enable Decentralized interoperable storage with Crust via Bagpipes. 

**Project Links:**

[Bagpipes.io Landing page](https://bagpipes.io)

[Documentation](https://docs.bagpipes.io)

[**Bagpipes on Twitter**](http://x.com/bagpipesorg)

[**Bagpipes Github**](https://github.com/XcmSend)


### Ecosystem Fit 

Crust being the leader in decentralized storage and Bagpipes being the abstraction leader in the Dotsama ecosystem. We want to allow anyone to build decentralized cross chain applications with the full functionality of the Crust and Crust Shadow chain. Together we can supercharge IPFS storage in the web3 space.    

## Team


#### Ramsey:

Hi I’m Ramsey, i’ve been interested in building something that makes this ecosystem - of parachains, primitives, pallets and tools - more accessible to more people, especially the creative and entrepreneurial minds who have a desire to solve their own problems and/or solve other people’s problems, so they can be more effective at experimenting and realizing their ideas.

I have quite a wide ranging experience in the ecosystem. I discovered Substrate in December 2020. I spent 6 months getting my bearings, watched a bunch of Dan Forbes weekly substrate videos. Followed Josh Orndorff’s breadcrumbs, and nagged Dan Shields for answers. I am part of a small club who has built and launched a live parachain taking it through a crowdloan on kusama (kabocha parachain), i’ve built a pallet “supersig”, I then attended the Polkadot Blockchain Academy, which took me from a hacky mechanic to a blockchain engineer. . And now I want to leverage all of that experience and insight, channel it into Bagpipes, and make life easier and fun for those behind me. 



#### Filip:


Started working with information security in 2011 with a love for open source and an urge to explore, since then he has worked on offensive security for several fortune 30 companies, trained a red team responsible for finding bugs in amazon, facebook and several large entities. In the defensive line, Filip has worked on enterprise intrusion detection systems and antimalware projects. In 2014, he started to operate a public Bitcoin node service. Snowballing into Ethereum and Monero development. Filip was introduced to Rust at an OpenSource meetup a few years ago and is now combining his passion for Rust and web3. In 2021, he started as one of the first rust developers for early stages of Picasso chain, moved a year later to edgeware with the goal to perform a large substrate code update. After going through a painful path he wanted to make it easier for future developers and worked on the open source Uptest project, which was funded by the Polkadot treasury. 


### Team Code Repos
* https://github.com/xcmsend
* https://github.com/flipchan
* https://github.com/decentration
* https://github.com/uptest-sc/


### Contact
* **Contact Name:** Filip Kalebo   
* **Contact Email:** blockchain [at] firosolutions[.]com 
* **Website:** bagpipes.io

### Legal Structure 
* **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. 
* **Registered Legal Entity:** Rust Syndicate LLC 



## Project History:   

## Bagpipes Milestones and Integrations

### Funding and Recognition
0. First iteration funded by Web3 Foundation: [Web3 Foundation Grant Application](https://grants.web3.foundation/applications/xcmsend)
1. Received Polkadot Treasury Grant with 94% community support: [Polkadot Referenda](https://polkadot.subsquare.io/referenda/362)
2.  Funded by Moonbeam Foundation and OAK Network.   

### Key Achievements
2. Integrated with OAK for Kusama, OAK, Mangatax, and scheduled on-chain transfers
3. Presented and demo'd at Sub0 Blockchain Conference in Bangkok, Thailand
4. Integrated with Moonbeam
5. Showcased at Polkadot Day in Belgrade, Serbia
6. Demo'd at Web3 Summit in Berlin

### Chain Integrations
Integrated chains include:
- Mainnet: Polkadot, Polkadot Assethub, Kusama, HydraDX, Moonbeam, Moonriver, Turing, OAK
- Testnets: Rococo, Paseo, Paseo Pop Network, Paseo Assethub

# Milestones Overview
* **Total Estimated Duration:** 5-7 weeks  
* **Full-Time Equivalent (FTE):**  2    
* **Total Costs:** 29 500 USD

## Milestone 1: Shadow + Crust Chain XCM asset transfers and Base integration
 
* **Estimated Duration:** 2-3 weeks month
* **FTE:**  2
* **Costs:**  14 500  USD


| Number | Name | Description | Time |
|--------|------|-------------|------|
| 1 | Kusama Crust Shadow XCM transfer | Shadow chain XCM transfer through kusama | 15 |
| 2 | Crust Shadow chain integration in Bagpipes UI | Configuration and design for integrating Shadow Chain into Bagpipes | 15 |
| 3 | Shadow substrate transactions and Queries with ChainTx and ChainQuery node | Ability to draft transactions and queries for all pallets on Shadow chain | 10 |
| 4 | Polkadot Crust Mainnet XCM | Abstracted XCM asset transfers with Crust polkadot parachain | 20 |
| 5 | Crust chain integration in Bagpipes UI | Configuration and design for integrating Crust Chain into Bagpipes | 15 |
| 6 | Crust with ChainTx and ChainQuery node | Ability to draft transactions and queries for all pallets on Crust chain | 20 |
| 7 | Documentation | Public documentation | 20 |
| 8 | Testing | Unit and transaction tests | 20 |
| 9 | Docker | Public docker image | 10 |
| **Total:** | | | **145** |
Here's the content converted to markdown:

## Feature Information

#### Kusama XCM Asset Transfer Directions
- Shadow <> Kusama
- Shadow <> Moonriver 
- Shadow <> Turing
- Shadow <> Kaura 

Easy to use XCM transfer with a shareable link, ideal for new users and public wiki: [XCM Cross-Chain Solution](https://wiki.crust.network/docs/en/buildXCMPBasedCrossChainSolution#cases-now)

1. Crust Shadow chain integration in Bagpipes UI
2. Shadow substrate transactions and Queries with ChainTx and ChainQuery node 

#### Crust Polkadot Parachain XCM Asset Transfer Directions
- Crust <> Polkadot
- Crust <> Interlay
- Crust <> Moonbeam
- Crust <> Polkadot Assethub 
- Crust <> Hydration 

1. Crust chain integration in Bagpipes UI
2. Crust ChainTx + ChainQuery

#### ChainTx Node Capabilities
Ability to Draft any substrate pallet transaction on Crust using the ChainTx node:
[ChainTx Documentation](https://docs.bagpipes.io/docs/nodes/chainTx)

#### ChainQuery Capabilities
Query any storage item on Crust using ChainQuery:
[ChainQuery Documentation](https://docs.bagpipes.io/docs/nodes/chainQuery)

#### Documentation and Testing
1. Public documentation of all milestone features + template links
2. Typescript testing of published code 
3. Public docker image for easy local deployment


## Milestone 2 xStorage pallet integration + IPFS: 

* **Estimated Duration:** 2-3 weeks
* **FTE:**  2
* **Costs:** 12000 USD

| Number | Name | Description | Time |
|--------|------|-------------|------|
| 1 | xStorage pallet as custom action | Support for xStorage pallet with placeStorageOrder and PlaceStorageOrderThrough parachain features | 30 |
| 2 | Query Order statuses | Query cid through the market pallet | 20 |
| 3 | IPFS file upload support | Support for uploading files to ipfs with bagpipes | 10 |
| 4 | Pin IPFS through Crust | Ability to pin a ipfs file through Crust | 20 |
| 5 | Testing | Unit tests | 20 |
| 6 | Documentation | Public documentation for all milestone features | 10 |
| 7 | Docker | Public docker image | 10 |
| **Total:** | | | **120** |

### Feature Information

#### xStorage Pallet Custom Action
- Utilize xStorage pallet on Crust chain for storage orders across Parachains
- Ideal for new users with example on [Crust Wiki](https://wiki.crust.network/docs/en/buildParachainBasedCrossChainSolution#solution)

#### Order Status Query
- Easily query IPFS CID through market pallet

#### IPFS Functionality
- Upload files to IPFS using Bagpipes
- PIN IPFS CID through Crust

#### Development and Documentation
- Unit and transaction testing
- Public documentation of milestone features
- Public docker image

## Milestone 3: Bagpipes goes crusty, github ci releases   
* **Estimated Duration:** 2-3 weeks   
* **FTE:**  2    
* **Costs:** 3500 USD      



| Number | Name | Description | Time |
|--------|------|-------------|------|
| 1 | Bagpipes ipfs version | Github releases will be uploaded to ipfs using Crust! | 25 |
| 2 | Documentation | Public documentation | 10 |
| **Total:** | | | **35** |


### Delivery Details:

All code will be published here:   
https://github.com/xcmsend/ 

All docker images will be published here: 
https://hub.docker.com/r/xcmsend/xcmsend 

Documentation published here:     
https://docs.bagpipes.io/ 

Videos, How-to’s and public documentation and user examples with template links will be provided for all milestones. 



## Future Plans

The goal of Bagpipes is to be the no-code workflow builder for web3.
