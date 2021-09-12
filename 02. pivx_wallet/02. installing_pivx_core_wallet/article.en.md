---
title: 'Installing the PIVX Core Wallet'
date: '01-08-2014 00:00'
slug: installing-the-pivx-core-wallet
taxonomy:
    category:
        - 'PIVX Core Wallet'
    author:
        - 'The PIVX Team'
---

downloading, versions, upgrades, system requirements etc.

* How-to
* Security Considerations
* Downloading the wallet
* Installation
* Startup / initial synchronisation

cd ~ && wget https://github.com/PIVX-Project/PIVX/releases/download/v5.3.0/pivx-5.3.0-Which.ever.one.is.right.for.your.pc

tar -zxvf pivx-5.3.0-aarch64-linux-gnu.tar.gz && sudo rm -f pivx-5.3.0-aarch64-linux-gnu.tar.gz


So before you enter "bin" there should be a file name "install-params.sh"
You need to execute that first.  "./pivx-params.sh"

./pivxd -daemon

./pivx-cli help



