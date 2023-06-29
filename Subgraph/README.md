# Subgraph

The Euler Subgraph directory contains a Subgraph implementation for tracking Euler's positions and identifying underwater positions that could be liquidated.

## Prerequisites

- Node.js (version >= 12.0.0)
- Yarn (optional, but recommended for package management)

## Installation

1. Clone this repository:

```

git clone https://github.com/your-username/euler-subgraph.git

```

2. Change into the `euler-subgraph` directory:

```

cd euler-subgraph

```

3. Install the necessary dependencies:

```

yarn install

```

## Configuration

1. Update the Subgraph manifest file `subgraph.yaml`:

   - Set the desired name and description for your Subgraph.
   - Define the data sources for tracking Euler's positions and events. Specify the contract ABIs and Ethereum network details.

## Usage

To build and deploy the Euler Subgraph, execute the following command:

```

yarn build

```

This will generate the Subgraph deployment artifacts.

To deploy the Subgraph to a specific network, run:

```

yarn deploy <network>

```

Replace `<network>` with the desired network name specified in your Hardhat configuration.

## Customization

You can customize the Subgraph data model, mappings, and queries to meet your specific needs. Refer to the Subgraph documentation (https://thegraph.com/docs/) for detailed information on customizing Subgraphs.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
