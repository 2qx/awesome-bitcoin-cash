# awesome-bitcoin-cash
A developer oriented list of awesome bitcoin cash resources 🕶️

Bitcoin Cash is a cryptocurrency forked from the BTC chain aimed at scaling to be an electronic peer-to-peer system for the world. 

# Whitepaper

The bitcoin whitepaper by Satoshi Nakamoto:

- [Archived copy of te bitcoin whitepaper from bitcoin.org](http://web.archive.org/web/20100704213649if_/http://www.bitcoin.org:80/bitcoin.pdf)
- [bitcoin whitepaper via ips](https://gateway.ipfs.io/ipfs/QmRA3NWM82ZGynMbYzAgYTSXCVM14Wx1RZ8fKP42G6gjgj)
- [A list of websites hosting the bitcoin whitepaper](https://blockchair.com/bitcoin/whitepaper), with sha256 hashes calculated hourly
- [Instructions and code](https://bitcoin.stackexchange.com/questions/35959/how-is-the-whitepaper-decoded-from-the-blockchain-tx-with-1000x-m-of-n-multisi) for decoding a version of the original paper hosted on the bitcoin blockchain

**note**

In the lead up-to the chain fork with BTC, certain members of the small-block side [attempted](https://github.com/bitcoin-dot-org/bitcoin.org/issues/1325) to make amendments and revisions to the original whitepaper.  For this reason, the original bitcoin whitepaper is actively monitored and checked for integrity.  

# Roadmaps

- [Roadmap](https://www.bitcoincash.org/roadmap.html) 
- [Coin Dance List](https://cash.coin.dance/development) - A list of broader developments and proposals 
- [Detailed Specs](https://www.bitcoincash.org/specs/) - An ongoing list of detailed specifications

# Developer resources:

- [Chris Troutner's introduction](https://troutsblog.com/research/bitcoin-cash/how-to-bch-full-stack-developer) to developing on bitcoin cash
- https://developers.cash/
- https://www.bitcoincash.org/developers.html

## Base Protocol

- [Base Protocol Reference](https://reference.cash/) - maintained by Bitcoin Unlimited

### Secondary protocols:

- [SLP Protocol](https://github.com/simpleledger/slp-specifications/blob/master/slp-token-type-1.md) for handling tradable or redeemable tokens
- [Memo Protocol](https://memo.cash/protocol) - For the on-chain tweet style social media app
- [Memo with Member extensions](https://github.com/memberapp/protocol) - For creating a reddit/hn style app
- [Cashfusion](https://github.com/cashshuffle/spec/blob/master/CASHFUSION.md) - A protocol for joining inputs from many parties to larger amounts

## Full Nodes

- [BitcoinABC](https://www.bitcoinabc.org/) [[mirror]](https://github.com/Bitcoin-ABC/bitcoin-abc) Bitcoin ABC is a full node implementation of the Bitcoin Cash protocol. The dominant mining implementation, C/C++.
- [BitcoinUnlimited](https://www.bitcoinunlimited.info/) [[src]](https://github.com/BitcoinUnlimited/BitcoinUnlimited) A full node implentation focused on supporting user needs.
- [BCHN](https://bitcoincashnode.org/) [[src]](https://gitlab.com/bitcoin-cash-node/bitcoin-cash-node) A descendant of the Bitcoin Core and Bitcoin ABC software projects with independant development team. C/C++.
- [bchd](https://bchd.cash/) [[src]](https://github.com/gcash/bchd) An alternative full node bitcoin cash implementation written in Go (golang)
- [Bitcoin Verde](https://bitcoinverde.org/) [[src]](https://github.com/softwareverde/bitcoin-verde)[[docs]](https://bitcoinverde.org/documentation/) A Java implementation with the goal of being interoperable with mining nodes
- [flowee](https://flowee.org/) [[src]](https://gitlab.com/FloweeTheHub) A full node supporting a suite of software focued on payment integration.

## SPV Wallets

### Desktop
- [Electron-Cash](https://electroncash.org) [[src]](https://github.com/Electron-Cash/Electron-Cash) - the awesome SVP wallet for Bitcoin Cash - Accept no imitations

#### Electron-Cash Plugins
- [CashFusion](https://cashfusion.org/)  plugin for privately and trustlessly joining coin amounts.
- [Flipstarter](https://gitlab.com/flipstarter/flipstarter-electron-cash) plugin for crowdfunding


## General Libraries & Software Development Kits:

- [Bitbox SDK](https://developer.bitcoin.com/bitbox/)[[docs]](https://developer.bitcoin.com/bitbox/docs/getting-started) for interacting with BCH via bitcoin.com
- [Bitcoin Cash JavaScript Library based on BITBOX
](https://fullstack.cash)[[docs]](https://bchjs.cash/bch-js/index.html) - Chris Troutner BitBox stack
- [Badger SDK docs](https://developer.bitcoin.com/badger/docs/getting-started) - Browser extension wallet
- [bitcash](https://sporestack.github.io/bitcash/) [[src]](https://github.com/sporestack/bitcash) - A python3 library for bitcoin cash.
- [bchd grpc web-client](https://github.com/simpleledgerinc/grpc-bchrpc-web) protobuf based javascript client for interacting with bchd full nodes
- [bchd python bindings](https://github.com/gcash/bchd/tree/master/bchrpc/pb-py) protobug based pyhton client for bchd

## Tokens
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
- [flipstarter](https://flipstarter.cash/) - A crowd funding app using Anyone can pay multisig transactions 
- [memo.cash](https://memo.cash) - Short message social media site with decentralized SLP token exchange
- [member.cash](https://member.cash) - Longer format social media platform with voting, tipping, moderation and filtering

### Marketplace
- [OpenBazaar](https://openbazaar.org/download/) - Desktop p2p marketplace using multisig transactions
- [Havenapp](https://gethaven.app/) - Mobile implementation of openbazaar 

### Entertainment
- [blockchain.poker](https://blockchain.poker) - Texas Hold'em using zero-conf for BCH deposits
- [Satoshi dice](https://www.satoshidice.com/) -  game

## Merchant Listings

### Awesome merchants
- [A good suit from lanieri](https://www.lanieri.com) - not that you would ever need one, for work.
- [Cheap plane tickets](https://www.cheapair.com) - for your fancy developer conferences. 

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

## Awesome Charity
- [Save the Children](https://files.savethechildren.org/cryptocurrency-donation/)
