# Privacy scoring modelling > Web3privacy now analytical [platform](https://github.com/Msiusko/web3privacy/tree/main/Web3privacynowplatform)

_Currently we are surveying developers, security engineers and  researchers to find out bottle necks & potential room for growth within privacy features assessment by techies._ [raw data spreadsheet](https://docs.google.com/spreadsheets/d/1JWpAsGL10UTsVeuIVbouzUxRjaSPUAamxcbFljXuUWE/edit?usp=sharing)

## Core user group (techies definition):
- junior or general devs with under 1-year web3 coding experience
- poor security auditing skills
- general interest in privacy tech

## Why this group
- general public within the devs landscape is the most vulnerable audience compared to mature decs with connections & experience
- generalisation helps to make universal tooling & secure research from the niche approaches

## General scoring will consist of
- audit check up (manual)
- scoring features
- dev toolkit
- DYOR expanded track (subjective observations)

## Quick take from market assessment 
- devs lack the basics of security audits (while auditing companies or security engineers create piles of written that require lots of dev hours to read & more to understand)
- case studies could help to "visualize" the assessment journey
- DB of the malicious practices & critical bugs within the privacy landscape will come in handy for practical devs

**Hypothesis**: can the market create a standard of cross-project privacy features check-up increasing general privacy stack levelling? 

**Crucial scoring context**: time on research x potential amount of privacy anti-features detection. Meaning that scoring could be scalable if more people will use it under the economy, general business & without expert knowledge level.

# MVP for non-techies expanded to techies

**Sandbox: DeFi category that has been analyzed**

**How to use sandbox?**
1. Read scoring assumptions below.
2. Give us feedback via Pull request here.
3. You can always explore [scoring MVP](https://mirror.xyz/0x0f1F3DAf416B74DB3DE55Eb4D7513a80F4841073/90XEXa7AG_qc-VgYKs40i88xB1HF97gr1zqb-qvnif0) based on 38 DeFi project' assessment [here](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/DeFi%20category%20prototype.md)

**important note**: here "techies" covers "juniors" & general "developers" (masses) & not aplicable to "lead", "seniors" or even "mid"-devs (core devs).

# Scoring model 1.3: validity track

_Validity track covers GitHub, Product-readiness, Team, Docs, Audit._

**Note**: quick assessment helps to decrease privacy dark patterns from obscure language to test-net claiming it has a "state of art privacy".
![alt text](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Scoring%201.2%20validity%20track.png?raw=true)

# Scoring criteria

**How to score**

**Availability**: 
- available (+)
- missing (-)

**Open-source**
- Contributors-friendly (+): well-written docs, available external contributors, communal disscussions (PRs, forum/Discord, grants, external proposals)
- Centralized (-): poor documentation, no external contributors, no communal disscussions & impact

**Dependencies**
- The less - the better (+)
- Hundreds (-)

**Traction**
- above 50 nodes with diverse geo (+)
- below 50 nodes in more or less same geo (-)

# Sandbox

**Extended scoring 1.0**
| Project | GitHub | Product-readiness | Team | Docs | Audit | Contributors | Licenses | Support | Score |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| **Test project** | available & active GitHub / not | Live or 🚧 (exclusion criteria) | public team / not | available & not marketing docs / not | available & up to date third-party audit / not | external contributors outside of the team members | What licenses are in use | Some form of support available? (telegram, discord, forum) | from 0 to 100% |
| **score** | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 100% |

**Updates 1.2**

![alt text](https://github.com/web3privacy/explorer/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Scoring%20for%20techies%20approach.png?raw=true)

Privacy assessment should start with understanding privacy implication:
1. **Category** "transaction", "storage", "messaging" etc.
2. **Privacy features** "sender & receiver are un-linked within the transactional privacy" or "content of the message is End-to-end encrypted within the Messenger privacy".
3. **Complexity**: specific use-case centric privacy, or "multiple privacy": L1, L0 (sharing multiple privacy categories & features. Examples: Nym - network-level privacy (incl metadata protection); DarkFi - anon DAO, anon smart-contracts &  multiple other privacy-enhancing protocol features).   

![alt text](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Privacy%20complexity%20(use-case%20%26%20protocol%20grade).png?raw=true)

## **GitHub**
* Is it in stable release, 1.0 and not an alpha or untested code?
* Are there many PRs and Issues pending?
* Are there external contributors outside of the team members? [Waku example](https://github.com/waku-org/go-waku)
* What are licenses in use? [Privy Apache-2.0 license](https://github.com/privy-io/shamir-secret-sharing)

**example**: _Free & Open Source Software is the foundation that enables you to check whatever you want. The hoprd client is released under [GPLv3 license](https://github.com/hoprnet/hoprnet/blob/master/LICENSE) that allows you to do that (and also modify and re-distribute) Hoprn freely_

_How to score_

**Availability**
- Available (+),
- Missing (-)

**Activity**:
- Active (+): there’s an activity within the last 6 months.
- Not (-): The GitHub account is silent.

**Licenses**
- Free & OSS (+)
- Commercial (-) 

## **Docs**
- read the documentation: is it comprehensive?
- how well-written are privacy & security assumptions/guarantees?
- if aplicable: how well-written is encryption method? [example](https://developer.litprotocol.com/v3/sdk/access-control/encryption)
- is whitepaper marketing or dev-centric?

_How to score_

**Availability**:
- Available (+)
- Missing (-)

**Open-source**
- Technical (+): written for technical specialists with the clear explanation of the privacy assumptions execution
- Marketing (-): use marketing language, lacks tech specs, lots of token narrative

**Fullness** (# of pages)
- More than 5 pages (+)
- 2-3 pages (-): seems inactive or early stage

## **Team**
* Check if there are known contributors (reputation 101)
* Check commits at GitHub
* How many community contributors beyond core team?
* How many technical specialists in the team?
* How mature are core contributors (previous projects, GitHub commits)?

_How to score_

**General team**

- Public (+): the team is public, with active social media &/or GitHub accounts (note: digital avatars are ok if people are actively contributing to the project & actively communicate in socials: dcbuilder example)
- Anon (-): weird names, no/or obscure avatars, no socials or GitHub links

**Experience**
_How many technical specialists in the team?_
- 3+ technical people (+): from CTO to generic devs with active commits
- Just 1 CTO (-): one point of entry

_Do they have a track record? (university, projects, important commits)_
- Active track record (+): field experience (ZK, E2EE, messengers); privacy-market experience (credible projects, research teams, important implementations - eg. Ring signatures in Monero)
- No track record (-): can't attest quality of their previous projects, commits

**Open-source**
- 10+ community contributors beyond core team (+): many external contributors (total number & commits delivery)
- from 0 to 2-3 (-): lack of active & broad communal contributors

## **Third-party audit**
- Were privacy features attested?
- Were bugs fixed? [Zokyo x Railgun_ example, p.7](https://assets.railgun.org/docs/audits/2023-02-03%20Zokyo.pdf)

_How to score_

- Privacy features attested (+): company audited privacy assumptions & wrote down their state (if positive, no bugs & potential exploitations found); or privacy associated bugs were fixed by the team
- Privacy features ignored (-): company skipped privacy assumptions in their audit report

## **Infrastructure**
- Where are the nodes (check block explorer) [Nym mainnet explorer](https://explorer.nymtech.net)  
- Number of nodes (the larger the footprint the best privacy)

_How to score_

**Node footprint**
- 50+ of nodes (+): the larger the footprint the best privacy
- below 50 nodes (-): small footprint

**Geo**
- Diverse node representation (+): majority of the continents, less than 10% of the nodes in 1 country
- Poor node diversity (-): eg. 20% of the nodes - in Germany; or run by the same infra provider

## **Dependencies**
- check the dependencies, more dependencies means more risk of security vulnerabilities and more risk of network code that can leak your IP or personal data 
- read terms and conditions of every third party dependency, its licenses and what network calls are made by simply adding the library to the project even when not being used
- Audit libraries in use
- Do they have a third-party audit?
- What's the reputation behind the library team?
- What's the reputation behind security audit company?

_Tools_: [npmgraph](npmgraph.js.org), [depcheck](https://www.npmjs.com/package/depcheck)

_How to score_

**Dependencies footprint**
- TBD number of depencencies (+): the less the better the best privacy
- TBD number of depencencies (-): the more the worst for privacy

**example**: Rabby - 1150 dependencies, Metamask - 720, Brume - 50 [link](https://twitter.com/hazae41/status/1750478720140280259)

## **Data aggregation**
- no email or tel number for signup  
- does not implement KYC or AML  
- What user information is stored? (username, IP address, last connection, wallets associate, etc) 

## **Traction**
- Amount of transactions (Dune, DeFi Lama, block explorer etc) 
- Number of people using it

_How to score_

**Transactional privacy**
- TBD number of transactions (+): the larger the better is attestation of privacy features
- TBD number of transactions (-): the less the bigger are risks that privacy features weren't field tested

## **Governance**
- DAO structure (if applied)  
- How centralized is the protocol governance? [Railgun_ governance docs](https://docs.railgun.org/wiki/rail-token/protocol-governance)  

## **Extended scoring 1.2**
| Project | GitHub | Product-readiness | Team | Docs | Audit | Contributors | Licenses | Support | Dependencies | Data aggregation | Score |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| **Test project** | available & active GitHub / not | Live or 🚧 (exclusion criteria) | public team / not | available & dev-centric docs / not | available & up to date third-party audit / not | external contributors outside of the team members | What licenses are in use | Some form of support available? (telegram, discord, forum) | Third-party dependencies (the less - the better) | no email or tel number for signup | - |
| - | Is it in stable release, 1.0 and not an alpha or untested code? | Amount of transactions (Dune, DeFi Lama, block explorer etc) | Known team members | read the documentation: is it comprehensive? | Were bugs fixed? [Zokyo x Railgun_ example, p.7](https://assets.railgun.org/docs/audits/2023-02-03%20Zokyo.pdf) | Known contributors | - | Is there a technical support available & how accurate? | - | doesn't track & collect data (reflected in Privacy policy) | - |
| - | Are there many PRs and Issues pending? | Number of people using it | How mature are core contributors (previous projects, GitHub commits)? | how well-written are privacy & security assumptions/guarantees? | Audit libraries in use: Do they have a third-party audit? | External contributors impact | - | - | - | what user information is stored? (username, IP address, last connection, wallets associate, etc) | - |
| - | 10% | 10% | 10% | 10% | 10% | 10% | 10% | 10% | 10% | 10% | **100%** |

## **Extended scoring 1.3**
_5 Feb 24' update_
![alt text](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Scoring%20for%20techies%201.3.png?raw=true)

## Out of model (temporary - to be researched & talked through with the community)

**Benchmarking**
- Exact # of transactions (Dune, DeFi Lama, block explorer etc): _min to reflect liveliness_
- Exact # of people using it: _min to reflect liveliness_
- Exact # of dependencies (Rabby - 1150 dependencies, Metamask - 720, Brume - 50): _critical impact on potential privacy exploitations_

**Category specific profiling**
- Where are the nodes (check block explorer) [Nym mainnet explorer](https://explorer.nymtech.net)  
- Number of nodes (the larger the footprint the best privacy) 

**Governance**
- DAO structure (if applied)  
- How centralized is the protocol governance? [Railgun_ governance docs](https://docs.railgun.org/wiki/rail-token/protocol-governance)
- How centralized are product updates?

## **Practical examples by community**

**example 1**: [Railgun](https://www.railgun.org)

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Railgun_400x400.jpg" alt="Railgun" width="150"/>

1. Use @Railway_xyz to send a private transfer to a 0zk address through a Relayer. 
2. Examine the "receipt" of that transfer on etherscan or arbiscan.  You will not find: (1) sender, (2) receiver, (3) token or (4) amount anywhere in the transaction receipt.

[source](https://t.co/PqkUJWwmPD)
* This is a 0zk -> 0zk transaction (sending tokens from one #DeFi user to another. You'll note that the scan has a from address but this is simply a Relayer address that pays gas to process the on-chain computation).
* User communications with a Relayer are passed via through the @waku_org p2p gossip network, so Relayers can't know a particular message origin. In other words, even here #privacy was a big consideration throughout the tech stack not just on Etherscan.
* The To address is simply the RAILGUN smart contract on @0xPolygon in this case. So nothing is revealed about the recipient.
* The value that exchanged hands? #Private
* Try to decode the input data for the transaction? It's all #encrypted.
* So how much money exchanged hands here? Well, the short answer here is - it's #private. 
* Only the sender and recipient will know. There will be #zeroknowledge about it unless they choose to reveal the transaction information.

**example 2**: [HOPR](http://hoprnet.org)

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/HOPR_400x400.jpg" alt="HOPR" width="150"/>

The only user of HOPR is actually @RPC_h_- so I'd check if that is private. 

1. Use [DERP](http://DERP.hoprnet.org) in your normal wallet.
2. See how every request from your wallet gets disclosed via the website.
3. Then install RPCh.
4. Connect it to the DERP endpoint
5. And see that no request is visible on the page anymore, because the requests are sent via other IP addresses.

**example 3**: [dm3](https://dm3.network)

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/dm3_400x400.jpg" alt="dm3" width="150"/>

The criteria for a messenger or messaging protocol/service to proof "privacy by design":
- decentralized delivery network (no central instance controls the flow/storage/transmission of messages or identity information)
- decentralized registry for communication info (no entity controls the information how to encrypt and deliver messages)
- end-2-end encryption, ideally with PFS (every message is end-to-end encrypted, ideally with rotating keys (PFS, ...))
- Messages are not stored in the network (web3 storage like IPFS-based storage is critical as we never know if the encryption will be secure in the future, if not, this info is public)
- no traceable transmission (transmission of messages must be not traceable from outside, as this may reveal the connection)
- open-source of security-relevant parts (closed systems can't be trusted to not have backdoors)

**example 4**: [MASQ Browser](https://www.masqbrowser.com)

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/MASQ%20Browser_400x400.png" alt="MASQ" width="150"/>

1. Have you tried the MASQ Browser
2. Run a cli node on a VPServer
3. Read the docs on docs.masq.ai
4. Break TLS at first as there is a TLS connection from the MASQ Browser to the destination web server.
5. Analyze https://github.com/MASQ-Project/Node

**example 5**: [Penumbra](https://penumbra.zone)

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Penumbra_400x400.jpg" alt="Penumbra" width="150"/>

1. Run a node and see what data is synced from the network.
2. Check out the various RPCs like get block by height and see that the transaction data is encrypted (aside from what is intended to be public like fees).
3. Look in the local pcli database and see that only your transactions are present in decrypted form.

_Verifying the confidentiality/integrity of the encryption is its own whole topic that requires cryptographic expertise however._

_advanced level_:

1. the RPC endpoints use TLS and our RPCs speak in protobuf gRPC. So you'll need to decode the TLS and decode the gRPC protobuf messages.
2. You might have an easier time making custom builds of pd and cometbft to dump the data they receive.
3. Getting a basic understanding of how ABCI works with cometBFT will help you with this a lot. They have pretty good docs on the cometBFT website.
4. Here is the pd code that receives and processes ABCI messages from cometBFT. You could add debugging code here to dump out the contents of the ABCI messages: https://github.com/penumbra-zone/penumbra/blob/main/crates/core/app/src/app/mod.rs

**example 6**: [OMNIA](https://omniatech.io)

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/OMNIA_400x400.jpg" alt="OMNIA" width="150"/>

_off-chain privacy_ - mostly protecting metadata like the IP address of the one making the request. Algorithm to validate this: set up a dummy RPC node (i.e. using netcat or anything), register it in a load balancer in OMNIA, then make requests to OMNIA LB endpoint. The expected result is that you will not see your original IP in the data you receive on the dummy node, but rather random proxy addresses used to protect customer data

_private transactions_ also known as transaction sent through private mempool. Algorithm to validate this (for now only mainnet):

1. Send a transaction through a frontrunning protected endpoint.
2. Look at the transaction with a third-party explorer like Etherscan.
3. The expected result is that you'll see a label of "MEV Transaction"/"Private Transaction" which usually means the tx was sent through a private mempool, hidden from the bots etc that are eyeing the public mempool.

Example here [link](https://etherscan.io/tx/0xf12371347f409ea7e5e674bd435ee1ad269af5d82cb74d4998ad57b3ab673609)

**example 7**

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Firn.png" alt="OMNIA" width="150"/>

[Firn](http://firn.cash)

1. Look at an existing withdrawal on Etherscan. see if you can understand why the identity of the withdrawer is hidden. see if you can understand what information is visible (zkp, timing, withdrawal amount, etc.). here's an example: [etherscan](https://etherscan.io/tx/0x0b070e834c040e516503c9fe435b45fa03038b68f1157253c0eddaed9d682617)
2. Skim through the code of all of our contracts, especially Firn.sol. try to understand the rough architecture, blackboxing for now the actual zkp.
  3. [github](https://github.com/firnprotocol/contracts/blob/mainnet/Firn.sol)
  4. [etherscan](https://etherscan.io/address/0x4ce75eafd588f36de4b4b6e15f5e4e44b2e67aa0#code)
5. do basic Firn transactions or two. 
6. open the developer tools console. 
7. inspect all outbound traffic (network tab).

**example 8**

<img src="https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Waku_400x400.jpg" alt="OMNIA" width="150"/>

[Waku](http://waku.org)

1. Read the doc to understand at high level
2. Read the specs to understand exact behaviour and limitations
3. Check code
4. Run code and look at the network/libp2p logs:
   - What node it's connecting too
   - What messages are being sent.
  
**example 9**

[Leo wallet](https://www.leo.app)
  
**Ovro Ahmed | Leo wallet**: 

For a developer conducting a privacy-service self-audit, a simple algorithm could involve 
- checking Leo's code repository for any private or sensitive data handling functions
- inspecting API endpoints for encryption,
- and reviewing documentation for privacy features.

Utilizing tools can enhance the assessment: 
- static code analysis
- and privacy-focused libraries

_For static code analysis:
- the link you provided is a helpful resource: https://owasp.org/www-community/controls/Static_Code_Analysis
- specific tools like SonarQube, Checkmarx, and Fortify can aid in analyzing your code for vulnerabilities and suggesting improvements. 

As for privacy-focused libraries (widely used and prioritizing user privacy and data protection):
- options like Crypto++, libsodium, and OpenSSL for cryptography
- and PySyft and TensorFlow Privacy for privacy-preserving machine learning.

_tools_: 
- something like _netstat_ would be enough to see the connections made by the node. Or just using network tool in the browser.
- enabling libp2p logs would be a good start

# Backlog

## General
- Immutability  
- Decentralised throughout, including hosting 
- Permissionless & accessible to all  
- Open-source

## Privacy policy
- Privacy Policy content [Railway zero data aggregation PP](https://www.railway.xyz/privacy.html) vs massive data aggregation [Nocturne PP](https://nocturne.xyz/privacy-policy)
- Non-vague and non-intrusive privacy policy 

## Storage
- e2e encrypted LOCAL storage 
- Where is it stored? (centralized server, certain jurisdictions, on-chain, in browser/local cache) 

## Privacy execution
- p2p / no central server 
- Trustless - No ID required (this is where ZKs are useful)  

**example**: "with the unirep protocol we're building an explorer that shows all the things happening in the system. So a user could see their epoch keys and attestations and see how they're distinct in the system. One thing we might do is write what can and can't be determined about the different identifiers".

## Testing
- try to trace a transaction 
- Other tooling to verify e.g. block explorers  

## Tooling
- _network requests_: **Wireshark on the Docker container** to check what it interfaces &/or **Console** - check network requests by opening the console, the more requests it does to external servers, the more your IP address is sent around
- _transactional analytics_: Etherscan
- _dependencies_: [depcheck](https://www.npmjs.com/package/depcheck)
- _static code analysis_: SonarQube, Checkmarx, and Fortify can aid in analyzing your code for vulnerabilities and suggesting improvements.
- _privacy-focused libraries_ to enhance the assessment: cryptographic - Crypto++, libsodium, and OpenSSL; privacy-preserving machine learning: PySyft and TensorFlow.
- _node connections_: _netstat_ would be enough to see the connections made by the node
- _Android_: Feel free to test it at [Exodus Privacy](https://exodus-privacy.eu.org/en/), a friendly service to investigate Android apps. Check https://f-droid.org and verify the “no anti-features” tag (like dependency on third-party services). [Example](https://f-droid.org/en/packages/com.nighthawkapps.wallet.android/)

# Advanced part

from community
* use a packet inspection tool such as #Wireshark to check all packets coming into your machine and going out
* using something like https://charlesproxy.com to see all the traffic

# ETHSecurity community recommendations
_We asked Ethereum security chat members to share guides that devs could use to check privacy features of a given dApp or a protocol. Here are the first tips:_

[DeFiSafety](https://medium.com/defi-safety/introducing-our-0-9-process-79ba88f8bba4): "a clear list of what a dev should add to a protocol (over and above the software)"

**Officercia** recommendations
- [The ultimate security checklist](https://www.beirao.xyz/blog/Security-checklist)
- [Tips for Solidity Code Auditors](https://github.com/OffcierCia/tips-solidity-code-auditors)
- [Minimum viable security plans from Trail of Bits](https://docs.google.com/document/d/1-_0Wlwch_vtkPM4F-SdEXLjQYaYT7KoPlU2rjt7tkLQ/edit)
- [Opinionated security and code quality standard for Solidity smart contracts](www.github.com/Rari-Capital/solcurity)

[SCSVS](https://github.com/ComposableSecurity/SCSVS/): Smart Contract Security Verification Standard

[EthTrust](https://entethalliance.github.io/eta-registry/security-levels-spec.html): EEA EthTrust Security Levels Specification v-after-1

**Aditya, Nighthawkapps** recommendations
[OSS security audit tooling](https://techbeacon.com/app-dev-testing/13-tools-checking-security-risk-open-source-dependencies)
