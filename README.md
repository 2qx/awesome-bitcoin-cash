<br/>
<div align="center">
  <img width="250px" src="./awesome-bitcoin-cash.png">
</div>
<br/>
<div align="center">
A curated list of Bitcoin Cash projects &amp; resources <br>
<a href="https://awesome.re">
  <img src="https://awesome.re/badge.svg" alt="awesome" style="height:12px;border:10;">
</a>
<br />
<br />
Bitcoin Cash (BCH) is a project to scale bitcoin on-chain as an electronic peer-to-peer payment system for the world. 🚀

</div>
<br/>

📤 [a mobile friendly version](https://awesomebitcoin.cash) of this [project](https://github.com/2qx/awesome-bitcoin-cash) is formatted [from markdown](https://github.com/2qx/awesome-bitcoin-cash/blob/master/README.md) by github pages.

Pull requests are welcome, please see [the contribution guidelines](CONTRIBUTING.md).

# Contents
- [Contents](#contents)
- [Whitepaper](#whitepaper)
- [Projects Built on Bitcoin Cash](#projects-built-on-bitcoin-cash)
  - [Shipyard](#shipyard)
  - [Shipped](#shipped)
    - [Wallets](#wallets)
    - [Apps](#apps)
    - [Decentralized Marketplace](#decentralized-marketplace)
    - [Entertainment](#entertainment)
    - [Network](#network)
    - [Projects Leveraging SLP Tokens](#projects-leveraging-slp-tokens)
    - [Services & Bots](#services--bots)
    - [Utilities](#utilities)
    - [Web](#web)
  - [Launchpad](#launchpad)
  - [In the Boneyard](#in-the-boneyard)
  - [See Also](#see-also)
- [Merchants and Services Accepting Bitcoin Cash](#merchants-and-services-accepting-bitcoin-cash)
  - [A Short List](#a-short-list)
  - [Geographic lists](#geographic-lists)
  - [Projects dedicated to listing or enabling eCommerce.](#projects-dedicated-to-listing-or-enabling-ecommerce)
  - [Some Charities and Foundations](#some-charities-and-foundations)
- [eCommerce Merchant Resources](#ecommerce-merchant-resources)
  - [Bitcoin Cash Open-Source plugins](#bitcoin-cash-open-source-plugins)
  - [BCH-to-Fiat Payment Processors](#bch-to-fiat-payment-processors)
  - [Payment Processor Status](#payment-processor-status)
- [Documentation](#documentation)
  - [Roadmaps](#roadmaps)
  - [General](#general)
  - [Base Protocol](#base-protocol)
    - [Secondary protocols](#secondary-protocols)
  - [Bitcoin Script](#bitcoin-script)
- [Software](#software)
  - [Full Nodes](#full-nodes)
    - [Full Node Developer Resources](#full-node-developer-resources)
  - [Open-Source Teams Builing Upon  Bitcoin Cash](#open-source-teams-builing-upon-bitcoin-cash)
  - [SPV servers](#spv-servers)
  - [Libraries & SDKs](#libraries--sdks)
    - [Javascript](#javascript)
    - [Typescript](#typescript)
    - [Python](#python)
    - [Java](#java)
    - [PHP](#php)
    - [Language Agnostic](#language-agnostic)
  - [SLP Token Enabled Tooling](#slp-token-enabled-tooling)

# Whitepaper

"Bitcoin: A Peer-to-Peer Electronic Cash System" by Satoshi Nakamoto.

Bitcoin Cash is one chain of Satoshi Nakamoto's blockchain invention which was deliberately hard-forked on August 1st, 2017.  It shares the whitepaper, first block, and all bitcoin block history prior to the fork.  It attempts to implement the central idea outlined in that paper.

Whitepaper TL;DR: 
  1. A person controls unspent value at some address with a secret key.
  2. Value is transferred permissionlessly by signing a transaction with the secret key.
  3. The network is maintained and controlled by rewarding new value to the network operators. 
  4. Tracking a list of unspent value is manageable on a global scale. 

Below is a copy of the original nine page whitepaper:

- [Archived copy](https://web.archive.org/web/20100704213649if_/http://www.bitcoin.org:80/bitcoin.pdf) of the bitcoin whitepaper from bitcoin.org
- [bitcoin whitepaper](https://gateway.ipfs.io/ipfs/QmRA3NWM82ZGynMbYzAgYTSXCVM14Wx1RZ8fKP42G6gjgj) via ipfs
- [Websites hosting the bitcoin whitepaper](https://blockchair.com/bitcoin/whitepaper), with sha256 hashes calculated hourly.
- [Instructions and code](https://bitcoin.stackexchange.com/questions/35959/how-is-the-whitepaper-decoded-from-the-blockchain-tx-with-1000x-m-of-n-multisi) for building the original paper encoded on the blockchain on 2013-04-06.


# Projects Built on Bitcoin Cash

## Shipyard

These are up and coming projects in alpha stage (may not be suitable for large transactions):

- [be.cash](https://be.cash) [[whitepaper]](https://be.cash/becash.pdf) [[demo]](https://twitter.com/TobiasRuck/status/1261025132971274240) - point of sale system using stable tokens and nfc
- [causes.cash](https://causes.cash/) [[src]](https://gitlab.com/bchplease/causes.cash) - a site for creating your own fundraising campaign
- Electron-Cash 4.1.* (CashFusion Alpha) [[src]](https://github.com/Electron-Cash/Electron-Cash/tree/cashfusion) [[bin]](https://c3-soft.com/downloads/BitcoinCash/Electron-Cash/Fusion/)
- stamp [[src]](https://github.com/cashweb/stamp) - A Bitcoin Cash powered chat electron app on testnet
- [AnyHedge](https://anyhedge.com/) [[whitepaper]](https://gitlab.com/GeneralProtocols/anyhedge/whitepaper) [[lib]](https://gitlab.com/GeneralProtocols/anyhedge/library) - A Decentralized Hedge Solution for Arbitrary Assets on Bitcoin Cash
  
## Shipped

All of these apps are mostly stable and active.  Always check the notes of a particualar project before risking a large sum of value.  Links are checked on a weekly basis, but function is not checked.

### Wallets

Below are non-custodial open-source wallets that use features specific to Bitcoin Cash.

#### Desktop
- [Electron-Cash](https://electroncash.org) [[src]](https://github.com/Electron-Cash/Electron-Cash) - the awesome SPV wallet for Bitcoin Cash
- [crescent.cash](https://crescent.cash) [[src]](https://gitlab.com/pokkst/crescentcash) - a Bitcoin Cash wallet in java.
  
##### Electron-Cash Plugins
- [Flipstarter Plugin](https://gitlab.com/flipstarter/flipstarter-electron-cash) - plugin for crowdfunding
- [Mecenas Plugin](https://github.com/KarolTrzeszczkowski/Mecenas-recurring-payment-EC-plugin/releases) - recurring payments
- [Last Will](https://github.com/KarolTrzeszczkowski/Electron-Cash-Last-Will-Plugin) - dead man smart contract creation
- [More Comprehensive List](https://blog.imaginary.cash/index.php/electron-cash-plugins/) - hosted by im_uname

#### Mobile
- [Electron-Cash](https://electroncash.org) - Android [[src]](https://github.com/Electron-Cash/Electron-Cash/tree/master/android) and iOS [[src]](https://github.com/Electron-Cash/Electron-Cash/tree/master/ios) versions available with more limited functionality
- [crescent.cash](https://crescent.cash) [[src]](https://gitlab.com/pokkst/crescentcash) - Android wallet with SLP, BIP70 and sms features.
- [neutrino](https://neutrino.cash/) [[src]](https://github.com/gcash/android-neutrino) - Android wallet with advanced privacy features.
- [Badger Mobile](https://badger.bitcoin.com/) [[src]](https://github.com/Bitcoin-com/badger-mobile) - Mobile App wallet with SLP and CashID support for iOS [[src]](https://github.com/Bitcoin-com/badger-mobile/tree/develop/ios) and Android [[src]](https://github.com/Bitcoin-com/badger-mobile/tree/develop/android)

#### Cli
- [bchwallet](https://github.com/gcash/bchwallet) - a secure Bitcoin Cash wallet daemon written in Go (golang)
- [openbazaar wallet](https://github.com/OpenBazaar/spvwallet) - an SPV wallet in Go (golang) developed for openbazaar2
- [bitcore-walleet](https://github.com/bitpay/bitcore/tree/master/packages/bitcore-wallet) - A command line wallet used for BitPay wallets

#### Browser

- [blockparty](https://blockparty.sh/) [[src]](https://github.com/blockparty-sh/wallet/) [[docs]](https://github.com/blockparty-sh/wallet/blob/master/README.md) - A simple in-browser web wallet using bitbox.earth
- [mint](https://mint.bitcoin.com) [[src]](https://github.com/Bitcoin-com/mint) - Non-custodial web-based tool to manage your SLP tokens. 
- [nito](https://nito.cash) [[src]](https://gitlab.com/bchplease/nito.cash) - Web wallet designed for easily on-boarding new users

#### Paper/Offline Generator
- [Cash Address Generator](https://cashaddress.org/) - reputable javascript address generator suitable for offline use.
- [BCH Gifts](https://gifts.bitcoin.com/) - generate reclaimable preloaded paper private keys as gifts.
- [SLP wallet generator](https://wallet.bitchslap.tech/) [[src]](https://github.com/SLPVH/SLPpaperwallet)- offline generator for Simple Ledger addresses

### Apps
- [read.cash](https://read.cash) - a conventionally hosted long-format blogging platform, with BCH tipping for content.
- [flipstarter](https://flipstarter.cash/) [[Introduction]](https://read.cash/@flipstarter/introducing-flipstarter-695d4d50) - a crowd funding app using anyone can pay multisig transactions.
- [memo.cash](https://memo.cash) - short message social media site with decentralized SLP token exchange.
- [member.cash](https://member.cash) - longer format social media platform with voting, tipping, moderation and filtering.
 
### Decentralized Marketplace
- [OpenBazaar](https://openbazaar.org/download/) -  desktop (daemon w/ electron app) p2p marketplace using multisig transactions.
- [Havenapp](https://gethaven.app/) - mobile implementation of openbazaar.

### Entertainment
- [blockchain.poker](https://blockchain.poker) - Texas Hold'em using zero-conf for BCH deposits, BTC and BSV supported.
- [Satoshi dice](https://www.satoshidice.com/) -  a provably fair dice game.
- [Spin BCH](https://SpinBCH.com) - Spinning wheel based gambling using zero-conf 


### Network

- [doublespend.cash](https://doublespend.cash) - view Bitcoin Cash double spend attempts.
- [tx street](https://txstreet.com/beta) - transaction visualizer, updated with popular protocols.
- [privacy stats](https://stats.cash/#/) - recent list and totals of shuffles & fusions.
- [fork.lol](https://fork.lol) - Site to monitor network health in relation to BTC.
  
  
### Projects Leveraging SLP Tokens

- [Electron-Cash SLP Edition](https://simpleledger.cash/project/electron-cash-slp-edition/)
- [mist](https://mistcoin.org/) - a mineable SLP token using a proof-of-work covenant contract 
- [cryptophyl](https://cryptophyl.com/) - an SLP exchange
- [Toba Token](https://tobaelectricbike.com/toba-token/) - an e-bike customer reward token
- [Honest Coin](https://www.honestcoin.io/) - a fully regulated, 1:1 U.S. Dollar-backed stablecoin
- [SpiceToken](https://spicetoken.org/) - a meme token for social tipping


### Services & Bots

- [chaintip](https://www.chaintip.org) - An on-chain non-custodial tipping bot for reddit/twitter & github.
- [tipbitcoin.cash](https://tipbitcoin.cash) - Live tipping bot for video streamers.
- [bitcash](https://gitcash.io/start) - A custodial tipping bot for github. 
- [Chaintip Bounties](https://github.com/chaintip/bounties/blob/master/README.md#available-bounties) - BCH bot for github bounties.
- [BCH Pizza](https://www.bchpizza.org) - BCH shared bounty site for pizza shop adoption.
- [Satoshi Wall](https://satoshiwall.cash/) - a non-custodial payment wall tiered content site.


### Utilities

- [CashAccount](https://www.cashaccount.info/) - Online utility for cashaccounts (address handles).
- [Bitcoin.com Tools](https://tools.bitcoin.com/) - A mix of Bitcoin utilities.

### Web

- [Pay Button](https://paybutton.org/docs/) [[src]](https://github.com/PayButton/paybutton) - a simple snippet to accept Bitcoin Cash on your website.

## Launchpad

Awesome projects which appear to be dormant due to lack of use.

- [lazyfox](https://lazyfox.io) - a Bitcoin Cash powered question and answer / tasking platform, 🚧 under revision.
- [stack exchange](https://read.cash/@nyusternie/stackexchange-provides-shelter-for-homeless-bch-developers-87223764) - an unsuccessful initiative to create a Bitcoin Cash stack exchange.


## In the Boneyard

These ships are apparently in long term storage

- [SLPDEX](https://slpdex.cash/) [[src]](https://github.com/slpdex/slpdex) - Decentralized token exchange, errors on slp/list

## See Also

These are other projects dedicated to listing projects in the Bitcoin Cash ecosystem:

- [Canonical awesome-bitcoin-cash](https://github.com/dsmurrell/awesome-bitcoin-cash) - the original.
- [Bitcoin Cash Projects](https://www.bitcoin.com/bitcoin-cash-projects/) - maintained by bitcoin.com.
- [BCH Developments](https://keepbitcoinfree.org/bch-dev/) - list maintained by KeepBitcoinFree.
  

# Merchants and Services Accepting Bitcoin Cash


## A Short List

These vendors have accepted bitcoin for years and are committed (or sympathetic) toward the idea of electronic cash payments.

Although some of these may appear to only accept Bitcoin (BTC), they do, in fact, accept Bitcoin Cash also.

- [Namecheap](https://namecheap.com) - dns, ssl and some packaged hosting.
- [CheapAir](https://www.cheapair.com) - for your travel needs.
- [items sold by Newegg](https://kb.newegg.com/knowledge-base/using-bitcoin-on-newegg/) - good for a great headset.
- [Lanieri](https://www.lanieri.com) - makes a good suit.
- [partsoven](https://www.partsoven.com/) - for that 3rd dimension of building.
- [AdaFruit](https://www.adafruit.com/bitcoin/) - hardware dodads via bitpay 

## Geographic lists
- [member map](https://memberapp.github.io/#map) - permanent on-chain geographic tags utilizing extensions to the memo protocol.
- [Bitcoin.com map](https://map.bitcoin.com/) - website and mobile app for discovering merchants, formerly marco coino.
- [Greenpages map](https://greenpages.cash/pages/map.php) - merchant finder with advanced filtering.

## Projects dedicated to listing or enabling eCommerce.
- [The Accept Bitcoin Cash Initiative](https://acceptbitcoin.cash) - list of merchants and stores.
- [Bitpay Directory](https://bitpay.com/directory) - partial list of websites using bitpay as a payment processor (sometimes outdated).
- [Openbazaar Listings](https://openbazaar.com) - web preview for distributed multicoin marketplace.
- [Purse.io](https://purse.io/) - service to privately purchase goods on Amazon.com (US) at a discount.

## Some Charities and Foundations

Just some good charities for the world at large. 

- [Save the Children](https://files.savethechildren.org/cryptocurrency-donation/) - Powered by [The Giving Block](https://www.thegivingblock.com/)
- [Electronic Freedom Foundation](https://supporters.eff.org/donate/join-4)
- [Tails](https://tails.boum.org/donate/index.en.html)


# eCommerce Merchant Resources 

## Bitcoin Cash Open-Source plugins
- [CryptoWoo for WooCommerce](https://github.com/WeProgramIT/cryptowoo-bitcoin-cash-addon) - Bitcoin Cash integration for CryptoWoo

## BCH-to-Fiat Payment Processors
- [BitPay developer Integrations](https://bitpay.com/integrations/) [[api docs]]((https://bitpay.com/docs))
- [Coinpayments Tools](https://www.coinpayments.net/merchant-tools) [[plugins]](https://www.coinpayments.net/merchant-tools-plugins) - Integrations for coinpayments
- [GoCoin](https://gocoin.com/docs) - GoCoin integrations, libraries & API docs.
- [Coinbase](https://commerce.coinbase.com/integrate) - Merchant integrations for coinbase

## Payment Processor Status

- [status.coinbase.com](https://status.coinbase.com/#) - Dashboard with subscriptions endpoints and post-mortems
- [status.bitPay.com](https://status.bitpay.com/) - Current status with recent incidents 


# Documentation


## Roadmaps

- [Bitcoin Cash Roadmap](https://www.bitcoincash.org/roadmap.html) - Official Bitcoin ABC Roadmap.
- [Detailed Specs of Proposed Improvements](https://www.bitcoincash.org/specs/) - an ongoing list.
- [Coin Dance list](https://cash.coin.dance/development) - with broader developments and proposals in various states from many groups.


## General 
- [Full-Stack how-to](https://troutsblog.com/research/bitcoin-cash/how-to-bch-full-stack-developer) - Chris Troutner's introduction to developing on Bitcoin Cash
- [*Mastering Bitcoin Cash*](https://developer.bitcoin.com/mastering-bitcoin-cash/) - Fork of Andreas M. Antonopoulos' book under Creative Commons
- [developers.cash](https://developers.cash/) - many useful resources and [tools](https://developers.cash/tools/)
- [bitcoincash.org dev docs](https://www.bitcoincash.org/developers.html) - libraries for interacting with Bitcoin Cash
- [Bitcoin.com Developer Resources](https://developer.bitcoin.com/) - Tooling and documentation developed by bitcoin.com
- [tutorial.cash](https://www.tutorial.cash/) - video tutorials
- [Learn Bitcoin Cash](https://learnbitcoin.cash/) - Early general introduction to Bitcoin Cash.
  

## Base Protocol

- [Base Protocol Reference](https://reference.cash/) - maintained by Bitcoin Unlimited

### Secondary protocols

[Bitcoin Cash Standards](https://bitcoincashstandards.org) is a site dedicated to collecting, some of which are listed below:
  
- [Cashaddr](https://github.com/bitcoincashorg/bitcoincash.org/blob/master/spec/cashaddr.md) - Format for Bitcoin Cash addresses
- [Payment Requests Specification (BIP-0070)](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) - For dealing with invoice style payments at specific amounts.
- [Cash Accounts](https://gitlab.com/cash-accounts/specification/blob/master/SPECIFICATION.md) - attach a human readable name to Bitcoin Cash addresses
- [Memo Protocol](https://memo.cash/protocol) - for the on-chain tweet style social media app
- [Memo with Member extensions](https://github.com/memberapp/protocol) - for creating a reddit/hn style app
- [Simple Ledger Protocol (SLP)](https://simpleledger.cash/) [[specs]](https://slp.dev) - for handling ERC-20 style tokens
- [CashShuffle](https://cashshuffle.com/) [[spec]](https://github.com/cashshuffle/spec/blob/master/SPECIFICATION.md) - a privacy protocol for combining transactions with others, splitting to the lowest common amount.
- [CashFusion](https://cashfusion.org/) [[spec]](https://github.com/cashshuffle/spec/blob/master/CASHFUSION.md) - a privacy protocol for privately and trustlessly joining coin amounts.
- [CashID](https://gitlab.com/cashid/protocol-specification) - Specification using Bitcoin Cash for secure authentication.
- Avalanche [[snowglobe spec]](https://github.com/tyler-smith/snowglobe/blob/master/spec/snowglobe.md) [[🐉implementation (golang)]](https://github.com/gcash/bchd/tree/snowglobe/) - local-state reconciliation  
- [Price Oracle](https://gitlab.com/GeneralProtocols/priceoracle/specification) [[🐉implementation]](https://gitlab.com/GeneralProtocols/priceoracle/library) - Price oracle work in progress

## Bitcoin Script

- [meep](https://github.com/gcash/meep) - a command line Bitcoin Cash script debugger.
- [bitauth ide](https://ide.bitauth.com/) [[src]](https://github.com/bitauth/bitauth-ide) - an integrated development environment for bitcoin authentication.
- [spedn](https://spedn.readthedocs.io/en/latest/) [[src]](https://bitbucket.org/o-studio/spedn/src/develop/) - a high level smart contract language that compiles to Bitcoin Cash Script.
- [Cashscript](https://cashscript.org/docs/basics/about/) - a solidity-style language that compiles to Bitcoin Cash Script.
- [Cashscript alt-docs](https://developer.bitcoin.com/cashscript/docs/language) - documentation for Cashscript hosted at bitcoin.com.

# Software 

## Full Nodes

- [BitcoinABC](https://www.bitcoinabc.org/) [[mirror]](https://github.com/Bitcoin-ABC/bitcoin-abc) - a full node implementation of the Bitcoin Cash protocol. The dominant mining implementation, C/C++.
- [BitcoinUnlimited](https://www.bitcoinunlimited.info/) [[src]](https://github.com/BitcoinUnlimited/BitcoinUnlimited) - a full node implentation focused on supporting user needs, C/C++.
- [bchd](https://bchd.cash/) [[src]](https://github.com/gcash/bchd) - alternative implementation written in Go (golang)
- [Bitcoin Verde](https://bitcoinverde.org/) [[src]](https://github.com/softwareverde/bitcoin-verde)[[docs]](https://bitcoinverde.org/documentation/) - java implementation with the goal of being interoperable with mining nodes
- [BCHN](https://bitcoincashnode.org/) [[src]](https://gitlab.com/bitcoin-cash-node/bitcoin-cash-node) - a descendant of the Bitcoin Core and Bitcoin ABC software projects with independent development team. C/C++.
- [Flowee the Hub](https://flowee.org/) [[src]](https://gitlab.com/FloweeTheHub) - a node supporting a suite of software focused on payment integration. C++
- [Knuth](https://kth.cash/) [[src]](https://github.com/k-nuth/kth)- a high performance implementation of the Bitcoin protocol focused on applications needing extra capacity and resilience.

### Full Node Developer Resources

- [Future of Bitcoin Cash](https://thefutureofbitcoin.cash) [[channel]](https://www.youtube.com/channel/UCXmhk-YFo_c5luPzRqr7ViA) - Hosts - [developer meetings](https://www.thefutureofbitcoin.cash/development-meetings), a [newsletter](https://www.thefutureofbitcoin.cash/pulse-newsletter) and other planing resources.
- [Workgroups](https://github.com/bitcoincashorg/bitcoincash.org/tree/master/workgroups) - Entrypoint for discussion around particular roadmap sub-projects.
- [Bitcoin Cash Research](https://bitcoincashresearch.org/) - Site dedicated to technical research on Bitcoin Cash.
- [Difficulty Simulator](https://github.com/kyuupichan/difficulty) - Simulator for testing algorithms for difficulty adjustment with rational miners.
- [Difficulty Simulator](https://github.com/jtoomim/difficulty) - A more up to date difficulty adjustment with rational miners.


## Open-Source Teams Builing Upon  Bitcoin Cash

> If you want to go fast, go alone. If you want to go far, go together. 
> 
> -- An African Proverb.


There are various groups developing software stacks & apps for the broader ecosystem.  

- [Bitcoin.com](https://bitcoin.com) [[repos]](https://github.com/Bitcoin-com) - Prolific group developing webapps, mobile apps, and new tooling for deployed at bitcoin.com. (Typescript with some Javascript et al.)
- [FullStack Cash](https://fullstack.cash/) [[repos]](https://github.com/Permissionless-Software-Foundation) - Team building web/ipfs apps based on BitBox compatible stack. (Javascript)
- [gcash](https://bchd.cash) [[repos]](https://github.com/gcash/) - Team building apps, a wallet and tooling using an alternative full node directly. (Golang)
- [Simple Ledger](https://simpleledger.io/) [[repos]](https://github.com/simpleledger) - Group leading SLP token integration. (Typescript & Python)
- [General Protocols](https://GeneralProtocols.com) [[repos]](https://gitlab.com/GeneralProtocols) - Team researching and developing protocols for non-custodial and trustless networks using BitBox. (Typescript and Javascript)
- [Electron Cash](https://electroncash.org/) [[repos]](https://github.com/Electron-Cash/) - Team maintaining a desktop SPV wallet with plugins and mobile app (Python)
- [Flowee](https://flowee.org) [[repos]](https://gitlab.com/FloweeTheHub) - Team maintaining a non-mining full node and services to access the Bitcoin Cash network. (C++, NodeJs et al)



## SPV servers

- [Fulcrum](https://github.com/cculianu/Fulcrum) - A fast & nimble SPV Server for Bitcoin Cash
- [ElectronX](https://github.com/Electron-Cash/electrumx) [[docs]](https://electrumx.readthedocs.io/en/latest/) - A reimplementation of Electrum-Server for a future with bigger blocks.  ⚠️ [See changlog note v1.15.0](https://electrumx.readthedocs.io/en/latest/changelog.html) ⚠️
- [Electron Cash ElectronX](https://github.com/Electron-Cash/electrumx) [[docs]](https://electrumx.readthedocs.io/en/latest/) - Electron Cash maintained version of ElectrumX.  ⚠️ See note on main branch above ⚠️

## Libraries & SDKs

### Javascript
- [bchjs](https://bchjs.cash) [[docs]](https://bchjs.cash/bch-js/index.html) - JavaScript Libraries based on BITBOX.
- [libcash-js](https://developers.cash/resource/libcash-js/default) - javascript library using the flowee api.
- [bitcore-lib-cash](https://github.com/bitpay/bitcore/tree/master/packages/bitcore-lib-cash) - javaScript library, maintained by bitpay.
- [bchd grpc web-client](https://github.com/simpleledgerinc/grpc-bchrpc-web) - protobuf based javascript client for interacting with bchd full nodes.
- [electrum-cash](https://gitlab.com/GeneralProtocols/electrum-cash) [[docs]](https://gitlab.com/GeneralProtocols/electrum-cash) - JavaScript library that lets you connect with one or more Electrum servers.

### Typescript
- [Bitbox SDK](https://developer.bitcoin.com/bitbox/) [[docs]](https://developer.bitcoin.com/bitbox/docs/getting-started) - library for interacting with BCH via rest.bitcoin.com.
- [Badger SDK](https://developer.bitcoin.com/badger/docs/getting-started) - browser extension wallet supporting BCH and SLP on webpages.
- [libauth](https://libauth.org/) [[src]](https://github.com/bitauth/libauth) - a zero-dependency, typescript bitcoin library, including WASM crypto functions, BTC, but BCH friendly. (formerly bitcoin-ts)

### Python
- [bitcash](https://sporestack.github.io/bitcash/) [[src]](https://github.com/sporestack/bitcash) - python3 library.
- [bchd python bindings](https://github.com/gcash/bchd/tree/master/bchrpc/pb-py) - sample protobuf based python client for bchd.

### Java
- [bitcoincashj](https://github.com/pokkst/bitcoincashj) - Bitcoin Cash library for Java 

### PHP
- [cashp](https://github.com/Ekliptor/cashp) - Library for BCH and SLP tokens

### Language Agnostic

- [grpc-bchrpc-star](https://github.com/2qx/grpc-bchrpc-star) - Client libraries for bchd rpc generated from protocol buffers
- [BitBox OpenAPI 3 (Swagger) spec](https://github.com/Bitcoin-com/rest.bitcoin.com/tree/master/swaggerJSONFiles) - for rest.bitcoin.com see: [openapi-generator](https://github.com/OpenAPITools/openapi-generator)

## SLP Token Enabled Tooling

- [slpjs](https://github.com/simpleledger/slpjs) - library for interacting with SLP tokens, dependent on bitbox.
- [SLPDB](https://github.com/simpleledger/SLPDB) - simpleledger indexer 
- [goslp](https://github.com/simpleledgerinc/goslp) - SLP go libraries
- [SLP Indexer](https://github.com/Bitcoin-com/slp-indexer) - bitcoin.com indexer
- [SLP SDKs](https://simpleledger.cash/project/slp-sdk/) - for android and iOS.


