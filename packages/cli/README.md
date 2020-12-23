# UMA CLI Tool

This package contains the UMA CLI tool. This tool works, but is deprecated, so its use is discouraged. It can be useful
for certain tasks, like viewing governance/admin proposals, but it is usually preferred to use tools.umaproject.org or
vote.umaproject.org.

## Installing the package

```bash
npm install -g @uma/cli
```

## Running the package

```bash
uma-cli --network mainnet_mnemonic
```

## Using your own node URL

By default, this package uses a default infura account that often exceeds its daily quota. To plug in your own node
node ULR, export the following env variable:

```bash
export CUSTOM_NODE_URL=your.node.url.io
uma-cli --network mainnet_mnemonic
```

## Using your private keys

See https://docs.umaproject.org/developers/setup#keys-and-networks to see options on how to plug in your own private
keys.
