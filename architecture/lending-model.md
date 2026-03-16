# DeFi Lending Model

Lending protocols allow users to borrow and lend digital assets without intermediaries.

## System Components

- Liquidity Pools
- Collateral Management
- Interest Rate Model
- Liquidation Mechanism

## Overcollateralization

Borrowers must deposit collateral greater than the borrowed value.

Example:

Collateral: $150 ETH  
Borrow: $100 USDC

If collateral value falls below a threshold, the position can be liquidated.

## Interest Rate Model

Interest rates are usually determined algorithmically based on supply and demand.

High borrowing demand increases interest rates.

## Liquidation

If collateral becomes insufficient, liquidators can repay part of the loan and receive collateral at a discount.
