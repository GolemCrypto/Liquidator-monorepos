# Liquidator

The Euler Liquidator is a Golang application that facilitates the liquidation of positions on the Euler protocol.

## Prerequisites

- Go 1.16 or higher
- Ethereum client (e.g., Ganache, Geth) connected to the Euler protocol contracts
- Euler protocol contract addresses and ABIs

## Installation

1. Clone this repository:

```
git clone https://github.com/your-username/euler-liquidator.git
```

2. Change into the `euler-liquidator` directory:

```
cd euler-liquidator
```

3. Install the necessary dependencies:

```
go mod tidy
```

## Configuration

1. Rename the `config.example.yaml` file to `config.yaml`.

2. Update the `config.yaml` file with the following information:

   - Ethereum network URL: Provide the URL to connect to your Ethereum client.
   - Euler protocol contract addresses and ABIs: Provide the contract addresses and ABIs for the Euler protocol contracts.

## Usage

To use the Euler Liquidator, run the following command:

```
go run main.go
```

The liquidator will start monitoring positions on the Euler protocol and perform liquidations for eligible underwater positions.

## Customization

You can customize the liquidation parameters and behavior by modifying the code in the `liquidation` package. You may need to adapt the code to meet the specific requirements of the Euler protocol or your use case.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
