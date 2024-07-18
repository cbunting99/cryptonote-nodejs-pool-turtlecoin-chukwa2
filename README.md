# cryptonote-nodejs-pool-turtlecoin-chukwa2
======================

#### This pool is now operating on this website:
Turtlecoin Pool
* https://allcoinspool.com/
* [GitHub Issues](https://github.com/masterprogrammer513/cryptonote-nodejs-pool-turtlecoin-chukwa2/issues)
* [Telegram Group](https://t.me/AllCoinsPool)
* [Discord Group](https://discord.gg/kZb5VbrSnS)

High performance Node.js (with native C addons) mining pool for CryptoNote based coins. Comes with lightweight example front-end script which uses the pool's AJAX API. Support for Cryptonight (Original, Monero v7, Stellite v7), Cryptonight Light (Original, Aeon v7, IPBC) Cryptonight Fast (Electronero/Crystaleum), and Cryptonight Heavy (Sumokoin) algorithms.

#### Please read Turtlecoin Section 
* New API for TurtleCoin daemon
* New API for TurlteCoin Wallet
* New config file with discord support
* Default config file work with TRTL

#### Table of Contents
* [Features](#features)
* [Usage](#usage)
  * [Requirements](#requirements)
  * [Downloading & Installing](#1-downloading--installing)
  * [Configuration](#2-configuration)
  * [Starting the Pool](#3-start-the-pool)
  * [Host the front-end](#4-host-the-front-end)
  * [Customizing your website](#5-customize-your-website)
  * [SSL](#ssl)
  * [Upgrading](#upgrading)
* [JSON-RPC Commands from CLI](#json-rpc-commands-from-cli)
* [Monitoring Your Pool](#monitoring-your-pool)
* [Community Support](#community--support)
* [Pools Using This Software](#pools-using-this-software)
* [Referral Links](#referral-links)
* [Donations](#donations)
* [Credits](#credits)
* [License](#license)


INFO
===
Most of the pools on this github are from years ago. Most have been installed on Ubuntu 20.04. 

Below is what was used to get the pool installed.

```
sudo apt-get install build-essential libboost-all-dev -y
sudo apt-get install libsodium-dev libgmp3-dev node-gyp libssl-dev -y

sudo apt-get update
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
source ~/.profile
nvm install 14.0.0
sudo apt-get install redis-server

git clone https://github.com/cbunting99/cryptonote-nodejs-pool-turtlecoin-chukwa2.git pool
cd pool
npm update
```