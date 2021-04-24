# ERC777 Token Transfer Contracts

Run
``` bash
npm install
```
to setup.

And after that, change `node_modules/@openzeppelin/contracts/token/ERC777/ERC777.sol` line33 to
``` solidity
IERC1820Registry constant internal _ERC1820_REGISTRY = IERC1820Registry(0x88887eD889e776bCBe2f0f9932EcFaBcDfCd1820);
```
Address of ERC1820 on Conflux is different from that of Ethereum. 
