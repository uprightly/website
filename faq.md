---
layout: page
title: FAQ
permalink: /faq/
---

# Frequently Asked Questions

## Can't somebody create multiple accounts and make tons of fake positive reviews for themselves?
Yes, in general it is cheap and easy to create positive reviews. So this system is vulnerable to a [Sybil Attack](https://en.wikipedia.org/wiki/Sybil_attack) with regard to positive reviews. Negative reviews and Reputation funds are not susceptible to such an attack because they have financial costs and other safeguards that would be difficult to manipulate in this manner.

Because of this risk, the main determining factors in the reputation "score" of an address would be the Reputation Fund value of an address as well as any negative reviews that were received. Positive reviews are nice, of course, but do not carry much weight since they are easily acquirable (by design.) The incentives are purposefully aligned to encourage participants to cooperate even during a dispute in order to not gain a negative review. This trade-off is acceptable due to the increased likelihood of positive outcomes.

## What is to stop somebody from just creating a new address after they scam someone?

The Reputation Fund. If a user has invested a considerable sum of money into his/her Reputation Fund, they are unlikely to abandon it! Of course, they could abandon it and start a new address, but it would be costly since they would have to start from zero with no reputation at all. For this reason, it is probably not a good idea to do business with someone who has a low Reputation Fund value because they cannot be trusted to stand by their address' reputation.

## What is "burning?"

Burning is the act of destroying cryptocurrency in a public and irreversible way. A simple example of this is when a user sends currency to an invalid address (0x0, for instance.) Everybody can see that this user ‘burned’ the token by sending it to an invalid address, and it is a signal to the public that this person has ‘invested’ 1 token into their address. In addition, it is an act of goodwill to the rest of the network because it effectively reduces the supply of the token, increasing the value of everyone else’s tokens. Somebody who has burned a lot of money on a certain address is basically saying, “I care about the reputation of this address and I invested money into its good name.”

In the context of Uprightly, users burn UPT tokens when they send them to the Uprightly reputation contract because the contract is written in such a way that there is no functionality to send the tokens back outside the contract.

## What if the UPT token varies widely in price?

This is a possibility with any cryptocurrency. If UPT were to rise in price sharply, all users would benefit from a more valuable Reputation Fund. If UPT declined, users would be hit with a declining Reputation Fund, but would be incentivized to buy more tokens at this point to protect their Reputation Fund. This may actually cause the price of the token to remain relatively stable compared to a token that was purely at the whims of speculation.

## Do I have to burn my tokens immediately?

No. You can hold them like any other ERC20 token. When you decide to invest them into the Uprightly protocol is when they are burned.

## Can I transfer my Reputation Fund (burned tokens) to another address?

No. The protocol does not allow for transferring of Reputation Funds between addresses. This is a key component of how the system works. It is to incentive users to continue using the same address that they invested in. If transfers were allowed, the Reputation Fund functionality would not have any value because a bad actor could simply transfer their Reputation Fund to a different address.
