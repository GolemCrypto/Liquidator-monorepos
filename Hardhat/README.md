# Hardhat

The Euler Hardhat directory contains the necessary setup for testing Euler liquidations on a local fork.

## Prerequisites

- Node.js (version >= 12.0.0)
- Hardhat (version >= 2.0.0)
- Ethereum client (e.g., Ganache) for running a local fork of the Ethereum network

## Installation

1. Clone this repository:

```

git clone https://github.com/your-username/euler-hardhat.git

```

2. Change into the `euler-hardhat` directory:

```

cd euler-hardhat

```

3. Install the necessary dependencies:

```

npm install

```

## Configuration

1. Update the Hardhat configuration file `hardhat.config.js`:

   - Set the network details in the `networks` section to match your Ethereum client configuration.

## Usage

To run the Euler liquidation tests on the local fork, execute the following command:

```

npx hardhat test

```

This will execute the test scripts located in the `test` directory and provide the test results.

## Customization

You can customize the tests and test scenarios by modifying the scripts in the `test` directory. You may need to adapt the test cases and assertions to align with the Euler protocol contracts and your specific use case.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
