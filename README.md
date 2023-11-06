# Avalanche Mod 1


#### Functions

- `transfer(address recipient, uint amount) external returns (bool)`: Transfers a specified amount of tokens from the sender's account to the recipient's account.
- `approve(address spender, uint amount) external returns (bool)`: Allows the spender to withdraw from the sender's account, multiple times, up to the specified amount.
- `transferFrom(address sender, address recipient, uint amount) external returns (bool)`: Transfers a specified amount of tokens from the sender's account to the recipient's account, provided the sender has been approved to do so.
- `mint(uint amount) external`: Mints a specified amount of tokens and assigns them to the sender's account.
- `burn(uint amount) external`: Burns a specified amount of tokens from the sender's account.

### Vault

#### Functions

- `deposit(uint _amount) external`: Deposits a specified amount of tokens into the vault and mints corresponding shares to the depositor.
- `withdraw(uint _shares) external`: Withdraws a specified amount of shares from the vault and burns the corresponding shares, transferring the equivalent tokens to the withdrawer.
