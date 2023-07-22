## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| Contracts/contracts/StableCoin.sol | 61bf7c3bf0aaad57a34c96b5545cb808486d84cf |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **StableCoin** | Implementation | Initializable, ERC20Upgradeable, ERC20PausableUpgradeable, OwnableUpgradeable, Common, ReentrancyGuardUpgradeable |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | initialize | Public ❗️ | 🛑  | initializer |
| └ | _setDefaultThresholds | Private 🔐 | 🛑  | |
| └ | decimals | Public ❗️ |   |NO❗️ |
| └ | getSignatoryList | External ❗️ |   |NO❗️ |
| └ | getThresholds | External ❗️ |   |NO❗️ |
| └ | getTokenSupplyControlRequest | External ❗️ |   |NO❗️ |
| └ | getTransactionControlRequest | External ❗️ |   |NO❗️ |
| └ | getSignatoryControlRequest | External ❗️ |   |NO❗️ |
| └ | getThresholdControlRequest | External ❗️ |   |NO❗️ |
| └ | createTokenSupplyControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateTokenSupplyControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createTransactionControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createSignatoryControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateSignatoryControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createThresholdControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateThresholdControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | vote | External ❗️ | 🛑  | onlySignatory nonReentrant |
| └ | execute | External ❗️ | 🛑  |NO❗️ |
| └ | cancelRequest | External ❗️ | 🛑  | onlySignatory nonReentrant |
| └ | swap | External ❗️ | 🛑  | nonReentrant |
| └ | _beforeTokenTransfer | Internal 🔒 | 🛑  | whenNotPaused |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
