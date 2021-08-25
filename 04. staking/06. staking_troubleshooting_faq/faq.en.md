---
title: 'Troubleshooting Staking'
date: '01-08-2014 00:00'
slug: staking-faq
taxonomy:
    category:
        - 'Staking'
    author:
        - 'The PIVX Team'


faqitems:
  - generic:
    sectiontitle: Staking FAQ
    questions:
      - question: "Why is staking inactive on my core wallet?"
        response: "Please start with making sure you meet all requirements listed on that page [Staking](/staking). If this doesn't help, run the **getstakingstatus** command in the core wallet command line or debug console; any 'false' value should be investigated as they are likely the cause for staking to be de-activated."
      - question: "I have been staking X PIVs for Y days and haven't received a reward yet. Is anything broken?"
        response: "Verify the staking status of your core wallet/of your staking provider. If active, your next best option is to give it time, as the frequency on which a staker will receive rewards is completely random. The staking calculator on [https://pivx.org/proof-of-stake](https://pivx.org/proof-of-stake) will provide you with an expected return/staking frequency that can help manage your expectations."
      - question: "Generic Question 3"
        response: "Response to generic question 3"
  - hotstaking:
    sectiontitle: Hot Staking
    questions:
      - question: "Core Wallet 1"
        response: "Response to Core Wallet question 1"
  - coldstaking:
    sectiontitle: Cold Staking
    questions:
      - question: "I want to cold stake my PIVs but cannot maintain a hot wallet. Where do I find a staking provider?"
        response: "Some members of the community offer to cold stake PIVs on their wallet; you can ask on Discord whether someone is willing to do it for you. There are also specialized service providers (such as [allnodes.com](https://help.allnodes.com/en/articles/3684105-how-to-stake-pivx-on-allnodes)) who offer this service for a small fee or for free."
      - question: "I have delegated my PIVs for staking to a thirdparty. Can he access/spend my PIVs?"
        response: "No. Cold staking is a non-custodial staking delegation. Your PIVs are safe in your cold/offline wallet, and only you can access and spend them."
      - question: "How do I access/spend the PIVs that I have delegated for cold staking?"
        response: "Just login to your cold wallet and spend them! It will break the cold staking for the UTXO you are spending, so if you want to stake the remainder of that UTXO you will need to put in place a new staking delegation."
---

### Troubleshooting Staking FAQ


