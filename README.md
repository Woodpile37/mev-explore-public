# Contribute to MEV-Explore

Hey! Thanks for your interest in contributing to MEV-Explore. T

For starters, we recommend you to join our [Discord](https://discord.gg/7hvTycdNcK) and the #MEV-Explore channel in there, and to check out MEV-Explore's [Metholodogy](https://explore.flashbots.net/methodology) page for an explanation of how we've arrived at this dashboard and our data collection process.

## Relevant repos to MEV-Explore
The repos in the Flashbots organization connected to MEV-Explore are the following:

* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs)
* [sql](https://github.com/flashbots/sql)
* [mev-inspect-logs](https://github.com/flashbots/mev-inspect-logs)
* [mev-inspect-ts](https://github.com/flashbots/mev-inspect-ts)

## Ways to contribute

### Help us improve our protocol coverage by writing inspectors

Requirements: 
* proficiency in Rust or Javascript
* understanding of smart contract logic

Inspectors currently missing include:
* Swerve arbitrage
* Bancor arbitrage
* Kyber Network arbitrage
* DyDx liquidations
* Mooniswap arbitrage
* DODO arbitrage
* ESD/DSD incentivized frontrunning calls

Review our existing code for any mistakes in there or in the tests we do. Our code for MEV-Inspect exists mostly in Rust.

### Help us improve the quality of our data

Requirements:
* no specific coding skill required
* an understanding of value flow within a transaction

Our data collection approach is far from perfect and we need as much help we can get in spotting misclassified transactions. You can see some individual transactions we classify in the [Leaderboard](https://explore.flashbots.net/leaderboard) page of the dashboard.

There are several kinds of misclassified transactions:
* a transaction we've classified as MEV but that isn't
* a transaction that has a different revenue and/or tx_fee than the one we're showing for it

For any misclassified transaction you find, please open an issue on here for us to look at it, prune it from our db and add a filter to our crawlers to ignore similar transactions in the future or correct the calculation error.

## General feedback 

Requirements:
* don't be too harsh :(

As a user of MEV-Explore, help us improve it by suggesting new visualizations and metrics that would be useful to you, your project or your research group. You can do that in the ['Discussions'](link) tab of this repository so that others can join in.


## Resources

* [MEV-Explore dashboard](https://explore.flashbots.net)
* [MEV-Explore blogpost](link)
* [MEV-Inspect codebase](https://github.com/flashbots/mev-inspect-rs)
* [Flashbots PM repo](https://github.com/flashbots/pm)
* [Flashbots Discord](https://discord.gg/7hvTycdNcK)


⚡️🤖
