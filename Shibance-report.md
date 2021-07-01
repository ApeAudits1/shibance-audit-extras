 Sūrya's Description Report

 Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| shibance-contracts/shibance-core/ShibanceERC20.sol | 303d827e0082f3ab1273dc84d09aae018e01fbee |
| shibance-contracts/shibance-core/interfaces/IShibanceERC20.sol | 870d54449a1d68a684c7d550a6df212068959fdf |
| shibance-contracts/shibance-core/libraries/SafeMath.sol | 97a5b17b0fd90ece89930aeff76cc32fef1a6f14 |
| shibance-contracts/shibance-periphery/ShibanceRouter.sol | f5a18bc0c46b9e6a752669ece176d18d04366c48 |
| shibance-contracts/shibance-periphery/interfaces/IShibanceFactory.sol | ce5085a427a92003bfaabb50a004486d8f7981d1 |
| shibance-contracts/shibance-periphery/interfaces/IShibanceRouter02.sol | 0267975aff2b1945fff93cf2a594f410081c3755 |
| shibance-contracts/shibance-periphery/interfaces/IShibanceRouter01.sol | 28bc121729b792eaca4ca178c6325c23cec175c8 |
| shibance-contracts/shibance-periphery/libraries/ShibanceLibrary.sol | 14492fe290e9517e79b312138a8dac0ce9af75fc |
| shibance-contracts/shibance-periphery/interfaces/IShibancePair.sol | 1147da919df9208713e49aa3607cfdc6a1065746 |
| shibance-contracts/shibance-periphery/libraries/SafeMath.sol | 123c932c8701c1178d049c82339bc68cd3c61d18 |
| shibance-contracts/shibance-periphery/interfaces/IERC20.sol | b7d011aaabd34898ee60760996cb702e7b2ca855 |
| shibance-contracts/shibance-periphery/interfaces/IWETH.sol | 6a25dd53c8494e3aef3a520f17e00608b529f061 |
| shibance-contracts/shibance-periphery/interfaces/IShibanceMigrator.sol | c823469d28eddb822c236d27d87ff1ac5a4f1fd2 |
| shibance-contracts/shibance-farm/interfaces/IMasterBoi.sol | bf726f848e041d80c9528b15c8bf13c2517005b1 |
| shibance-contracts/shibance-farm/interfaces/IERC20.sol | a34e3e5dfb9756d2bfc276118132daaa0df1c88e |
| shibance-contracts/shibance-farm/MasterBoi.sol | f7cb04b1e91569e7859aa6f169fe4fa4c90d3d65 |
| shibance-contracts/shibance-farm/WoofToken.sol | 3abc31cb8a228f7cb5b951c803ce05b996057f2e |
| shibance-contracts/shibance-farm/DoggyPound.sol | 23647cd3b75a59fe7cfc646038a92772aea771c9 |
| shibance-contracts/shibance-farm/SupportBoi.sol | 52f5cfa4d7011d11dfeda0049098fac599a5b265 |
| shibance-contracts/shibance-farm/libs/Multicall.sol | 4a81a0cb88176dfbb30355dd6da4fe130b4a4a46 |
| shibance-contracts/shibance-farm/Timelock.sol | 886a311488a573bd2a6d6ea14d9654292a66af15 |
| shibance-contracts/shibance-core/interfaces/IShibanceCallee.sol | 4367f9f17e442652731af32db3a8cf06b736050a |
| shibance-contracts/shibance-core/interfaces/IShibancePair.sol | 2c2baebfa1b929f6a93c668d905e36612bb9d630 |
| shibance-contracts/shibance-core/interfaces/IShibanceFactory.sol | 97d5e2c9f1425973cc2b7cb418ef6ef07a112bed |
| shibance-contracts/shibance-core/interfaces/IERC20.sol | b7d011aaabd34898ee60760996cb702e7b2ca855 |
| shibance-contracts/shibance-core/ShibancePair.sol | 6db88ce967cf7e20819a71299f099d452415466a |
| shibance-contracts/shibance-core/libraries/Math.sol | e6f63d883294ea708b0ab5ecee646f9fcac6722c |
| shibance-contracts/shibance-core/libraries/UQ112x112.sol | 5c0f96357914f9f80b6d616b79ece099d5f91ec4 |
| shibance-contracts/shibance-core/ShibanceFactory.sol | 208f142aa7d14cb4fc3a4163ae22d3192e4c1fe4 |
| shibance-contracts/shibance-woofvault/WoofVault.sol | dab07da5ba7534ed75c6ec00a8a7a5871df86c10 |


 Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **ShibanceERC20** | Implementation | IShibanceERC20 |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | _mint | Internal 🔒 | 🛑  | |
