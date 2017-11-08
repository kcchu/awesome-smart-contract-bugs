# Awesome Smart Contract Bugs

A list of security bugs with smart contracts on Ethereum. ([original source](https://www.reddit.com/r/ethereum/comments/4omdlf/to_kickstart_the_building_safer_smart_contracts/))

 1. The DAO
 1. The "payout index without the underscore" ponzi ([FirePonzi](https://www.reddit.com/r/ethereum/comments/4e5y30/live_example_of_underhanded_solidity_coding_on/))
 1. The casino with a [public RNG seed](http://martin.swende.se/blog/Breaking_the_house.html)
 1. [Governmental](https://www.reddit.com/r/ethereum/comments/4ghzhv/governmentals_1100_eth_jackpot_payout_is_stuck/) (1100 ETH stuck because payout exceeds gas limit)
 1. [5800 ETH swiped](https://www.reddit.com/r/MakerDAO/comments/4niu10/critical_ether_token_wrapper_vulnerability_eth/) (by whitehats) from an ETH-backed ERC20 token
 1. The [King of the Ether game](http://www.kingoftheether.com/postmortem.html)
 1. Rubixi : Fees stolen because the [constructor function](https://etherscan.io/address/0xe82719202e5965Cf5D9B6673B7503a3b92DE20be#code) had an incorrect name, allowing [anyone to become the owner](https://bitcointalk.org/index.php?topic=1400536.60)
 1. Rock paper scissors [trivially cheatable](https://www.reddit.com/r/ethtrader/comments/4fpn6o/play_rockpaperscissors_for_1_eth_via_mist_wallet/) because the first to move shows their hand
 1. The [Parity Wallet Hack](https://blog.zeppelin.solutions/on-the-parity-wallet-multisig-hack-405a8c12e8f7) caused by missing checks before overwriting wallet owner.
 1. The [Parity Wallet Hack Again](https://blog.zeppelinos.org/parity-wallet-hack-reloaded/amp/) because anyone can take ownership of the library contract.
