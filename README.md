# Liquidator-monorepos

This monorepo contains the following files and directories:

1. `liquidator/`: A Golang application for liquidating positions on the Euler protocol.
2. `hardhat/`: A directory containing the Hardhat setup for testing Euler liquidations on a local fork.
3. `subgraph/`: A Subgraph implementation for tracking Euler's positions and identifying underwater positions that could be liquidated.

## Liquidator

The `liquidator` directory contains a Golang application that facilitates the liquidation of positions on the Euler protocol. It utilizes the Euler protocol's contracts and interacts with the Ethereum blockchain. To use the liquidator, follow the instructions in the `liquidator/README.md` file.

## Hardhat

The `hardhat` directory contains the necessary setup for testing Euler liquidations on a local fork. It utilizes the Hardhat framework to deploy and interact with the Euler protocol contracts. Detailed instructions on setting up and running the tests can be found in the `hardhat/README.md` file.

## Subgraph

The `subgraph` directory contains a Subgraph implementation for tracking Euler's positions and identifying underwater positions that could be liquidated. It listens to relevant events emitted by the Euler protocol contracts and stores the data in a subgraph database. To set up and run the Subgraph, refer to the `subgraph/README.md` file.

Please refer to the individual README files within each directory for more detailed instructions and information about each component.

```

```