| └ | _burn | Internal 🔒 | 🛑  | |
| └ | _approve | Private 🔐 | 🛑  | |
| └ | _transfer | Private 🔐 | 🛑  | |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | permit | External ❗️ | 🛑  |NO❗️ |
||||||
| **IShibanceERC20** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | DOMAIN_SEPARATOR | External ❗️ |   |NO❗️ |
| └ | PERMIT_TYPEHASH | External ❗️ |   |NO❗️ |
| └ | nonces | External ❗️ |   |NO❗️ |
| └ | permit | External ❗️ | 🛑  |NO❗️ |
||||||
| **SafeMath** | Library |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
||||||
| **ShibanceRouter** | Implementation | IShibanceRouter02 |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | _addLiquidity | Internal 🔒 | 🛑  | |
| └ | addLiquidity | External ❗️ | 🛑  | ensure |
| └ | addLiquidityETH | External ❗️ |  💵 | ensure |
| └ | removeLiquidity | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityETH | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHSupportingFeeOnTransferTokens | Public ❗️ | 🛑  | ensure |
| └ | removeLiquidityETHWithPermitSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | _swap | Internal 🔒 | 🛑  | |
| └ | swapExactTokensForTokens | External ❗️ | 🛑  | ensure |
| └ | swapTokensForExactTokens | External ❗️ | 🛑  | ensure |
| └ | swapExactETHForTokens | External ❗️ |  💵 | ensure |
| └ | swapTokensForExactETH | External ❗️ | 🛑  | ensure |
| └ | swapExactTokensForETH | External ❗️ | 🛑  | ensure |
| └ | swapETHForExactTokens | External ❗️ |  💵 | ensure |
| └ | _swapSupportingFeeOnTransferTokens | Internal 🔒 | 🛑  | |
| └ | swapExactTokensForTokensSupportingFeeOnTransferTokens | External ❗️ | 🛑  | ensure |
| └ | swapExactETHForTokensSupportingFeeOnTransferTokens | External ❗️ |  💵 | ensure |
| └ | swapExactTokensForETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  | ensure |
| └ | quote | Public ❗️ |   |NO❗️ |
| └ | getAmountOut | Public ❗️ |   |NO❗️ |
| └ | getAmountIn | Public ❗️ |   |NO❗️ |
| └ | getAmountsOut | Public ❗️ |   |NO❗️ |
| └ | getAmountsIn | Public ❗️ |   |NO❗️ |
||||||
| **IShibanceFactory** | Interface |  |||
| └ | feeTo | External ❗️ |   |NO❗️ |
| └ | feeToSetter | External ❗️ |   |NO❗️ |
| └ | getPair | External ❗️ |   |NO❗️ |
| └ | allPairs | External ❗️ |   |NO❗️ |
| └ | allPairsLength | External ❗️ |   |NO❗️ |
| └ | createPair | External ❗️ | 🛑  |NO❗️ |
| └ | setFeeTo | External ❗️ | 🛑  |NO❗️ |
| └ | setFeeToSetter | External ❗️ | 🛑  |NO❗️ |
||||||
| **IShibanceRouter02** | Interface | IShibanceRouter01 |||
| └ | removeLiquidityETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermitSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForTokensSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactETHForTokensSupportingFeeOnTransferTokens | External ❗️ |  💵 |NO❗️ |
| └ | swapExactTokensForETHSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
||||||
| **IShibanceRouter01** | Interface |  |||
| └ | factory | External ❗️ |   |NO❗️ |
| └ | WETH | External ❗️ |   |NO❗️ |
| └ | addLiquidity | External ❗️ | 🛑  |NO❗️ |
| └ | addLiquidityETH | External ❗️ |  💵 |NO❗️ |
| └ | removeLiquidity | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETH | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityETHWithPermit | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapTokensForExactTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactETHForTokens | External ❗️ |  💵 |NO❗️ |
| └ | swapTokensForExactETH | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForETH | External ❗️ | 🛑  |NO❗️ |
| └ | swapETHForExactTokens | External ❗️ |  💵 |NO❗️ |
| └ | quote | External ❗️ |   |NO❗️ |
| └ | getAmountOut | External ❗️ |   |NO❗️ |
| └ | getAmountIn | External ❗️ |   |NO❗️ |
| └ | getAmountsOut | External ❗️ |   |NO❗️ |
| └ | getAmountsIn | External ❗️ |   |NO❗️ |
||||||
| **ShibanceLibrary** | Library |  |||
| └ | sortTokens | Internal 🔒 |   | |
| └ | pairFor | Internal 🔒 |   | |
| └ | getReserves | Internal 🔒 |   | |
| └ | quote | Internal 🔒 |   | |
| └ | getAmountOut | Internal 🔒 |   | |
| └ | getAmountIn | Internal 🔒 |   | |
| └ | getAmountsOut | Internal 🔒 |   | |
| └ | getAmountsIn | Internal 🔒 |   | |
||||||
| **IShibancePair** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | DOMAIN_SEPARATOR | External ❗️ |   |NO❗️ |
| └ | PERMIT_TYPEHASH | External ❗️ |   |NO❗️ |
| └ | nonces | External ❗️ |   |NO❗️ |
| └ | permit | External ❗️ | 🛑  |NO❗️ |
| └ | MINIMUM_LIQUIDITY | External ❗️ |   |NO❗️ |
| └ | factory | External ❗️ |   |NO❗️ |
| └ | token0 | External ❗️ |   |NO❗️ |
| └ | token1 | External ❗️ |   |NO❗️ |
| └ | getReserves | External ❗️ |   |NO❗️ |
| └ | price0CumulativeLast | External ❗️ |   |NO❗️ |
| └ | price1CumulativeLast | External ❗️ |   |NO❗️ |
| └ | kLast | External ❗️ |   |NO❗️ |
| └ | mint | External ❗️ | 🛑  |NO❗️ |
| └ | burn | External ❗️ | 🛑  |NO❗️ |
| └ | swap | External ❗️ | 🛑  |NO❗️ |
| └ | skim | External ❗️ | 🛑  |NO❗️ |
| └ | sync | External ❗️ | 🛑  |NO❗️ |
| └ | initialize | External ❗️ | 🛑  |NO❗️ |
||||||
| **SafeMath** | Library |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
||||||
| **IERC20** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **IWETH** | Interface |  |||
| └ | deposit | External ❗️ |  💵 |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | withdraw | External ❗️ | 🛑  |NO❗️ |
||||||
| **IShibanceMigrator** | Interface |  |||
| └ | migrate | External ❗️ | 🛑  |NO❗️ |
||||||
| **IMasterBoi** | Interface |  |||
| └ | updateMultiplier | External ❗️ | 🛑  |NO❗️ |
| └ | add | External ❗️ | 🛑  |NO❗️ |
| └ | set | External ❗️ | 🛑  |NO❗️ |
| └ | poolLength | External ❗️ |   |NO❗️ |
| └ | checkPoolDuplicate | External ❗️ |   |NO❗️ |
| └ | getMultiplier | External ❗️ |   |NO❗️ |
| └ | pendingCake | External ❗️ |   |NO❗️ |
| └ | massUpdatePools | External ❗️ | 🛑  |NO❗️ |
| └ | updatePool | External ❗️ | 🛑  |NO❗️ |
| └ | deposit | External ❗️ | 🛑  |NO❗️ |
| └ | withdraw | External ❗️ | 🛑  |NO❗️ |
| └ | enterStaking | External ❗️ | 🛑  |NO❗️ |
| └ | leaveStaking | External ❗️ | 🛑  |NO❗️ |
| └ | emergencyWithdraw | External ❗️ | 🛑  |NO❗️ |
| └ | getPoolInfo | External ❗️ |   |NO❗️ |
| └ | dev | External ❗️ | 🛑  |NO❗️ |
||||||
| **IERC20** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **MasterBoi** | Implementation | Ownable |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | updateMultiplier | Public ❗️ | 🛑  | onlyOwner |
| └ | poolLength | External ❗️ |   |NO❗️ |
| └ | checkPoolDuplicate | Public ❗️ |   |NO❗️ |
| └ | add | Public ❗️ | 🛑  | onlyOwner |
| └ | set | Public ❗️ | 🛑  | onlyOwner |
| └ | updateStakingPool | Internal 🔒 | 🛑  | |
| └ | getMultiplier | Public ❗️ |   |NO❗️ |
| └ | pendingCake | External ❗️ |   |NO❗️ |
| └ | massUpdatePools | Public ❗️ | 🛑  |NO❗️ |
| └ | updatePool | Public ❗️ | 🛑  | validatePool |
| └ | deposit | Public ❗️ | 🛑  | validatePool |
| └ | withdraw | Public ❗️ | 🛑  | validatePool |
| └ | enterStaking | Public ❗️ | 🛑  |NO❗️ |
| └ | leaveStaking | Public ❗️ | 🛑  |NO❗️ |
| └ | emergencyWithdraw | Public ❗️ | 🛑  |NO❗️ |
| └ | getPoolInfo | Public ❗️ |   |NO❗️ |
| └ | safeCakeTransfer | Internal 🔒 | 🛑  | |
| └ | dev | Public ❗️ | 🛑  |NO❗️ |
||||||
| **WoofToken** | Implementation | BEP20 |||
| └ | mint | Public ❗️ | 🛑  | onlyOwner |
| └ | delegates | External ❗️ |   |NO❗️ |
| └ | delegate | External ❗️ | 🛑  |NO❗️ |
| └ | delegateBySig | External ❗️ | 🛑  |NO❗️ |
| └ | getCurrentVotes | External ❗️ |   |NO❗️ |
| └ | getPriorVotes | External ❗️ |   |NO❗️ |
| └ | _delegate | Internal 🔒 | 🛑  | |
| └ | _moveDelegates | Internal 🔒 | 🛑  | |
| └ | _writeCheckpoint | Internal 🔒 | 🛑  | |
| └ | safe32 | Internal 🔒 |   | |
| └ | getChainId | Internal 🔒 |   | |
||||||
| **DoggyPound** | Implementation | BEP20 |||
| └ | mint | Public ❗️ | 🛑  | onlyOwner |
| └ | burn | Public ❗️ | 🛑  | onlyOwner |
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | safeCakeTransfer | Public ❗️ | 🛑  | onlyOwner |
| └ | delegates | External ❗️ |   |NO❗️ |
| └ | delegate | External ❗️ | 🛑  |NO❗️ |
| └ | delegateBySig | External ❗️ | 🛑  |NO❗️ |
| └ | getCurrentVotes | External ❗️ |   |NO❗️ |
| └ | getPriorVotes | External ❗️ |   |NO❗️ |
| └ | _delegate | Internal 🔒 | 🛑  | |
| └ | _moveDelegates | Internal 🔒 | 🛑  | |
| └ | _writeCheckpoint | Internal 🔒 | 🛑  | |
| └ | safe32 | Internal 🔒 |   | |
| └ | getChainId | Internal 🔒 |   | |
||||||
| **SupportBoi** | Implementation |  |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | addressLength | External ❗️ |   |NO❗️ |
| └ | getMultiplier | Internal 🔒 |   | |
| └ | pendingReward | External ❗️ |   |NO❗️ |
| └ | updatePool | Public ❗️ | 🛑  |NO❗️ |
| └ | deposit | Public ❗️ | 🛑  |NO❗️ |
| └ | withdraw | Public ❗️ | 🛑  |NO❗️ |
| └ | emergencyWithdraw | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Multicall** | Implementation |  |||
| └ | aggregate | Public ❗️ | 🛑  |NO❗️ |
| └ | getEthBalance | Public ❗️ |   |NO❗️ |
| └ | getBlockHash | Public ❗️ |   |NO❗️ |
| └ | getLastBlockHash | Public ❗️ |   |NO❗️ |
| └ | getCurrentBlockTimestamp | Public ❗️ |   |NO❗️ |
| └ | getCurrentBlockDifficulty | Public ❗️ |   |NO❗️ |
| └ | getCurrentBlockGasLimit | Public ❗️ |   |NO❗️ |
| └ | getCurrentBlockCoinbase | Public ❗️ |   |NO❗️ |
||||||
| **Timelock** | Implementation |  |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | setDelay | Public ❗️ | 🛑  |NO❗️ |
| └ | acceptAdmin | Public ❗️ | 🛑  |NO❗️ |
| └ | setPendingAdmin | Public ❗️ | 🛑  |NO❗️ |
| └ | queueTransaction | Public ❗️ | 🛑  |NO❗️ |
| └ | cancelTransaction | Public ❗️ | 🛑  |NO❗️ |
| └ | executeTransaction | Public ❗️ |  💵 |NO❗️ |
| └ | getBlockTimestamp | Internal 🔒 |   | |
||||||
| **IShibanceCallee** | Interface |  |||
| └ | pancakeCall | External ❗️ | 🛑  |NO❗️ |
||||||
| **IShibancePair** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | DOMAIN_SEPARATOR | External ❗️ |   |NO❗️ |
| └ | PERMIT_TYPEHASH | External ❗️ |   |NO❗️ |
| └ | nonces | External ❗️ |   |NO❗️ |
| └ | permit | External ❗️ | 🛑  |NO❗️ |
| └ | MINIMUM_LIQUIDITY | External ❗️ |   |NO❗️ |
| └ | factory | External ❗️ |   |NO❗️ |
| └ | token0 | External ❗️ |   |NO❗️ |
| └ | token1 | External ❗️ |   |NO❗️ |
| └ | getReserves | External ❗️ |   |NO❗️ |
| └ | price0CumulativeLast | External ❗️ |   |NO❗️ |
| └ | price1CumulativeLast | External ❗️ |   |NO❗️ |
| └ | kLast | External ❗️ |   |NO❗️ |
| └ | mint | External ❗️ | 🛑  |NO❗️ |
| └ | burn | External ❗️ | 🛑  |NO❗️ |
| └ | swap | External ❗️ | 🛑  |NO❗️ |
| └ | skim | External ❗️ | 🛑  |NO❗️ |
| └ | sync | External ❗️ | 🛑  |NO❗️ |
| └ | initialize | External ❗️ | 🛑  |NO❗️ |
||||||
| **IShibanceFactory** | Interface |  |||
| └ | feeTo | External ❗️ |   |NO❗️ |
| └ | feeToSetter | External ❗️ |   |NO❗️ |
| └ | getPair | External ❗️ |   |NO❗️ |
| └ | allPairs | External ❗️ |   |NO❗️ |
| └ | allPairsLength | External ❗️ |   |NO❗️ |
| └ | createPair | External ❗️ | 🛑  |NO❗️ |
| └ | setFeeTo | External ❗️ | 🛑  |NO❗️ |
| └ | setFeeToSetter | External ❗️ | 🛑  |NO❗️ |
||||||
| **IERC20** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **ShibancePair** | Implementation | IShibancePair, ShibanceERC20 |||
| └ | getReserves | Public ❗️ |   |NO❗️ |
| └ | _safeTransfer | Private 🔐 | 🛑  | |
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | initialize | External ❗️ | 🛑  |NO❗️ |
| └ | _update | Private 🔐 | 🛑  | |
| └ | _mintFee | Private 🔐 | 🛑  | |
| └ | mint | External ❗️ | 🛑  | lock |
| └ | burn | External ❗️ | 🛑  | lock |
| └ | swap | External ❗️ | 🛑  | lock |
| └ | skim | External ❗️ | 🛑  | lock |
| └ | sync | External ❗️ | 🛑  | lock |
||||||
| **Math** | Library |  |||
| └ | min | Internal 🔒 |   | |
| └ | sqrt | Internal 🔒 |   | |
||||||
| **UQ112x112** | Library |  |||
| └ | encode | Internal 🔒 |   | |
| └ | uqdiv | Internal 🔒 |   | |
||||||
| **ShibanceFactory** | Implementation | IShibanceFactory |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | allPairsLength | External ❗️ |   |NO❗️ |
| └ | createPair | External ❗️ | 🛑  |NO❗️ |
| └ | setFeeTo | External ❗️ | 🛑  |NO❗️ |
| └ | setFeeToSetter | External ❗️ | 🛑  |NO❗️ |
||||||
| **Context** | Implementation |  |||
| └ | _msgSender | Internal 🔒 |   | |
| └ | _msgData | Internal 🔒 |   | |
||||||
| **Ownable** | Implementation | Context |||
| └ | <Constructor> | Internal 🔒 | 🛑  | |
| └ | owner | Public ❗️ |   |NO❗️ |
| └ | renounceOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
||||||
| **SafeMath** | Library |  |||
| └ | tryAdd | Internal 🔒 |   | |
| └ | trySub | Internal 🔒 |   | |
| └ | tryMul | Internal 🔒 |   | |
| └ | tryDiv | Internal 🔒 |   | |
| └ | tryMod | Internal 🔒 |   | |
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
||||||
| **IERC20** | Interface |  |||
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **Address** | Library |  |||
| └ | isContract | Internal 🔒 |   | |
| └ | sendValue | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionStaticCall | Internal 🔒 |   | |
| └ | functionStaticCall | Internal 🔒 |   | |
| └ | functionDelegateCall | Internal 🔒 | 🛑  | |
| └ | functionDelegateCall | Internal 🔒 | 🛑  | |
| └ | _verifyCallResult | Private 🔐 |   | |
||||||
| **SafeERC20** | Library |  |||
| └ | safeTransfer | Internal 🔒 | 🛑  | |
| └ | safeTransferFrom | Internal 🔒 | 🛑  | |
| └ | safeApprove | Internal 🔒 | 🛑  | |
| └ | safeIncreaseAllowance | Internal 🔒 | 🛑  | |
| └ | safeDecreaseAllowance | Internal 🔒 | 🛑  | |
| └ | _callOptionalReturn | Private 🔐 | 🛑  | |
||||||
| **Pausable** | Implementation | Context |||
| └ | <Constructor> | Internal 🔒 | 🛑  | |
| └ | paused | Public ❗️ |   |NO❗️ |
| └ | _pause | Internal 🔒 | 🛑  | whenNotPaused |
| └ | _unpause | Internal 🔒 | 🛑  | whenPaused |
||||||
| **IMasterChef** | Interface |  |||
| └ | deposit | External ❗️ | 🛑  |NO❗️ |
| └ | withdraw | External ❗️ | 🛑  |NO❗️ |
| └ | enterStaking | External ❗️ | 🛑  |NO❗️ |
| └ | leaveStaking | External ❗️ | 🛑  |NO❗️ |
| └ | pendingCake | External ❗️ |   |NO❗️ |
| └ | userInfo | External ❗️ |   |NO❗️ |
| └ | emergencyWithdraw | External ❗️ | 🛑  |NO❗️ |
||||||
| **WoofVault** | Implementation | Ownable, Pausable |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | deposit | External ❗️ | 🛑  | whenNotPaused notContract |
| └ | withdrawAll | External ❗️ | 🛑  | notContract |
| └ | harvest | External ❗️ | 🛑  | notContract whenNotPaused |
| └ | setAdmin | External ❗️ | 🛑  | onlyOwner |
| └ | setTreasury | External ❗️ | 🛑  | onlyOwner |
| └ | setPerformanceFee | External ❗️ | 🛑  | onlyAdmin |
| └ | setCallFee | External ❗️ | 🛑  | onlyAdmin |
| └ | setWithdrawFee | External ❗️ | 🛑  | onlyAdmin |
| └ | setWithdrawFeePeriod | External ❗️ | 🛑  | onlyAdmin |
| └ | emergencyWithdraw | External ❗️ | 🛑  | onlyAdmin |
| └ | inCaseTokensGetStuck | External ❗️ | 🛑  | onlyAdmin |
| └ | pause | External ❗️ | 🛑  | onlyAdmin whenNotPaused |
| └ | unpause | External ❗️ | 🛑  | onlyAdmin whenPaused |
| └ | calculateHarvestCakeRewards | External ❗️ |   |NO❗️ |
| └ | calculateTotalPendingCakeRewards | External ❗️ |   |NO❗️ |
| └ | getPricePerFullShare | External ❗️ |   |NO❗️ |
| └ | withdraw | Public ❗️ | 🛑  | notContract |
| └ | available | Public ❗️ |   |NO❗️ |
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | _earn | Internal 🔒 | 🛑  | |
| └ | _isContract | Internal 🔒 |   | |


 Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
