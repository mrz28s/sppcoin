


SPP-Coin

Copyright (c) 2014 SPP-Coin Developers
Copyright (c) 2013-2014 hyperstake Developers
Copyright (c) 2013 NovaCoin Developers
Copyright (c) 2011-2012 Bitcoin Developers
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
SPP-Coin is a free open source project derived from NovaCoin, with
the goal of providing a long-term energy-efficient Proof of Stake based crypto-currency.
Built on the foundation of Bitcoin and NovaCoin, innovations such as proof-of-stake
help further advance the field of crypto-currency.

Setup
-----
Unpack the files into a directory and run:
 bin/32/sppcoind (headless, 32-bit)
 bin/64/sppcoind (headless, 64-bit)

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 

18675 (TCP) to your computer so you can receive
incoming connections.  sppcoin works without incoming connections,
but allowing incoming connections helps the sppcoin network.


Upgrade
-------
All you existing coins/transactions should be intact with the upgrade.
To upgrade first backup wallet
sppcoind backupwallet <destination_backup_file>
Then shutdown sppcoind by
sppcoind stop
Start up the new sppcoind.


See the sppcoin site:
  http://sppcoindesign.wixsite.com/sppcoin
for help and more information.

### Wallet themes

| HyperBlue     | PoloniexNight | PoloniexDay   |
| ------------- | ------------- | ------------- |
| [![HyperBlue](https://github.com/zeewolfik/SPP-Coin/raw/master/src/qt/res/screenshots/sppcoin-hyperblue-theme-th.png)](https://github.com/zeewolfik/SPP-Coin/raw/master/src/qt/res/screenshots/sppcoin-hyperblue-theme.png) | [![PoloniexNight](https://github.com/zeewolfik/SPP-Coin/raw/master/src/qt/res/screenshots/sppcoin-poloniexnight-theme-th.png)](https://github.com/zeewolfik/SPP-Coin/raw/master/src/qt/res/screenshots/sppcoin-poloniexnight-theme.png) | [![PoloniexNight](https://github.com/zeewolfik/SPP-Coin/raw/master/src/qt/res/screenshots/sppcoin-poloniexday-theme-th.png)](https://github.com/zeewolfik/SPP-Coin/raw/master/src/qt/res/screenshots/sppcoin-poloniexday-theme.png) |



