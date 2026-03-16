# Integer Overflow

Integer overflow occurs when a number exceeds the maximum value that a data type can store.

This can cause unexpected behavior in smart contracts.

## Example

If a variable reaches its maximum value and increases again, it may reset to zero.

## Impact

- incorrect balances
- broken calculations
- potential exploits

## Prevention

Modern Solidity versions include built-in overflow protection.

Developers should also use safe math practices.
