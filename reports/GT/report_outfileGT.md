## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| Contracts/contracts/Governance.sol | b0f5a4d47ba9c043b228de5f1b901c515f5fe086 |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **GovernanceToken** | Implementation | Initializable, ERC20Upgradeable, ERC20PausableUpgradeable, OwnableUpgradeable, Common, ReentrancyGuardUpgradeable |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | initialize | Public ❗️ | 🛑  | initializer |
| └ | _setDefaultThresholds | Private 🔐 | 🛑  | |
| └ | decimals | Public ❗️ |   |NO❗️ |
| └ | getSignatoryList | External ❗️ |   |NO❗️ |
| └ | getWhiteListedUsers | External ❗️ |   |NO❗️ |
| └ | getThresholds | External ❗️ |   |NO❗️ |
| └ | getTokenSupplyControlRequest | External ❗️ |   |NO❗️ |
| └ | getTransactionControlRequest | External ❗️ |   |NO❗️ |
| └ | getSignatoryControlRequest | External ❗️ |   |NO❗️ |
| └ | getThresholdControlRequest | External ❗️ |   |NO❗️ |
| └ | getWhiteListControlRequest | External ❗️ |   |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
| └ | createTokenSupplyControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateTokenSupplyControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createTransactionControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createSignatoryControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateSignatoryControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createThresholdControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateThresholdControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | createWhiteListControlRequest | External ❗️ | 🛑  | onlySignatory |
| └ | updateWhiteListControlRequest | External ❗️ | 🛑  | onlySignatory |
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
