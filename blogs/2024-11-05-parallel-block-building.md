---
title: "Parallel block building"
url: "https://writings.flashbots.net/parallel-builder"
date: "2024-11-05"
feed_url: "https://writings.flashbots.net/rss.xml"
---
We introduce a new approach to block building called parallel block building. Instead of treating all transactions as potentially conflicting - as traditional sequential building algorithms do - parallel block building recognizes that most transactions in a block are actually independent. When a user swaps ETH for USDC, it doesn't affect someone minting an NFT - so why process them sequentially?
