# Reentrancy Attack

Reentrancy is a smart contract vulnerability where an external contract can repeatedly call a function before the previous execution is completed.

This can lead to unexpected behavior and fund theft.

## How It Works

1. A contract sends ETH to another contract.
2. The receiving contract executes a fallback function.
3. The fallback calls the vulnerable function again before state updates.

## Example Scenario

A withdraw function sends ETH before updating the user's balance.

This allows an attacker to repeatedly withdraw funds.

## Prevention

- Use the checks-effects-interactions pattern
- Update state before sending funds
- Use reentrancy guards
