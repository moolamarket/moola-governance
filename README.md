# Moola Governance Repository

## template

```
---
mgp: <to be assigned>
title: <MGP title>
date-created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
status: <PROPOSED | TESTNET | MAINNET | REVERTED >
governance-proposal-id: [if submitted]
date-executed: [if executed] <date created on, in ISO 8601 (yyyy-mm-dd) format>
---
```

# Overview

MGP - Moola Governance Proposal

Pick a four digit number subsequent to the latest proposal raised and name your file.

## Status:

- PROPOSAL = proposed but not deployed to testnet yet
- TESTNET = after deployed to testnet
- MAINNET = after deployed to mainnet
- REVERTED = after revert transaction deployed

Describe the issue that motivates this MGP. It should indicate all parameters that are being changed and why doing so is important.
Explain what benefits the enhancement this change will bring. To the extent possible, enumerate use cases affected by this MGP.

# Proposed changes

1. Description of transaction 1

- Destination: A human readable description of the address and method being called
- Data: A human readable description of the transaction data
- Value: How much of which asset is being sent, and why?

# Verification

An explanation of how voters can verify that this MGP does what it intends to do. Can be left as “TODO” until the proposal is made.

# Risks

Highlight any risks and concerns that may affect consensus, proof-of-stake, governance, protocol economics, the stability protocol, security, and privacy.

# Useful Links

- Optional section
- Links to related documents (eg. if this is a proposal to point to a new instance of a smart contract that was updated)
