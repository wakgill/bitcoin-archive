---
layout: default
title: Lexicon
nav_order: 15
search_exclude: true
---

# Satoshi Nakamoto Lexicon
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

- TOC
{:toc}

---

## Addresses

### [Re: Bitcoin Address Collisions](/docs/forum/bitcoin-forum/65)

There's a separate public/private keypair for every bitcoin address.  You don't have a single private key that unlocks everything.  Bitcoin addresses are a 160-bit hash of the public key, everything else in the system is 256-bit.

### [Re: Repost: How anonymous are bitcoins?](/docs/forum/bitcoin-forum/7)

Bitcoins are sent to and from bitcoin addresses, which are essentially random numbers with no identifying information.

## Banks

### [Re: Bitcoin open source implementation of P2P currency](/docs/emails/p2p-research/1/)

The central bank must be trusted not to debase the currency, but the history of fiat currencies is full of breaches of that trust. Banks must be trusted to hold our money and transfer it electronically, but they lend it out in waves of credit bubbles with barely a fraction in reserve. We have to trust them with our privacy, trust them not to let identity thieves drain our accounts. Their massive overhead costs make micropayments impossible.<br>

## Scaling

### [Bitcoin P2P e-cash paper](/docs/emails/cryptography/2)

At first, most users would run network nodes, but as the network grows beyond a certain point, it would be left more and more to specialists with server farms of specialized hardware. A server farm would only need to have one node on the network and the rest of the LAN connects with that one node.

### [Bitcoin P2P e-cash paper](/docs/emails/cryptography/2)

The bandwidth might not be as prohibitive as you think. A typical transaction would be about 400 bytes (ECC is nicely compact). Each transaction has to be broadcast twice, so lets say 1KB per transaction. Visa processed 37 billion transactions in FY2008, or an average of 100 million transactions per day. That many transactions would take 100GB of bandwidth, or the size of 12 DVD or 2 HD quality movies, or about $18 worth of bandwidth at current prices.

### [Re: Questions about BitCoin](/docs/emails/mike-hearn/1)

The existing Visa credit card network processes about 15 million Internet purchases per day worldwide.  Bitcoin can already scale much larger than that with existing hardware for a fraction of the cost.  It never really hits a scale ceiling.
