---
title: 'Core Wallet Best Practices / FAQ'
date: '01-08-2014 00:00'
slug: core-wallet-faq
taxonomy:
    category:
        - 'PIVX Core Wallet'
    author:
        - 'The PIVX Team'


faqitems:
  - generic:
    sectiontitle: Generic Questions
    questions:
      - question: "Generic Question 1"
        response: "Response to generic question 1"
      - question: "Generic Question 2"
        response: "Response to generic question 2"
      - question: "Generic Question 3"
        response: "Response to generic question 3"
  - corewallet:
    sectiontitle: Core Wallet
    questions:
      - question: "Core Wallet 1"
        response: "Response to Core Wallet question 1"
      - question: "Core Wallet 2"
        response: "Response to Core Wallet question 2"
      - question: "Core Wallet 3"
        response: "Response to Core Wallet question 3"
  - issues:
    sectiontitle: Blockchain Synchronisation Issues
    questions:
      - question: "My wallet has stopped syncing at block xxx. How can I fix it?"
        response: "The first step is to confirm whether you are on the right chain. To do so, follow the following steps:\n
        * Run the **getbestblockhash** command in the debug console\n
        * Check whether that block is available on the PIVX explorer: https://explorer.pivx.link/\n
        * If it is not available there, your core wallet is on a forked chain, and needs to be resynced from scratch (see below for steps)"
      - question: "How did my Core Wallet end up being on a forked chain?"
        response: "There are a few possibilities, among which:\n
        * Connecting to 'bad' peers that veer you onto an orphan chain.\n
        * Having too few peers, making net consensus less reliable.\n
        * General connectivity issues (net speed, reliability)."
      - question: "How do I resync my core wallet from scratch?"
        response: "
        1. Stop the wallet.\n
        2. Make a backup of your wallet.dat file.\n
        3. Start the wallet.\n
        4. Go to Settings --> Debug --> Wallet Repair --> Delete local blockchain.\n
        5. Wait for resync to complete.\n
        
        Steps 3/4 can also be ran from the command line using: **pivxd -daemon -resync**"
---

### Core Wallet Best Practices FAQ


