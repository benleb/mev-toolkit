# ⛓🕹 mev toolkit


<br>

<p align="center">
<img src="https://user-images.githubusercontent.com/1130416/210285135-2d0c3965-a3cd-44f7-a167-3ec14a9ad695.png" width="50%" align="center" style="padding:1px;border:1px solid black;"/>
 </p>


<br>

## tl; dr

<br>

##### 👾 maximal extractable value (MEV) encompasses the profits generated by participant parties in the block production supply chain. for searchers, this revenue can be generated from arbitrage when reducing the price spread between markets, slippage loss of swap users, frontrunning users' transactions, among other [strategies](MEV_strategies).

##### 👾 the public discussion around MEV started by [pmcgooohan](https://twitter.com/pmcgoohancrypto?lang=en) on [e/ethereum](https://www.reddit.com/r/ethereum/comments/2d84yv/miners_frontrunning/), and it was formalized by [phildaiann et. al](https://twitter.com/phildaian)'s paper [flash boys 2.0](https://arxiv.org/abs/1904.05234). 

##### 👾 MEV extraction can be a force of good in a non-predatory and [fair](https://twitter.com/bertcmiller/status/1456346690164768770) blockspace free-market as an incentive for economic security. every actor in the supply chain is relevant. order flow toxicity is a trader's exposure to counter-parties that possess private informational advantages. as everything in life, *[the most valuable commodity is information](https://frontier.tech/a-new-game-in-town)*.

##### ⚠️ this repository is a catalog from my own (free time / out-of-curiosity) research, enjoy at your own risk.


<br>


---


### extraction strategies

<br>

##### atomic (tx ordering)

* [sniping](MEV_strategies/sniping)
* [longtails](MEV_strategies/longtails)
* [atomic arbs](MEV_strategies/atomic_arb)
* [sandwiches](MEV_strategies/sandwich)
* [flashloans](MEV_strategies/flashloans)
* [jit liquidity](MEV_and_trading/protocols/uniswap/uniswap-v3/just-in-time.md)
* [liquidations](MEV_strategies/liquidations)
* [frontrunning](MEV_strategies/frontrunning)
* [backrunning](MEV_strategies/backrunning)


##### statistical (informed signal)


* [order flows](MEV_searchers/order_flows)
* [statistical arbs](MEV_strategies/stat_arbs)
* [defi and trading](MEV_and_trading)
* [cross-domain mev](MEV_searchers/cross_domain_mev)
* [oracles and twamm](MEV_strategies/oracles)


<br>

### mev by chains

* [mev on solana](MEV_by_chains/MEV_on_Solana)
* [mev on cosmos](MEV_by_chains/MEV_on_Cosmos)
* [mev on polygon](MEV_by_chains/MEV_on_Polygon)
* [mev on arbitrum](MEV_by_chains/MEV_on_Arbitrum)
* [mev on ethereum](MEV_by_chains/MEV_on_Ethereum)
* [mev on optimism](MEV_by_chains/MEV_on_Optimism)
* [mev on bsc chain](MEV_by_chains/MEV_on_BSC)
* [mev on avalanche](MEV_by_chains/MEV_on_Avalanche)


<br>

### building a toolkit

<br>

* [order flows](MEV_searchers/order_flows)
* [mev projects](MEV_projects)
* [build your mev bot](MEV_searchers)
* [data and analytics](MEV_searchers/data_and_analytics)
* [latency optimization](MEV_searchers/latency)
* [mempools monitoring](MEV_searchers/mempool_monitoring)
* [tx and signature explorers](MEV_searchers/tx_and_signature_explorers)
* [read papers from the past](MEV_projects/history.md)

<br>
