---
title: Designating a Beneficiary for Celo Validator Rewards 
description: Overview of designating a beneficiary to receive a fraction of Validator Rewards
slug: /celo-codebase/protocol/proof-of-stake/epoch-rewards/validator-rewards-beneficiary
---

# Validator Rewards Beneficiary

Overview of how to designate a beneficiary and share a fraction of Validator rewards.

___

Validators can choose to share a fraction of rewards by designating a beneficiary.

## Setting a Beneficiary

WIP: The celocli can be used to designate a beneficiary. This could be an individual account or a smart contract.

```text
USAGE
  $ celocli account:set-payment-delegation --beneficiary ADDRESS --fraction .1

OPTIONS
  --from=0xc1912fEE45d61C87Cc5EA59DaE31190FFFFf232d     
                                                    (optional) Address of the account
                                                    to designate as beneficiary

  --beneficiary=0xc1912fEE45d61C87Cc5EA59DaE31190FFFFf232d  
                                                    (required) Address of the 
                                                    beneficiary account

  --fraction=0.1                                    (required) The fraction of rewards to 
                                                    delegate

```

```text
EXAMPLE
  celocli account:set-payment-delegation --beneficiary ADDRESS --fraction .1
```

## Example Projects

WIP: The Spirals Protocol allows... 
WIP: Impact Markets

