# awesome-bitcoin-cash
A curated list of awesome bitcoin cash dev resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

📤 [A shareable link](https://2qx.github.io/awesome-bitcoin-cash/)

Bitcoin Cash is a cryptocurrency forked from the BTC chain aimed at scaling to be an electronic peer-to-peer system for the world. 

# Whitepaper

The bitcoin whitepaper by Satoshi Nakamoto:

- [Archived copy](http://web.archive.org/web/20100704213649if_/http://www.bitcoin.org:80/bitcoin.pdf) of the bitcoin whitepaper from bitcoin.org
- [bitcoin whitepaper via ips](https://gateway.ipfs.io/ipfs/QmRA3NWM82ZGynMbYzAgYTSXCVM14Wx1RZ8fKP42G6gjgj)
- [A list of websites hosting the bitcoin whitepaper](https://blockchair.com/bitcoin/whitepaper), with sha256 hashes calculated hourly
- [Instructions and code](https://bitcoin.stackexchange.com/questions/35959/how-is-the-whitepaper-decoded-from-the-blockchain-tx-with-1000x-m-of-n-multisi) for decoding a version of the original paper hosted on the bitcoin blockchain
 

# Roadmaps

- [Bitcoin Cash Roadmap](https://www.bitcoincash.org/roadmap.html)  
- [Detailed Specs of Proposed Improvements](https://www.bitcoincash.org/specs/) - An ongoing list of detailed specifications
- [Coin Dance List](https://cash.coin.dance/development) - A broader list of developments and proposals in various states from many groups
- [Canonical awesome-bitcoin-cash](https://github.com/dsmurrell/awesome-bitcoin-cash) - An awesome early Bitcoin Cash list.

# Developer resources:

- [Chris Troutner's introduction](https://troutsblog.com/research/bitcoin-cash/how-to-bch-full-stack-developer) to developing on Bitcoin Cash
- [developers.cash](https://developers.cash/) Many useful resources
- [bitcoincash.org dev docs](https://www.bitcoincash.org/developers.html) Libraries for interacting with Bitcoin Cash

## Base Protocol

- [Base Protocol Reference](https://reference.cash/) - maintained by Bitcoin Unlimited

### Secondary protocols:

- [SLP Protocol](https://github.com/simpleledger/slp-specifications/blob/master/slp-token-type-1.md) for handling fungible or redeemable tokens
- [Memo Protocol](https://memo.cash/protocol) - For the on-chain tweet style social media app
- [Memo with Member extensions](https://github.com/memberapp/protocol) - For creating a reddit/hn style app
- [CashShuffle](https://cashshuffle.com/)[[spec]](https://github.com/cashshuffle/spec/blob/master/SPECIFICATION.md) A privacy protocol for combining transactions with others, splitting to the lowest common amount.
- [CashFusion](https://cashfusion.org/)[[spec]](https://github.com/cashshuffle/spec/blob/master/CASHFUSION.md) A privacy protocol for privately and trustlessly joining coin amounts.

## Full Nodes

- [BitcoinABC](https://www.bitcoinabc.org/) [[mirror]](https://github.com/Bitcoin-ABC/bitcoin-abc) Bitcoin ABC is a full node implementation of the Bitcoin Cash protocol. The dominant mining implementation, C/C++.
- [BitcoinUnlimited](https://www.bitcoinunlimited.info/) [[src]](https://github.com/BitcoinUnlimited/BitcoinUnlimited) A full node implentation focused on supporting user needs, C/C++.
- [BCHN](https://bitcoincashnode.org/) [[src]](https://gitlab.com/bitcoin-cash-node/bitcoin-cash-node) A descendant of the Bitcoin Core and Bitcoin ABC software projects with independant development team. C/C++.
- [bchd](https://bchd.cash/) [[src]](https://github.com/gcash/bchd) An alternative full node bitcoin cash implementation written in Go (golang)
- [Bitcoin Verde](https://bitcoinverde.org/) [[src]](https://github.com/softwareverde/bitcoin-verde)[[docs]](https://bitcoinverde.org/documentation/) A Java implementation with the goal of being interoperable with mining nodes
- [flowee](https://flowee.org/) [[src]](https://gitlab.com/FloweeTheHub) A full node supporting a suite of software focued on payment integration.

## Open Source Wallets

### Desktop
- [Electron-Cash](https://electroncash.org) [[src]](https://github.com/Electron-Cash/Electron-Cash) - the awesome SPV wallet for Bitcoin Cash

#### Electron-Cash Plugins
- [Flipstarter Plugin](https://gitlab.com/flipstarter/flipstarter-electron-cash) - plugin for crowdfunding
- [Mecenas Plugin](https://github.com/KarolTrzeszczkowski/Mecenas-recurring-payment-EC-plugin/releases) - recurring payments
- [Last Will](https://github.com/KarolTrzeszczkowski/Electron-Cash-Last-Will-Plugin) - dead man smart contract creation


### Mobile

- [Electron-Cash](https://electroncash.org) - Android and iOS version available with limited functionality 
- [neutrino](https://github.com/gcash/android-neutrino) - An android wallet with advanced privacy features.

### Cli
- [bchwallet](https://github.com/gcash/bchwallet) - A secure bitcoin cash wallet daemon written in Go (golang)
- [openbazaar wallet](https://github.com/OpenBazaar/spvwallet) - An SPV wallet in Go (golang) used by openbazaar2

### Offline Address Generator

- [Cash Address Generator](https://cashaddress.org/) - Reputible javascript random address generator suitable for offline use.

## General Libraries & Software Development Kits:

### Javascript
- [Bitcoin Cash JavaScript Library based on BITBOX
](https://fullstack.cash)[[docs]](https://bchjs.cash/bch-js/index.html) - Chris Troutner Bitcoin Cash stack
- [libcash-js](https://developers.cash/resource/libcash-js/default) - Javascript library using the flowee api
- [bchd grpc web-client](https://github.com/simpleledgerinc/grpc-bchrpc-web) protobuf based javascript client for interacting with bchd full nodes

### Typescript
- [Bitbox SDK](https://developer.bitcoin.com/bitbox/)[[docs]](https://developer.bitcoin.com/bitbox/docs/getting-started) for interacting with BCH via bitcoin.com
- [Badger SDK](https://developer.bitcoin.com/badger/docs/getting-started) - Browser extension wallet supporting BCH and SLP
- [bitcoin-ts](https://github.com/bitauth/bitcoin-ts) - A zero-dependency, typescript bitcoin library, including WASM crypto functions

### Python
- [bitcash](https://sporestack.github.io/bitcash/) [[src]](https://github.com/sporestack/bitcash) - A python3 library for bitcoin cash.
- [bchd python bindings](https://github.com/gcash/bchd/tree/master/bchrpc/pb-py) protobuf based pyhton client for bchd

## SLP Tokens
- [Electron-Cash SLP Edition](https://simpleledger.cash/project/electron-cash-slp-edition/) 
- [slpjs](https://github.com/simpleledger/slpjs) - Library for interacting with SLP tokens, dependant on bitbox.
- [SLP SDKs](https://simpleledger.cash/project/slp-sdk/) - Link to sdks for android and iOS

## Scripting

- [meep](https://github.com/gcash/meep) - Meep is a command line Bitcoin Cash script debugger
- [bitauth ide](https://ide.bitauth.com/) - an integrated development environment for bitcoin authentication
- [Cashscript](https://developer.bitcoin.com/cashscript/docs/language) A solidity like language for bitcoin cash
 
# Adoption

## Apps

### Social
- [read.cash](https://read.cash) - A long-format blogging platform allowing BCH tipping for content
- [flipstarter](https://flipstarter.cash/) [Introduction](https://read.cash/@flipstarter/introducing-flipstarter-695d4d50) A crowd funding app using Anyone can pay multisig transactions 
- [memo.cash](https://memo.cash) - Short message social media site with decentralized SLP token exchange
- [member.cash](https://member.cash) - Longer format social media platform with voting, tipping, moderation and filtering

### Marketplace
- [OpenBazaar](https://openbazaar.org/download/) - Desktop p2p marketplace using multisig transactions
- [Havenapp](https://gethaven.app/) - Mobile implementation of openbazaar 

### Entertainment
- [blockchain.poker](https://blockchain.poker) - Texas Hold'em using zero-conf for BCH deposits
- [Satoshi dice](https://www.satoshidice.com/) -  Provably fair dice game

### Bots

- [chaintip](https://www.chaintip.org) - An on-chain non-custodial reddit tipping bot.

## Boneyard

These are awesome projects which appear to be dormant due to lack of users, and may come back one day.

- [lazyfox](lazyfox.io) - A Bitcoin Cash Powered Question and Answer / Tasking Platform 
- [stack exchange](https://read.cash/@nyusternie/stackexchange-provides-shelter-for-homeless-bch-developers-87223764) - an unsuccessful initiative to create a bitcoin cash stack exchange
- [Satoshi Wall](https://satoshiwall.cash/) - A non-custodial payment wall service
- [Learn Bitcoin dot Cash](https://learnbitcoin.cash/) - Letsencrypt expired Monday, April 27, 2020 at 2:24:48 PM
- [Chaintip Bounties](https://github.com/chaintip/bounties/blob/master/README.md#available-bounties) - Bounties for github commits

## eCommerce Plugins

- [WooCommerce plugin](https://github.com/sanchaz/P2P-Electronic-Cash-Payments-for-WooCommerce) - accepting BCH and BSV

## Merchant Listings

### Awesome merchants

There are many places that accept Bitcoin Cash.

#### The Short List

This list is meant to highlight the really awesome ones and not replicate the listing services below. They have accepted Bitcoin Cash for years and are committed or sympathetic toward the idea of electronic cash payments.

- [Lanieri](https://www.lanieri.com) - makes a good suit, not that you would ever need one, for work.
- [Cheap plane tickets](https://www.cheapair.com) - for your travel needs. 
- [Items sold by newegg](https://newegg.com) - good for a great headset.

### Merchants near you or where you're headed
- [Member map](https://memberapp.github.io/#map) - Permanent on-chain geographic tags utilizing extensions to the memo protocol.
- [Bitcoin.com map](https://map.bitcoin.com/) - Website and mobile app for discovering merchants, formerly marcocoino
- [Greenpages map](https://greenpages.cash/pages/map.php) - Merchant finder with advanced filtering

### Listing searches across the broader internet
- [The Accept Bitcoin Cash Initiative](https://acceptbitcoin.cash) - Browsable list of merchants and stores
- [Bitpay Directory](https://bitpay.com/directory) - Partial and outdateed list of websites using bitpay as a payment processor.
 using ipfs.
- [Openbazaar Listings](https://openbazaar.com) - Distributed multicoin marketplace with integrated wallet
- [Purse.io](https://purse.io/) - Service to privately purchace goods on Amazon.com (US) at a discount

## Awesome Charities
- [Save the Children](https://files.savethechildren.org/cryptocurrency-donation/)
- [Electronic Freedom Foundation](https://supporters.eff.org/donate/join-4)
- [Tails](https://tails.boum.org/donate/index.en.html)
