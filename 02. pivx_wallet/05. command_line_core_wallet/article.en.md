---
title: 'PIVX Command Line Core Wallet'
date: '01-08-2014 00:00'
slug: command-line-core-wallet
taxonomy:
    category:
        - 'PIVX Core Wallet'
    author:
        - 'The PIVX Team'
---

### Command Line Core Wallet

The process to launch the PIVX Core Wallet in command line is called pivxd and can be found in the bin folder of the pivx core wallet.

The base command to launch the pivx core wallet is:

	```
	pivx-5.3.0/bin/pivxd -daemon
	```

The pivxd process accepts multiple command line options, that can be listed (along with their description) using the following command:

	```
	pivxd --help
	```

When no options are specified, the pivxd process will use default values for all parameters (such as date folder, log file, etc.).




