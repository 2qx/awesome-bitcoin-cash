# awesome-bitcoin-cash
A curated list of awesome bitcoin cash dev resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

📤 [A shareable link](https://2qx.github.io/awesome-bitcoin-cash/) of this README fomatted with github pages

Bitcoin Cash (BCH) is a cryptocurrency forked from the BTC chain aimed at scaling to be an electronic peer-to-peer system for the world. 

This project is **not a fork** of the canonical [awesome-bitcoin-cash](https://github.com/dsmurrell/awesome-bitcoin-cash) project with a more general focus.

# Whitepaper

The bitcoin whitepaper by Satoshi Nakamoto:

- [Archived copy](http://web.archive.org/web/20100704213649if_/http://www.bitcoin.org:80/bitcoin.pdf) of the bitcoin whitepaper from bitcoin.org
- [bitcoin whitepaper](https://gateway.ipfs.io/ipfs/QmRA3NWM82ZGynMbYzAgYTSXCVM14Wx1RZ8fKP42G6gjgj) via ipfs
- [A list of websites hosting the bitcoin whitepaper](https://blockchair.com/bitcoin/whitepaper), with sha256 hashes calculated hourly
- [Instructions and code](https://bitcoin.stackexchange.com/questions/35959/how-is-the-whitepaper-decoded-from-the-blockchain-tx-with-1000x-m-of-n-multisi) for decoding a version of the original paper hosted on the pre-fork bitcoin blockchain
 

# Roadmaps

- [Bitcoin Cash Roadmap](https://www.bitcoincash.org/roadmap.html) - official.
- [Detailed Specs of Proposed Improvements](https://www.bitcoincash.org/specs/) - an ongoing list of detailed specifications
- [Coin Dance List](https://cash.coin.dance/development) - a broader list of developments and proposals in various states from many groups
- [Canonical awesome-bitcoin-cash](https://github.com/dsmurrell/awesome-bitcoin-cash) - an awesome early Bitcoin Cash list.

# Developer resources:

- [Full-Stack how-to](https://troutsblog.com/research/bitcoin-cash/how-to-bch-full-stack-developer) - Chris Troutner's introduction to developing on Bitcoin Cash
- [developers.cash](https://developers.cash/) - many useful resources and [tools](https://developers.cash/tools/)
- [bitcoincash.org dev docs](https://www.bitcoincash.org/developers.html) - libraries for interacting with Bitcoin Cash
- [KeepBitcoinFree](https://keepbitcoinfree.org/bch-dev/) - a great list of many B/itcoin Cash projects
- [tutorial.cash](https://www.tutorial.cash/) - video tutorials

## Base Protocol

- [Base Protocol Reference](https://reference.cash/) - maintained by Bitcoin Unlimited

### Secondary protocols:

- [SLP Protocol](https://github.com/simpleledger/slp-specifications/blob/master/slp-token-type-1.md) - for handling fungible or redeemable tokens
- [Memo Protocol](https://memo.cash/protocol) - for the on-chain tweet style social media app
- [Memo with Member extensions](https://github.com/memberapp/protocol) - for creating a reddit/hn style app
- [CashShuffle](https://cashshuffle.com/)[[spec]](https://github.com/cashshuffle/spec/blob/master/SPECIFICATION.md) - a privacy protocol for combining transactions with others, splitting to the lowest common amount.
- [CashFusion](https://cashfusion.org/)[[spec]](https://github.com/cashshuffle/spec/blob/master/CASHFUSION.md) - a privacy protocol for privately and trustlessly joining coin amounts.

## Full Nodes

- [BitcoinABC](https://www.bitcoinabc.org/) [[mirror]](https://github.com/Bitcoin-ABC/bitcoin-abc) - a full node implementation of the Bitcoin Cash protocol. The dominant mining implementation, C/C++.
- [BitcoinUnlimited](https://www.bitcoinunlimited.info/) [[src]](https://github.com/BitcoinUnlimited/BitcoinUnlimited) - a full node implentation focused on supporting user needs, C/C++.
- [BCHN](https://bitcoincashnode.org/) [[src]](https://gitlab.com/bitcoin-cash-node/bitcoin-cash-node) - a descendant of the Bitcoin Core and Bitcoin ABC software projects with independant development team. C/C++.
- [bchd](https://bchd.cash/) [[src]](https://github.com/gcash/bchd) - alternative implementation written in Go (golang)
- [Bitcoin Verde](https://bitcoinverde.org/) [[src]](https://github.com/softwareverde/bitcoin-verde)[[docs]](https://bitcoinverde.org/documentation/) - java implementation with the goal of being interoperable with mining nodes
- [flowee TheHub](https://flowee.org/) [[src]](https://gitlab.com/FloweeTheHub) - a node supporting a suite of software focued on payment integration. C++

## Open Source Wallets

### Desktop
- [Electron-Cash](https://electroncash.org) [[src]](https://github.com/Electron-Cash/Electron-Cash) - the awesome SPV wallet for Bitcoin Cash

#### Electron-Cash Plugins
- [Flipstarter Plugin](https://gitlab.com/flipstarter/flipstarter-electron-cash) - plugin for crowdfunding
- [Mecenas Plugin](https://github.com/KarolTrzeszczkowski/Mecenas-recurring-payment-EC-plugin/releases) - recurring payments
- [Last Will](https://github.com/KarolTrzeszczkowski/Electron-Cash-Last-Will-Plugin) - dead man smart contract creation

### Mobile
- [Electron-Cash](https://electroncash.org) - Android and iOS version available with limited functionality 
- [neutrino](https://github.com/gcash/android-neutrino) - Android wallet with advanced privacy features.

### Cli
- [bchwallet](https://github.com/gcash/bchwallet) - a secure Bitcoin Cash wallet daemon written in Go (golang)
- [openbazaar wallet](https://github.com/OpenBazaar/spvwallet) - an SPV wallet in Go (golang) used by openbazaar2

### Browser

- [blockparty](https://blockparty.sh/) [[docs]](https://github.com/blockparty-sh/wallet/blob/master/README.md) - A simple in-browser web wallet using bitox.earth

### Paper/Offline Generator
- [Cash Address Generator](https://cashaddress.org/) - reputible javascript random address generator suitable for offline use.
- [BCH Gifts](https://gifts.bitcoin.com/) - generate reclaimable preloaded paper private keys as gifts.
- [SLP wallet generator](https://wallet.bitchslap.tech/) - generator for Simple Ledger addresses

## General Libraries & Software Development Kits:

### Javascript
- [Bitcoin Cash JavaScript Library based on BITBOX
](https://fullstack.cash)[[docs]](https://bchjs.cash/bch-js/index.html) - Chris Troutner's Bitcoin Cash stack
- [libcash-js](https://developers.cash/resource/libcash-js/default) - javascript library using the flowee api
- [bchd grpc web-client](https://github.com/simpleledgerinc/grpc-bchrpc-web) - protobuf based javascript client for interacting with bchd full nodes

### Typescript
- [Bitbox SDK](https://developer.bitcoin.com/bitbox/) [[docs]](https://developer.bitcoin.com/bitbox/docs/getting-started) - library for interacting with BCH via bitcoin.com
- [Badger SDK](https://developer.bitcoin.com/badger/docs/getting-started) - browser extension wallet supporting BCH and SLP on webpages
- [bitcoin-ts](https://github.com/bitauth/bitcoin-ts) - a zero-dependency, typescript bitcoin library, including WASM crypto functions, BTC, but BCH friendly.

### Python
- [bitcash](https://sporestack.github.io/bitcash/) [[src]](https://github.com/sporestack/bitcash) - python3 library.
- [bchd python bindings](https://github.com/gcash/bchd/tree/master/bchrpc/pb-py) - sample protobuf based python client for bchd.

## SLP Tokens

- [Electron-Cash SLP Edition](https://simpleledger.cash/project/electron-cash-slp-edition/) 
- [slpjs](https://github.com/simpleledger/slpjs) - library for interacting with SLP tokens, dependant on bitbox.
- [SLP SDKs](https://simpleledger.cash/project/slp-sdk/) - link to sdks for android and iOS.

## Scripting

- [meep](https://github.com/gcash/meep) - a command line Bitcoin Cash script debugger.
- [bitauth ide](https://ide.bitauth.com/) [[src]](https://github.com/bitauth/bitauth-ide) - an integrated development environment for bitcoin authentication
- [spedn](https://spedn.readthedocs.io/en/latest/) [[src]](https://bitbucket.org/o-studio/spedn/src/develop/) - a high level smart contracts language that compiles to Bitcoin Cash Script.
- [Cashscript](https://developer.bitcoin.com/cashscript/docs/language) - a solidity-style language that compiles to Bitcoin Cash Script.
 
# Adoption

### Shipyard

These are up and coming projects in beta:

- [causes.cash](https://causes.cash/) - a site for creating your own fundraising campaign

## Apps

### Network

- [doublespend.cash](https://doublespend.cash) - to view Bitcoin Cash double spend attempts
- [tx street](https://txstreet.com/beta) - transaction visualizer
- [privacy stats](https://stats.cash/#/) - recent list and totals of shuffles & fusions

### Social
- [read.cash](https://read.cash) - a conventional long-format blogging platform, with BCH tipping for content
- [flipstarter](https://flipstarter.cash/) [Introduction](https://read.cash/@flipstarter/introducing-flipstarter-695d4d50) - a crowd funding app using anyone can pay multisig transactions 
- [memo.cash](https://memo.cash) - short message social media site with decentralized SLP token exchange
- [member.cash](https://member.cash) - longer format social media platform with voting, tipping, moderation and filtering

### Marketplace
- [OpenBazaar](https://openbazaar.org/download/) -  Desktop (daemon w/ electron app) p2p marketplace using multisig transactions
- [Havenapp](https://gethaven.app/) - Mobile implementation of openbazaar 

### Entertainment
- [blockchain.poker](https://blockchain.poker) - Texas Hold'em using zero-conf for BCH deposits, BTC and BSV supported
- [Satoshi dice](https://www.satoshidice.com/) -  a provably fair dice game

### Web

- [Pay Button](https://paybutton.org/docs/) [[src]](https://github.com/PayButton/paybutton) - a simple embedable script to accept Bitcoin Cash on your website

### Bots

- [chaintip](https://www.chaintip.org) - an on-chain non-custodial tipping bot for reddit/twitter & github.
- [Chaintip Bounties](https://github.com/chaintip/bounties/blob/master/README.md#available-bounties) - BCH bot for github bounties

## Launchpad

Awesome projects which appear to be dormant due to lack of use.

- [lazyfox](https://lazyfox.io) - a Bitcoin Cash powered question and answer / tasking platform 
- [stack exchange](https://read.cash/@nyusternie/stackexchange-provides-shelter-for-homeless-bch-developers-87223764) - an unsuccessful initiative to create a Bitcoin Cash stack exchange
- [Satoshi Wall](https://satoshiwall.cash/) - a non-custodial payment wall service
- [Chaintip Bounties](https://github.com/chaintip/bounties/blob/master/README.md#available-bounties) - bounties for github commits


## In the Boneyard

These ships are apparently in long term storage

- [Learn Bitcoin dot Cash](https://learnbitcoin.cash/) - Letsencrypt expired Monday, April 27, 2020 at 2:24:48 PM
- [BCH Pizza](https://www.bchpizza.org) - Connection Refused
- [SLPDEX](https://slpdex.cash/) [[src]](https://github.com/slpdex/slpdex) - Decentralized token exchange


## eCommerce 

### Plugins and Resources

- [WooCommerce plugin](https://github.com/sanchaz/P2P-Electronic-Cash-Payments-for-WooCommerce) - accepting BCH and BSV
- [BitPay developer tools](https://bitpay.com/docs)
- [Shopify Cryptocurrency Docs](https://help.shopify.com/en/manual/payments/alternative-payments/cryptocurrency)

#### The Awesome Short List

This list is meant to highlight the really awesome sites, but not replicate the general listing services below. They have accepted Bitcoin Cash for years and are committed (or sympathetic) toward the idea of electronic cash payments.

- [Cheap plane tickets](https://www.cheapair.com) - for your travel needs. 
- [Items sold by newegg](https://newegg.com) - good for a great headset.
- [Lanieri](https://www.lanieri.com) - makes a good suit.

### Merchants near you or where you're headed
- [Member map](https://memberapp.github.io/#map) - permanent on-chain geographic tags utilizing extensions to the memo protocol.
- [Bitcoin.com map](https://map.bitcoin.com/) - website and mobile app for discovering merchants, formerly marcocoino
- [Greenpages map](https://greenpages.cash/pages/map.php) - merchant finder with advanced filtering

### Listing directories across the broader internet
- [The Accept Bitcoin Cash Initiative](https://acceptbitcoin.cash) - browsable list of merchants and stores
- [Bitpay Directory](https://bitpay.com/directory) - partial and outdated list of websites using bitpay as a payment processor.
- [Openbazaar Listings](https://openbazaar.com) - web listings for distributed multicoin marketplace with integrated wallet
- [Purse.io](https://purse.io/) - service to privately purchace goods on Amazon.com (US) at a discount

## Awesome Charities and Foundations
- [Save the Children](https://files.savethechildren.org/cryptocurrency-donation/)
- [Electronic Freedom Foundation](https://supporters.eff.org/donate/join-4) 
- [Tails](https://tails.boum.org/donate/index.en.html)
