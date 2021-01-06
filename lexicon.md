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
{: .no_toc }

There's a separate public/private keypair for every bitcoin address.  You don't have a single private key that unlocks everything.  Bitcoin addresses are a 160-bit hash of the public key, everything else in the system is 256-bit.

### [Re: Repost: How anonymous are bitcoins?](/docs/forum/bitcoin-forum/7)
{: .no_toc }

Bitcoins are sent to and from bitcoin addresses, which are essentially random numbers with no identifying information.

## Banks

### [Re: Bitcoin open source implementation of P2P currency](/docs/emails/p2p-research/1/)
{: .no_toc }

The central bank must be trusted not to debase the currency, but the history of fiat currencies is full of breaches of that trust. Banks must be trusted to hold our money and transfer it electronically, but they lend it out in waves of credit bubbles with barely a fraction in reserve. We have to trust them with our privacy, trust them not to let identity thieves drain our accounts. Their massive overhead costs make micropayments impossible.

## Micropayments

### [Bitcoin open source implementation of P2P currency](/docs/forum/p2p-foundation/1)
{: .no_toc }

Banks must be trusted to hold our money and transfer it electronically, but they lend it out in waves of credit bubbles with barely a fraction in reserve. We have to trust them with our privacy, trust them not to let identity thieves drain our accounts. Their massive overhead costs make micropayments impossible.

## Nodes

### [Re: More BitCoin questions](docs/emails/mike-hearn/12/)
{: .no_toc }

As things have evolved, the number of people who need to run full nodes is less than I originally imagined.  The network would be fine with a small number of nodes if processing load becomes heavy.

## Privacy

### [Bitcoin: A Peer-to-Peer Electronic Cash System](/docs/whitepaper/en/)
{: .no_toc }

The traditional banking model achieves a level of privacy by limiting access to information to the parties involved and the trusted third party. The necessity to announce all transactions publicly precludes this method, but privacy can still be maintained by breaking the flow of information in another place: by keeping public keys anonymous. The public can see that someone is sending an amount to someone else, but without information linking the transaction to anyone. This is similar to the level of information released by stock exchanges, where the time and size of individual trades, the "tape", is made public, but without telling who the parties were.

### [Bitcoin: A Peer-to-Peer Electronic Cash System](/docs/whitepaper/en/)
{: .no_toc }

As an additional firewall, a new key pair should be used for each transaction to keep them from being linked to a common owner. Some linking is still unavoidable with multi-input transactions, which necessarily reveal that their inputs were owned by the same owner. The risk is that if the owner of a key is revealed, linking could reveal other transactions that belonged to the same owner.

### [Re: Repost: How anonymous are bitcoins?](/docs/forum/bitcoin-forum/7)
{: .no_toc }

For greater privacy, it's best to use bitcoin addresses only once.

### [Re: Repost: How anonymous are bitcoins?](docs/forum/bitcoin-forum/41/)

Bitcoin is still very new and has not been independently analysed. If you're serious about privacy, TOR is an advisable precaution.

### [Re: Repost: How anonymous are bitcoins?](docs/forum/bitcoin-forum/41/)

You could use TOR if you don't want anyone to know you're even using Bitcoin.

## Scaling

### [Bitcoin P2P e-cash paper](/docs/emails/cryptography/2)
{: .no_toc }

At first, most users would run network nodes, but as the network grows beyond a certain point, it would be left more and more to specialists with server farms of specialized hardware. A server farm would only need to have one node on the network and the rest of the LAN connects with that one node.

### [Bitcoin P2P e-cash paper](/docs/emails/cryptography/2)
{: .no_toc }

The bandwidth might not be as prohibitive as you think. A typical transaction would be about 400 bytes (ECC is nicely compact). Each transaction has to be broadcast twice, so lets say 1KB per transaction. Visa processed 37 billion transactions in FY2008, or an average of 100 million transactions per day. That many transactions would take 100GB of bandwidth, or the size of 12 DVD or 2 HD quality movies, or about $18 worth of bandwidth at current prices.

### [Re: Questions about BitCoin](/docs/emails/mike-hearn/1)
{: .no_toc }

The existing Visa credit card network processes about 15 million Internet purchases per day worldwide.  Bitcoin can already scale much larger than that with existing hardware for a fraction of the cost.  It never really hits a scale ceiling.
