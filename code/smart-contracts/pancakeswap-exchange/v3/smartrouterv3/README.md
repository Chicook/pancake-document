# SmartRouterV3

### Contract Info

BSC Address: `0x13f4EA83D0bd40E75C8222255bc855a974568Dd4`

Ethereum Address: `0x13f4EA83D0bd40E75C8222255bc855a974568Dd4`

BSC testnet Address: `0x9a489505a00cE272eAa5e07Dba6491314CaE3796`

Goerli Address: `0x9a489505a00cE272eAa5e07Dba6491314CaE3796`

{% hint style="info" %}
### Notice

At the very end of all swaps via router, `refundETH` should be called. PancakeSwap will ensure this.
{% endhint %}

### Audits

### API

#### constructor

`constructor(address _factoryV2, address _deployer, address _factoryV3, address _positionManager, address _stableFactory, address _stableInfo, address _WETH9) public`
