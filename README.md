# yield-v1

EVM network smart contracts for the HippoxOS yield system.

## Overview

hippox-yield-v1 is the yield layer of the HippoxOS ecosystem, managing how user assets generate and receive on-chain returns.

## Core Features

- Yield Sources: Aggregates returns from DEX liquidity, bond curve issuance, and other on-chain strategies.
- Yield Distribution: Calculates and distributes returns to eligible users based on their positions.
- Claiming: Users can claim accrued yield transparently on-chain.

## Project Structure

src/ Core yield contracts
test/ Tests
script/ Deployment and interaction scripts

## Development

Build: forge build
Test: forge test
Local node: anvil
Deploy: forge script script/Deploy.s.sol --rpc-url <your_rpc_url> --private-key <your_private_key>
