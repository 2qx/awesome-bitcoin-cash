<div id='stars'></div>
<div id='stars2'></div>
<div id='stars3'></div>
<br/>
<div align="center">
  <img width="400px" alt="awesome bitcoin cash" src="./awesome-bitcoin-cash.dark.svg">
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

<!--💚-->

# Contents

- [Contents](#contents)
- [Getting Started](#getting-started)
- [State of the Project](#state-of-the-project)
- [Whitepaper](#whitepaper)
- [Open-Source Wallets](#open-source-wallets)
  - [Mobile](#mobile)
  - [Desktop](#desktop)
    - [Electron-Cash Plugins](#electron-cash-plugins)
  - [Cli](#cli)
  - [Browser](#browser)
  - [Paper/Offline Generator](#paperoffline-generator)
- [Projects Built on Bitcoin Cash](#projects-built-on-bitcoin-cash)
  - [Apps (Social)](#apps-social)
  - [Crowdfunding](#crowdfunding)
  - [Entertainment](#entertainment)
  - [Exchanges](#exchanges)
    - [Centralized](#centralized)
    - [More decentralized](#more-decentralized)
  - [Oracles](#oracles)
  - [Faucets](#faucets)
  - [Network](#network)
  - [SmartBCH Projects](#smartbch-projects)
  - [SLP Token Projects](#slp-token-projects)
  - [Services](#services)
  - [Utilities](#utilities)
  - [Web](#web)
  - [See Also](#see-also)
- [Merchants and Services Accepting Bitcoin Cash](#merchants-and-services-accepting-bitcoin-cash)
  - [A Short List](#a-short-list)
  - [Geographic lists](#geographic-lists)
  - [Projects dedicated to listing or enabling eCommerce.](#projects-dedicated-to-listing-or-enabling-ecommerce)
  - [Some Charities and Foundations](#some-charities-and-foundations)
- [eCommerce Merchant Resources](#ecommerce-merchant-resources)
  - [Bitcoin Cash Open-Source plugins](#bitcoin-cash-open-source-plugins)
  - [Non-Custodial Payment Processors](#non-custodial-payment-processors)
  - [BCH-to-Fiat Payment Processors](#bch-to-fiat-payment-processors)
  - [Payment Processor Status](#payment-processor-status)
- [Documentation](#documentation)
  - [Roadmaps](#roadmaps)
  - [General](#general)
  - [Base Protocol](#base-protocol)
    - [Secondary protocols](#secondary-protocols)
  - [Improvement Proposals](#improvement-proposals)
  - [Miner Consensus](#miner-consensus)
  - [Bitcoin Script](#bitcoin-script)
- [Software](#software)
  - [Full Nodes](#full-nodes)
    - [Developer Resources](#developer-resources)
  - [Open-Source Teams Building on Bitcoin Cash](#open-source-teams-building-on-bitcoin-cash)
  - [Testnet 4](#testnet-4)
  - [Simple Payment Verification (SPV)](#simple-payment-verification-spv)
  - [Simple Ledger Protocol (SLP Token)](#simple-ledger-protocol-slp-token)
    - [Protocols](#protocols)
    - [Libraries](#libraries)
  - [Libraries & SDKs](#libraries--sdks)
    - [Language Agnostic](#language-agnostic)
    - [Typescript](#typescript)
    - [Javascript](#javascript)
    - [Python](#python)
    - [Java](#java)
    - [C](#c)
    - [PHP](#php)
    - [R](#r)
- [Podcasts, News & Media](#podcasts-news--media)
  - [The Bitcoin Cash Podcast](#the-bitcoin-cash-podcast)

# Getting Started

- [bitcoincash.org](https://bitcoincash.org) - A general multi-lingual introduction.
- [BCH Info](https://bch.info/) - Multilingual site for general information about bitcoin cash.
- [Why Bitcoin Cash?](https://whybitcoincash.com/) - The revolution will not be censored.
- [Bitcoin.com Getting Started](https://www.bitcoin.com/get-started/) - Comprehensive introduction for general audiences.

# State of the Project

- [Three Years In: A Bitcoin Cash Update From One of Its Founders](https://news.bitcoin.com/three-years-in-a-bitcoin-cash-update-from-one-of-its-founders/) - by Jonald Fyookball

# Whitepaper

"Bitcoin: A Peer-to-Peer Electronic Cash System" by Satoshi Nakamoto.

Bitcoin Cash is one chain of Satoshi Nakamoto's blockchain invention which was deliberately hard-forked on August 1st, 2017. It shares the whitepaper, first block, and all bitcoin block history prior to the fork. It attempts to implement the central idea outlined in that paper.

Below is a copy of the original nine page whitepaper:

- [Archived copy](https://web.archive.org/web/20100704213649if_/http://www.bitcoin.org:80/bitcoin.pdf) of the bitcoin whitepaper from bitcoin.org.
- [bitcoin whitepaper](https://gateway.ipfs.io/ipfs/QmRA3NWM82ZGynMbYzAgYTSXCVM14Wx1RZ8fKP42G6gjgj) via ipfs.
- Websites hosting the bitcoin whitepaper [[wayback archive]](http://web.archive.org/web/20210516141704if_/https://blockchair.com/bitcoin/whitepaper), with sha256 hashes calculated as of May 16th 2021.
- [As a webcomic](https://whitepaper.coinspice.io/) - Bitcoin White Paper web comic.
- [Instructions and code](https://bitcoin.stackexchange.com/questions/35959/how-is-the-whitepaper-decoded-from-the-blockchain-tx-with-1000x-m-of-n-multisi) for building the original paper encoded on the blockchain on 2013-04-06.

# Open-Source Wallets

Below are non-custodial open-source wallets that use features specific to Bitcoin Cash.

## Mobile

- [Electron-Cash](https://electroncash.org) - Android [[src]](https://github.com/Electron-Cash/Electron-Cash/tree/master/android) and iOS [[src]](https://github.com/Electron-Cash/Electron-Cash/tree/master/ios) versions available with more limited functionality.
- [Bitcoin.com](https://wallet.bitcoin.com/) - A user friendly bitcoin wallet.
- [edge.app](https://edge.app) [[src]](https://github.com/EdgeApp/edge-react-gui) [[apk]](https://apk.edge.app/) - Edge Wallet for iOS and Android. A multi-coin non-custodial wallet for BCH, XMR, ETH, LTC, DOGE, EOS, XRP, DASH, XLM and others.
- [zapit](https://zapit.io/#/) - A native, non-custodial Bitcoin Cash wallet for iOS and Android.
- [bread](https://brd.com/) - Multicoin wallet for Android [[src]](https://github.com/breadwallet/breadwallet-android) and iOS [[src]](https://github.com/breadwallet/breadwallet-ios)
- [neutrino](https://neutrino.cash/) [[src]](https://github.com/gcash/android-neutrino) - Android wallet with advanced privacy features.

Honorable mention:

- [Cake Wallet](https://cakewallet.com/) [[src]](https://github.com/cake-tech/cake_wallet) [[apk]](https://github.com/cake-tech/cake_wallet/releases) - An open source wallet for iOS and Android supporting XMR and other currencies.

## Desktop

- [Electron-Cash](https://electroncash.org) [[src]](https://github.com/Electron-Cash/Electron-Cash) - the awesome SPV wallet for Bitcoin Cash.

### Electron-Cash Plugins

- [Flipstarter Plugin](https://gitlab.com/flipstarter/flipstarter-electron-cash) - plugin for crowdfunding.
- [Mecenas Plugin](https://github.com/KarolTrzeszczkowski/Mecenas-recurring-payment-EC-plugin/releases) - recurring payments.
- [Last Will](https://github.com/KarolTrzeszczkowski/Electron-Cash-Last-Will-Plugin) - dead man smart contract creation.
- [More Comprehensive List](https://blog.imaginary.cash/index.php/electron-cash-plugins/) - hosted by im_uname.

## Cli

- [bchwallet](https://github.com/gcash/bchwallet) - a secure Bitcoin Cash wallet daemon written in Go (golang)
- [openbazaar wallet](https://github.com/OpenBazaar/spvwallet) - an SPV wallet in Go (golang) developed for openbazaar2
- [bitcore-wallet](https://github.com/bitpay/bitcore/tree/master/packages/bitcore-wallet) - A command line wallet used for BitPay wallets.

## Browser

- [PSF wallet](https://wallet.fullstack.cash/) [[src]](https://github.com/Permissionless-Software-Foundation/gatsby-ipfs-web-wallet) - Static javascript web-wallet using gatsby react from the permissionless software foundation.
- [BCH Merchant PoS](https://pos.cash)[[src]](https://github.com/softwareverde/pos-cash) - Bitcoin Cash Web Point of Sale, from SoftwareVerde.
- [blockparty](https://blockparty.sh/) [[src]](https://github.com/blockparty-sh/wallet/) [[docs]](https://github.com/blockparty-sh/wallet/blob/master/README.md) - A simple in-browser web wallet using bitbox.earth.

## Paper/Offline Generator

- [Cash Address Generator](https://cashaddress.org/) - reputable javascript address generator suitable for offline use.
- [BCH Gifts](https://gifts.bitcoin.com/) - generate reclaimable preloaded paper private keys as gifts.

# Projects Built on Bitcoin Cash

All of these apps are mostly stable and active. Always check the notes of a particular project before risking a large sum of value. Links are checked on a weekly basis, but function is not checked.

## Apps (Social)

- [noise.cash](https://noise.cash) - A Bitcoin Cash powered micro-blogging platform.
- [read.cash](https://read.cash) - a conventionally hosted long-format blogging platform, with BCH tipping for content.
- [memo.cash](https://memo.cash) - short message social media site with decentralized SLP token exchange.
- [lazyfox](https://lazyfox.io) - a Bitcoin Cash powered question and answer / tasking platform.
- [OnlyCoins](https://onlycoins.com/) - Adult content monetization platform.

## Crowdfunding

- [causes.cash](https://causes.cash/) [[src]](https://gitlab.com/bchplease/causes.cash) - a site for creating your own fundraising campaign.
- [flipstarter](https://flipstarter.cash/) [[Introduction]](https://read.cash/@flipstarter/introducing-flipstarter-695d4d50) [[src]](https://gitlab.com/flipstarter/backend) - a crowd funding app using anyone can pay multisig transactions.
- [IPFS Flipstarter](https://create.flipstarter.me/) [[src]](https://gitlab.com/ipfs-flipstarter/admin) - An IPFS flipstarter campaign site.

## Entertainment

- [blockchain.poker](https://blockchain.poker) - Texas Hold'em using zero-conf for BCH deposits, BTC and BSV supported.
- [bch.games](https://bch.games/) - dice and numbers game.
- [craft.cash](https://craft.cash/) [[src]](https://github.com/blockparty-sh/craft.cash) - Voxel world stored on Bitcoin Cash.
- [Satoshi dice](https://www.satoshidice.com/) - a provably fair dice game.
- [Enter the Sphere](https://market.enter-the-sphere.com/) - NFT trading card game.
- [Spin BCH](https://SpinBCH.com) - Spinning wheel based gambling using zero-conf

## Exchanges

Bitcoin Cash is supported on hundreds of exchanges, these are a few.

### Centralized

- [CoinEx](https://www.coinex.com/) - A BCH friendly exchange with automatic coin-splitting
- [Coinbase](https://www.coinbase.com/) - A regulated US based exchange.

### More decentralized

- [Local Cryptos](https://localcryptos.com/) - Peer-to-peer marketplace with non-custodial escrow which supports Bitcoin Cash.
- [AtmoicDex](https://atomicdex.io/) - Decentralized exchange with desktop clients supporting BCH and many UTXO coins, ETH, ERC-20 tokens

## Oracles

- [Oracles.Cash](https://oracles.cash/) [[Best Practices]](https://gitlab.com/GeneralProtocols/priceoracle/library#best-practices-for-price-oracle-consumers) [[spec]](https://gitlab.com/GeneralProtocols/priceoracle/specification) - Price oracles for Bitcoin Cash

## Faucets

- [Testnet4 Faucet](https://tbch4.googol.cash/) [[src]](https://gitlab.com/uak/light-crypto-faucet)
- [Testnet Faucet](https://tbch.googol.cash/) [[src]](https://gitlab.com/uak/light-crypto-faucet)
- BCH Testnet Faucet [[src]](https://github.com/christroutner/testnet-faucet2/) - Fullstack.cash faucet for tBCH.
- [bitcoin-cash-faucet](https://www.npmjs.com/package/bitcoin-cash-faucet) [[src]](https://github.com/2qx/bitcoin-cash-faucet#readme) - An on-chain faucet for tBCH and BCH using introspection.

## Network

- [Blockchain Explorer](https://explorer.bitcoinunlimited.info/) [[src]](https://github.com/sickpig/bch-rpc-explorer) - Database-free, self-hosted Bitcoin Cash explorer, via RPC,
  - [(also available for Testnet)](https://texplorer.bitcoinunlimited.info/)
  - [(also available for Testnet4)](https://testnet4.imaginary.cash/)
- [Chaingraph](https://chaingraph.cash/) [[src]](https://github.com/bitauth/chaingraph) - A multi-node blockchain indexer and GraphQL API.
- [Blockchain.com BCH explorer](https://www.blockchain.com/explorer?view=bch) [[bch testnet]](https://www.blockchain.com/explorer?view=bch-testnet) - Established blockchain explorer.
- [privacy stats](https://stats.sploit.cash/#/fusion) - Recent list fusions.
- [CashFusion Stats](https://fusionstats.redteam.cash/) - Data on privacy-enhancing CashFusion transactions.
- [doublespend.cash](https://doublespend.cash) - view Bitcoin Cash double spend attempts.
- [tx street](https://txstreet.com/v/bch) - transaction visualizer, updated with popular protocols.
- [fork.lol](https://fork.lol) - Site to monitor network health in relation to BTC.
- [Johoe's Bitcoin Mempool Statistics](https://jochen-hoenicke.de/queue/) [[src]](https://github.com/jhoenicke/mempool) - Colorful mempool graphs.
- [Electrum Server Status for BCH](https://1209k.com/bitcoin-eye/ele.php?chain=bch) [[or tBCH]](https://1209k.com/bitcoin-eye/ele.php?chain=tbch) - A 1209k hosted list of electrum servers
- [CoinSalad](https://coinsalad.com/bitcoincash/) - Bitcoin Cash statistics
- [bitcoinfees.cash](https://bitcoinfees.cash/) - bitcoin chain fee juxtaposition.

## SmartBCH Projects

Protocol:

- [smartBCH](https://smartbch.org/) [[whitepaper]](https://smartbch.github.io/whitepaper/SmartBCH_Whitepaper-en.pdf) [ (中文)](https://smartbch.github.io/whitepaper/SmartBCH_Whitepaper-cn.pdf) [[src]](https://github.com/smartbch/smartbch) - an EVM&Web3 compatible sidechain for Bitcoin Cash

🐉 🐉 smartBCH is a permissionless BCH sidechain. It is not BCH 🐉 🐉

- [helpme.cash](https://helpme.cash/) - Getting started with SmartBCH
- [smartBCH](https://smartbch.org/) [[repos]](https://github.com/smartbch) - EVM & Web3 on a sidechain of Bitcoin Cash
- [Smartscan Explorer](https://www.smartscan.cash/) [[src]](https://github.com/jay-bch/smartbch-explorer) - Explorer for smartBCH.
- [smartBCH Stats](https://smartbch.fountainhead.cash/grafana/d/GUnTOBGnz/smartbch?orgId=1&refresh=5s) - Grafana for SmartBCH
- [hop.cash](https://hop.cash/) - Bridge to swap BCH for smartBCH
- [Verse Dex](https://verse.bitcoin.com/) - Uniswap based Automated Maker Model Dex for SmartBCH.
- [benswap](https://benswap.finance/) [[src]](https://github.com/BenTokenFinance) - Decentralized exchanged on SmartBCH
- [mistswap](https://app.mistswap.fi) [[src]](https://github.com/mistswapdex) [[docs]](https://docs.mistswap.fi/) - SEP-20 swap based on the mist SLP-token
- [marketcap.cash](https://www.marketcap.cash/) - Market Capitalization of Bitcoin Cash SEP20 Tokens on SmartBCH

## SLP Token Projects

- [SLP Explorer](https://simpleledger.info/) [[src]](https://github.com/salemkode/slp-explorer) [[backend src]](https://github.com/salemkode/slp-explorer-backend) - Open source explorer for SLP tokens.
- Electron-Cash SLP Edition [[src]](https://github.com/simpleledger/Electron-Cash-SLP) [[releases]](https://github.com/simpleledger/Electron-Cash-SLP/releases)
- [Honk Token](https://honkhonk.io/) [[whitepaper]](https://honkhonk.io/honkwhitepaper.pdf) - A gambling/gaming/multipurpose SLP token.
- mistcoin [[archive]](http://web.archive.org/web/20210128134553/https://mistcoin.org/) [[blue miner]](https://gitlab.com/blue_mist/miner) - A mineable SLP token using a proof-of-work covenant contract
- [SpiceToken](https://spicetoken.org/) - A meme token for social tipping.

## Services

- [chaintip](https://www.chaintip.org) - An on-chain non-custodial tipping bot for reddit/twitter & github.
- [SideShift.ai](https://sideshift.ai/) - enables HUMANS and AI to shift between 30+ cryptocurrencies.
- [WhaleAlertBCH](https://twitter.com/WhaleAlertBch) [[src]](https://github.com/Ekliptor/cashwhale) - A twitter whalebot for BCH.
- [Chaintip Bounties](https://github.com/chaintip/bounties/blob/master/README.md#available-bounties) - BCH bot for github bounties.
- [CCtip](https://cctip.io/) - Tipping for twitter, telegram, & discord.

## Utilities

- [CashAccount](https://www.cashaccount.info/) - Online utility for cashaccounts (address handles).
- [Bitcoin.com Tools](https://tools.bitcoin.com/) - A mix of Bitcoin utilities.
- [Bitauth IDE](https://ide.bitauth.com/) [[src]](https://github.com/bitauth/bitauth-ide) - An online IDE for developing Bitcoin Cash contracts.

## Web

- [PayButton](https://paybutton.org/) [[src]](https://github.com/paybutton/paybutton) - a simple html (or react component) button to accept Bitcoin Cash on a website.
- [Bitcoin Paywall](https://wordpress.org/plugins/bitcoin-paywall/) [[src]](https://plugins.trac.wordpress.org/browser/bitcoin-paywall/) - Wordpress paywall plugin

## See Also

These are other projects dedicated to listing projects in the Bitcoin Cash ecosystem:

- [Bitcoin Cash Projects](https://www.bitcoin.com/bitcoin-cash-projects/) - maintained by bitcoin.com.
- [BCH Developments](https://keepbitcoinfree.org/bch-dev/) - list maintained by KeepBitcoinFree.
- [Canonical awesome-bitcoin-cash](https://github.com/dsmurrell/awesome-bitcoin-cash) - the original.

# Merchants and Services Accepting Bitcoin Cash

## A Short List

These vendors have accepted bitcoin for years and are committed (or sympathetic) toward the idea of electronic cash payments.

Although some of these may appear to only accept Bitcoin (BTC), they do, in fact, accept Bitcoin Cash also.

- [Namecheap](https://namecheap.com) - dns, ssl and some packaged hosting.
- [keys4coins](https://www.keys4coins.com/) - Buy PC games and gift cards with cryptocurrency.
- [alfa.top](https://alfa.top/) - Buy mobile top-up (credit) and internet with cryptocurrency.
- [CheapAir](https://www.cheapair.com) - for your travel needs.
- [items sold by Newegg](https://kb.newegg.com/knowledge-base/using-bitcoin-on-newegg/) - good for a great headset.
- [Lanieri](https://www.lanieri.com) - makes a good suit.
- [partsoven](https://www.partsoven.com/) - for that 3rd dimension of building.

## Geographic lists

- [Bitcoin.com map](https://map.bitcoin.com/) - website and mobile app for discovering merchants, formerly marco coino.

## Projects dedicated to listing or enabling eCommerce.

- [The Accept Bitcoin Cash Initiative](https://acceptbitcoin.cash) - list of merchants and stores.
- [Bitpay Directory](https://bitpay.com/directory) - partial list of websites using bitpay as a payment processor (sometimes outdated).
- [Purse.io](https://purse.io/) - service to privately purchase goods on Amazon.com (US) at a discount.
- [CryptoToPayPal](https://cryptotopaypal.com/) - Merchant paypal to crypto or send cryptocurrencies to paypal.

## Some Charities and Foundations

Just some good charities for the world at large.

- [Tails](https://tails.boum.org/donate/index.en.html) - The Amnesic Incognito Live System, is a security-focused Debian-based Linux distribution aimed at preserving privacy and anonymity.
- [Save the Children](https://files.savethechildren.org/cryptocurrency-donation/) - **A United Kingdom based charity, founded in 1919**, to improve the lives of children through better education, health care, and economic opportunities, as well as providing emergency aid in natural disasters, war, and other conflicts. (Cryptocurrency donations are powered by [The Giving Block](https://www.thegivingblock.com/))
- [God's Love We Deliver](https://www.glwd.org/donate/ways-to-give/donate-crypto-currency/) - **A non-denominational NYC charity**, that delivers illness-specific meals to New Yorkers in need [*especially* in pandemics]. Powered by [The Giving Block](https://www.thegivingblock.com/))
- [Electronic Freedom Foundation](https://supporters.eff.org/donate/join-4) - dedicated to ensuring that technology supports freedom, justice, and innovation for all the people of the world.
- [Bitpay Charity Directory](https://bitpay.com/directory/nonprofits) A list of charities that accept Bitcoin Cash and other cryptocurrencies.

# eCommerce Merchant Resources

## Bitcoin Cash Open-Source plugins

- [CryptoWoo for WooCommerce](https://github.com/WeProgramIT/cryptowoo-bitcoin-cash-addon) - Bitcoin Cash integration for CryptoWoo

## Non-Custodial Payment Processors

- [Prompt.cash](https://prompt.cash) [[demo]](https://www.youtube.com/watch?v=8TIpZW1P_9M) [[docs]](https://prompt.cash/pub/docs/#introduction) - **Non-custodial** Bitcoin Cash payment gateway
- [Cash Pay Server](https://github.com/developers-cash/cash-pay-server-js) [[docs]](https://developers-cash.github.io/cash-pay-server-js/) - a self-hostable NodeJS micro-service that can be used to handle BIP70 and JSON Payment Protocol invoices for Bitcoin Cash (BCH)

## BCH-to-Fiat Payment Processors

- [BitPay developer Integrations](https://bitpay.com/integrations/) [[api docs]](https://bitpay.com/docs)
- [Coinbase](https://commerce.coinbase.com/integrate) - Merchant integrations for coinbase.

## Payment Processor Status

- [status.coinbase.com](https://status.coinbase.com/#) - Dashboard with subscriptions endpoints and post-mortems.
- [status.bitpay.com](https://status.bitpay.com/) - Current status with recent incidents.

# Documentation

## Roadmaps

- [Coin Dance list](https://cash.coin.dance/development) - with broader developments and proposals in various states from many groups.

## General

- [developers.cash](https://developers.cash/) - many useful resources
- [Bitcoin.com Developer Resources](https://www.bitcoin.com/developer/) - Tooling and documentation developed by bitcoin.com.
- [Permissionless Software Foundation Videos](https://psfoundation.cash/video/)

## Base Protocol

- [Bitcoin Cash Protocol Documentation](https://documentation.cash/) [[src]](https://github.com/SoftwareVerde/bitcoin-cash-specification) - maintained by Software Verde.
- [BCH Specification](https://flowee.org/docs/spec/) - Specification hosed by flowee.org.

### Secondary protocols

[Bitcoin Cash Standards](https://bitcoincashstandards.org) is a site dedicated to collecting, some of which are listed below:

- [Cashaddr](https://upgradespecs.bitcoincashnode.org/cashaddr/) - Format for Bitcoin Cash addresses.
- [Electrum Cash Protocol](https://bitcoincash.network/electrum/) [[src]](https://github.com/dagurval/electrum-cash-protocol) - Protocol for SPV clients and servers.
- [Payment Requests Specification (BIP-0070)](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) - For dealing with invoice style payments at specific amounts.
- [Cash Accounts](https://gitlab.com/cash-accounts/specification/blob/master/SPECIFICATION.md) - attach a human readable name to Bitcoin Cash addresses.
- [Memo Protocol](https://memo.cash/protocol) - for the on-chain tweet style social media app.
- [CashFusion](https://cashfusion.org/) [[spec]](https://github.com/cashshuffle/spec/blob/master/CASHFUSION.md) - a privacy protocol for privately and trustlessly joining coin amounts.

- [CashID](https://gitlab.com/cashid/protocol-specification) - Specification using Bitcoin Cash for secure authentication.

- [CashShuffle](https://cashshuffle.com/) [[spec]](https://github.com/cashshuffle/spec/blob/master/SPECIFICATION.md) - a privacy protocol for combining transactions with others, splitting to the lowest common amount.
- [Price Oracle](https://gitlab.com/GeneralProtocols/priceoracle/specification) [[🐉implementation]](https://gitlab.com/GeneralProtocols/priceoracle/library) - Price oracle work in progress.

## Improvement Proposals

- [Bitcoin Cash Improveent Proposals (CHIPS)](https://gitlab.com/GeneralProtocols/research/chips)
- [Bitcoin Unlimited Improvement Proposals (BUIPS)](https://www.bitcoinunlimited.info/voting/)

## Miner Consensus

- [Bitcoin Mining Parlament](https://bmp.virtualpol.com/) [[README]](https://bmp.virtualpol.com/README) [[src]](https://github.com/JavierGonzalez/BMP) - A decentralized place to talk, vote and more with delegated hashpower.

## Bitcoin Script

- [Cashscript](https://cashscript.org/docs/basics/about/) [[src]](https://github.com/Bitcoin-com/cashscript) [[playground]](https://playground.cashscript.org/) - a solidity-style language that compiles to Bitcoin Cash Script.
- [AutoCove](https://github.com/TinosNitso/AutoCove-Plugin) - Electrum-cash script decoder.
- [meep](https://github.com/gcash/meep) - a command line Bitcoin Cash script debugger.
- [Cashscript VS Code plugin](https://marketplace.visualstudio.com/items?itemName=nathanielcherian.cashscript) [[src]](https://github.com/nathanielCherian/vscode-cashscript) - Visual Studio Code extension for cashscript.
- [bitauth ide](https://ide.bitauth.com/) [[src]](https://github.com/bitauth/bitauth-ide) [[video intro]](https://www.youtube.com/watch?v=o-igo-adS8E) - an integrated development environment for bitcoin authentication.
- [spedn](https://spedn.pl/) [[src]](https://bitbucket.org/o-studio/spedn/src/develop/) [[docs]](https://spedn.readthedocs.io/en/latest/) - a high level smart contract language that compiles to Bitcoin Cash Script.

# Software

## Full Nodes

- [BCHN](https://bitcoincashnode.org/) [[src]](https://gitlab.com/bitcoin-cash-node/bitcoin-cash-node) [[docs]](https://docs.bitcoincashnode.org/) - a descendant of the Bitcoin Core and Bitcoin ABC software projects with independent development team. C/C++.
- [BitcoinUnlimited](https://www.bitcoinunlimited.info/) [[src]](https://github.com/BitcoinUnlimited/BitcoinUnlimited) - a full node implentation focused on supporting user needs, C/C++.
- [Flowee the Hub](https://flowee.org/) [[src]](https://gitlab.com/FloweeTheHub) - a node supporting a suite of software focused on payment integration. C++
- [Bitcoin Verde](https://bitcoinverde.org/) [[src]](https://github.com/softwareverde/bitcoin-verde) [[docs]](https://explorer.bitcoinverde.org/documentation/) - java implementation with the goal of being interoperable with mining nodes.
- [Knuth](https://kth.cash/) [[src]](https://github.com/k-nuth/kth) - a high performance implementation of the Bitcoin protocol focused on applications needing extra capacity and resilience.
- [bchd](https://bchd.cash/) [[src]](https://github.com/gcash/bchd) [[docs]](https://github.com/gcash/bchd/tree/master/docs) - alternative implementation written in Go (golang)

### Developer Resources

- [Bitcoin Cash Research](https://bitcoincashresearch.org/) - Site dedicated to technical research on Bitcoin Cash.
- [Bitcoin Cash Discussions](https://bitcoincashnetworkdiscussions.org/) [[youtube]](https://www.youtube.com/channel/UCmyoHmbSsChInLzZ9S5aAAw) - Site for hosting live meetings and discussions about protocols

## Open-Source Teams Building on Bitcoin Cash

> If you want to go fast, go alone. If you want to go far, go together.
>
> -- An African Proverb.

There are various groups developing software stacks & apps for the broader ecosystem.

- [General Protocols](https://GeneralProtocols.com) [[repos]](https://gitlab.com/GeneralProtocols) - Team researching and developing protocols for non-custodial and trustless networks using BitBox. (Typescript and Javascript)
- [Electron Cash](https://electroncash.org/) [[repos]](https://github.com/Electron-Cash/) - Team maintaining a desktop SPV wallet with plugins and mobile app (Python)
- [Flowee](https://flowee.org) [[repos]](https://gitlab.com/FloweeTheHub) - Team maintaining a non-mining full node and services to access the Bitcoin Cash network. (C++, NodeJs et al)
- [Bitcoin.com](https://bitcoin.com) [[repos]](https://github.com/Bitcoin-com) - Prolific group developing webapps, mobile apps, and new tooling, deployed at bitcoin.com. (Typescript with some Javascript et al.)
- [FullStack Cash](https://fullstack.cash/) [[repos]](https://github.com/Permissionless-Software-Foundation) - Team building web/ipfs apps based on BitBox compatible stack. (Javascript)

## Testnet 4

- [Announcement](https://read.cash/@bitcoincashnode/bch-testnet4-for-may-2022-network-upgrade-95a21d51), [Explorer](https://testnet4.imaginary.cash/)

## Simple Payment Verification (SPV)

- [Fulcrum](https://github.com/cculianu/Fulcrum) - A fast & nimble SPV Server for Bitcoin Cash.
- [ElectrsCash](https://github.com/BitcoinUnlimited/ElectrsCash) - Electron Cash Server, rust implementation.

## Simple Ledger Protocol (SLP Token)

### Protocols

- Simple Ledger Protocol (SLP) [[specs]](https://slp.dev) - for handling ERC-20 style tokens.
- [Simple Ledger Postage Protocol](https://github.com/simpleledger/slp-specifications/blob/master/slp-postage-protocol.md) - Protocol for sending SLP tokens without BCH "gas".

### Libraries

- [Simple Ledger](https://simpleledger.cash/) [[repos]](https://github.com/simpleledger) - Group leading SLP token integration. (Typescript & Python)
- SLP Indexer [[src]](https://github.com/Permissionless-Software-Foundation/psf-slp-indexer)
- [SLP Explorer](https://simpleledger.info/) [[src]](https://github.com/salemkode/slp-explorer) [[backend src]](https://github.com/salemkode/slp-explorer-backend) - Slp explorer for bitcoin cash.
- [SLPDB](https://slpdb.fountainhead.cash/explorer) [[src]](https://github.com/simpleledger/SLPDB) [[doc]](https://slp.dev/tooling/slpdb/) - simpleledger indexer
- [gs++](https://gs.fountainhead.cash/) [[src]](https://github.com/blockparty-sh/cpp_slp_graph_search) [[doc]](https://gs.fountainhead.cash/swagger.html) - a fast SLP indexer, validator, and graph search server.
- [SLP Stream](https://slpstream.fountainhead.cash/channel) [[src]](https://github.com/blockparty-sh/slpstream) [[doc]](https://slp.dev/tooling/slpstream/) - a frontend API for GS++ that provides a streaming output of new transactions.
- [goslp](https://github.com/simpleledgerinc/goslp) - SLP go libraries.
- [SLP Indexer](https://github.com/Bitcoin-com/slp-indexer) - bitcoin.com indexer.
- [SLP Icons](https://github.com/kosinusbch/slp-token-icons) - Hosted icons for slp tokens.

## Libraries & SDKs

- [Developer tools](https://bch.info/en/developers) - Page devoted to high level developer tools.

### Language Agnostic

- [mainnet](https://mainnet.cash/) [[tutorial]](https://mainnet.cash/tutorial/) [[rest spec]](https://rest-unstable.mainnet.cash/api-docs/#/) - Typescript library, also available via rest api, or over rest from [python](https://github.com/mainnet-cash/mainnet-python-generated), [golang](https://github.com/mainnet-cash/mainnet-go-generated), [php](https://github.com/mainnet-cash/mainnet-php-generated) generated clients, [et. al](https://mainnet.cash/tutorial/other-languages.html)
- [Insomnia](https://insomnia.fountainhead.cash/) [[src]](https://github.com/fountainhead-cash/insomnia) - Swagger/OpenAPI3 specification for ElectrumX
- [BitBox OpenAPI 3 (Swagger) spec](https://github.com/Bitcoin-com/rest.bitcoin.com/tree/master/swaggerJSONFiles) - for rest.bitcoin.com see: [openapi-generator](https://github.com/OpenAPITools/openapi-generator)

### Typescript

- [PayButton](https://paybutton.org/) [[src]](https://github.com/PayButton/paybutton) - Front end library that makes it easier to accept Bitcoin Cash by adding a buy button.
- [Libauth](https://libauth.org/) [[src]](https://github.com/bitauth/libauth) - an ultra-lightweight, zero-dependency library for Bitcoin Cash and Bitauth applications. (Formerly `bitcoin-ts`.)
- [electrum-cash](https://gitlab.com/GeneralProtocols/electrum-cash) [[docs]](https://gitlab.com/GeneralProtocols/electrum-cash) [[tutorials]](https://read.cash/c/electrum-cash-f45e) - JavaScript library that lets you connect with one or more Electrum servers.
- [flowee-js](https://flowee.org/floweejs/) [[docs]](https://flowee.org/docs/) [[src]](https://gitlab.com/FloweeTheHub/floweejs/) - Bindings for using Flowee applications and libraries with the NodeJS JavaScript engine.
- [mainnet-js](https://mainnet.cash/) [[src]](https://github.com/mainnet-cash/mainnet-js) - Typescript library, also available over rest.
- [bchd grpc web-client](https://github.com/simpleledgerinc/grpc-bchrpc-web) - protobuf based javascript client for interacting with bchd full nodes.

### Javascript

- [bch-js](https://github.com/Permissionless-Software-Foundation/bch-js) [[docs]](https://bchjs.fullstack.cash/)
- [electrum-cli](https://github.com/rkalis/electrum-cli) - Super simple command line electrum client.
- [signup.cash](https://signup.cash/) [[src]](https://github.com/signupcash/signup-core) - Non-custodial platform as a service for building decentralized apps.
- [bitcore-lib-cash](https://github.com/bitpay/bitcore/tree/master/packages/bitcore-lib-cash) - javaScript library, maintained by bitpay.

### Python

- [bitcash](https://pybitcash.github.io/bitcash/) [[src]](https://github.com/pybitcash/bitcash) - python3 library.
- [bchd python bindings](https://github.com/gcash/bchd/tree/master/bchrpc/pb-py) - sample protobuf based python client for bchd.
- [jtoomim/p2pool](https://github.com/jtoomim/p2pool) - jtoomim fork of bitcoin pool mining software.

### Java

- [bitcoincashj](https://github.com/pokkst/bitcoincashj) - Bitcoin Cash library for Java

### C

- [Breadwallet Core](https://github.com/breadwallet/breadwallet-core) - SPV bitcoin C library.

### PHP

- [cashp](https://github.com/Ekliptor/cashp) - Library for BCH and SLP tokens.

### R

- [rbch](https://cran.r-project.org/package=rbch) - Extraction and Statistical Analysis of Data from the BCH Blockchain

# Podcasts, News & Media

Bitcoin Cash focussed media and content.

## The Bitcoin Cash Podcast

- [The Bitcoin Cash Podcast](https://www.bitcoincashpodcast.com) - Available on Youtube [[src]](https://www.youtube.com/channel/UCsrDsJnHFnkMnJhEslofyPQ) and RSS [[src]](https://rss.com/podcasts/bitcoincashpodcast/) audio versions, plus other video and podcast platforms (see links at bottom of website).
