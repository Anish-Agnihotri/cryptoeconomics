# TRC Token Standards
Tron's TRC (Tron Request for Comment) proposals are technical documents that define a set of rules used when implementing tokens for the Tron ecosystem.

## Common token standards

### TRC-10
The most commonly used Tron token standard is the TRC-10 token. It is a TRON system-level token, charcterized by the low resources consumed by transfers. TRC-10 token contracts are accessible by both smart contract and API, have a GUI for one-click coin offerings (ICO's), do not support decimals denominations, and have transaction fees ~1000 times lower than TRC-20.

**Note:** TRC-10 tokens are supported by TRON blockchain natively, **without** the TRON Virtual Machine (TVM).

Common examples of TRC-10 tokens include:

- [BitTorrent (BTT)](https://www.bittorrent.com/btt/): Utility token for use on the BitTorrent platform; Tokenized rewards for content creation and curation on the BitTorrent peer-to-peer network.

### TRC-20
The TRC-20 Tron smart-contract token standard is a developer-oriented implementation of tokens inspired largely by Ethereum's ERC-20 standard. TRC-20 tokens are divisible from `0` to `18` decimal places, fungible in nature, and on Tron, enabled interface customization.

**Note:** TRC‌-20 is a technical standard used for smart contracts on the TRON blockchain for implementing tokens **with the** TRON Virtual Machine (TVM).

Common examples of TRC-20 tokens include:

- [WINk](https://www.wink.org/): Token for use on the WINk gambling platform.

## Comparison: TRC-10 vs TRC-20
Tron's MainNet token standards are built to differentiate between consumer-oriented and developer-oriented specifications. A comparison between TRC-10 and TRC-20:

|**Features**   |**TRC-10**   |**TRC-20**   |
|---|---|---|
|Developers Learning Curve   |Easy  |Medium   |
|Interface Customization?   |No   |Yes   |
|Accessible by Smart Contract?   |Yes   |Yes   |
|Accessible by API?   |Yes   |No   |
|Lost Token Protection   |No   |No   |
|GUI for ICO   |Yes   |No   |
|Deposit from Contract Address   |No   |No   |
|Easy to track   |Easy — Built In   |Need a 3rd-party platform to track   |
|Decimal   |Not Supported   |Up to 18   |
|In Development   |TVM support is in development   |Compatible with ERC20   |
|Transaction Fee   |~ 1000 times lower than TRC20 (using API, not by smart contract)   |~ 1000 times (dynamic) higher than TRC10   |
|Transfer   |Can use API to transfer, but costs bandwidth points; transfer in smart contract costs both bandwidth points and energy.   |Energy & Bandwidth Points   |

*Table transcribed from [CoinGape](https://coingape.com/tron-trc10-trc20-token-standards/)*
