# IHT Ethereum Token/Crowdsale Contract Source

This is a in process version of the IHT Token/Crowdsale contracts source.

## General Info about the IHT project

Information about [IHT project and product](http://ihtcoin.com/). Please subscribe to our [Telegram channel](https://t.me/IHTcoin) for the latest information about our crowdsale.

## Main contracts in this repository

* CrowdsaleToken - a ReleasableToken, MintableToken, UpgradeableToken, Burnable ERC20 contract
* MintedTokenCappedCrowdsale - a Mintable, Allocatable, Haltable crowdsale contract
* BonusFinalizeAgent - a finalize agent that tidy things up at end of crowdsale
* TokenTranchePricing - a pricing strategy that based on the amount of token invested that associated with this crowdsale
* Multisig - a “wallet” where the ether, raised by this crowdsale, is kept, and requires > 1 account to approve for transfer out - this is based on Zeppelin/Gnosis implementation

### Versioning

TBD

