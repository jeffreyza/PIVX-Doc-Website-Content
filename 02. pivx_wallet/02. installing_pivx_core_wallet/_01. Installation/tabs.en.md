---
title: 'Install Tabs'
date: '01-08-2014 00:00'
slug: install-tabs
taxonomy:
    category:
        - 'PIVX Core Wallet'
    author:
        - 'The PIVX Team'
        
tabitems:
  - name: linux
    title: "Linux"
    content: "
    1. Navigate to the folder where you want to install the PiVX Core Wallet (for example **cd /home/pivx/pivx**)\n
    2. Download the latest version of the Core Wallet: **wget https://github.com/PIVX-Project/PIVX/releases/download/v5.3.0/pivx-5.3.0-xxx** (link from pivx.org website) \n
    3. Unzip the archive: **tar -zxvf pivx-5.3.0-aarch64-linux-gnu.tar.gz && sudo rm -f pivx-5.3.0-aarch64-linux-gnu.tar.gz** \n
    4. Navigate to the newly created folder **cd pivx-5.3.0**\n
    5. *First install only:* Install the Sapling parameters (Keys securing Shield transactions) by running the command **./install-params.sh** \n
    6. Launch the PiVX server **./pivxd -daemon**, or the PiVX GUI client: **./pivx-qt** \n"
  - name: windows
    title: "Windows"
    content: "
    1. Download the latest version of the Core Wallet from https://pivx.org/downloads \n
    2. Run the installer and follow all steps.\n
    3. Launch the PiVX Core Wallet.\n"
  - name: macos
    title: "MacOS"
    content: "
    1. Download the latest version of the Core Wallet from https://pivx.org/downloads \n
    2. Run the installer and Copy the PiVX App to Applications folder.\n
    3. Launch the PiVX Core Wallet.\n"
    
---

