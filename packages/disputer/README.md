# @uma/disputer

This package contains the UMA Dispute bot reference implementation. This executable will watch an ExpiringmutliParty
contract for liquidations and dispute any that it deems to be invalid.

## Installing the package

```bash
npm install @uma/disputer -g
```

## Running the disputer

The simplest way to run the disputer (with default parameters and price feeds) is:

```bash
yarn global add @uma/disputer
EMP_ADDRESS=0x1234 CUSTOM_NODE_URL=your.node.url MNEMONIC="your mnemonic here" disputer --network mainnet_mnemonic
```

## Other networks and private keys

See https://docs.umaproject.org/developers/setup#keys-and-networks to see options on how to plug in your private
keys in different ways or use different networks.

## More customization options

See [here](index.js#189-209) for a full list of environment variables that can be provided to customize the disputer.
