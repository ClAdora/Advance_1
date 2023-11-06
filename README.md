# Avalanche Mod 1

### ERC20
#### `transfer`

- **Description**: Transfers a specified amount of tokens from the sender's account to the recipient's account.
- **Function Signature**: `transfer(address recipient, uint amount) external returns (bool)`

#### `approve`

- **Description**: Allows the spender to withdraw from the sender's account, multiple times, up to the specified amount.
- **Function Signature**: `approve(address spender, uint amount) external returns (bool)`

#### `transferFrom`

- **Description**: Transfers a specified amount of tokens from the sender's account to the recipient's account, provided the sender has been approved to do so.
- **Function Signature**: `transferFrom(address sender, address recipient, uint amount) external returns (bool)`

#### `mint`

- **Description**: Mints a specified amount of tokens and assigns them to the sender's account.
- **Function Signature**: `mint(uint amount) external`

#### `burn`

- **Description**: Burns a specified amount of tokens from the sender's account.
- **Function Signature**: `burn(uint amount) external`



### Vault

#### `deposit`

- **Description**: Deposits a specified amount of tokens into the vault and mints corresponding shares to the depositor.
- **Function Signature**: `deposit(uint _amount) external`

#### `withdraw`

- **Description**: Withdraws a specified amount of shares from the vault and burns the corresponding shares, transferring the equivalent tokens to the withdrawer.
- **Function Signature**: `withdraw(uint _shares) external` 
