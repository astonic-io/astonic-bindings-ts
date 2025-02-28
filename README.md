# Astonic Bindings TS

This package provides auto-generated typescript types and ethers.js factories for interacting with the Astonic Protocol

## What is Astonic?

The Astonic protocol is a smart contract platform built on the Planq blockchain that enables the creation of stable value digital assets. Stable assets created with Astonic can be classified as 'Hybrid stable assets' as they are algorithmic, transparent and backed by a over-collateralized, diversified portfolio of exogenous crypto assets.

## Documentation

- [Protocol Documentation](https://astonic.gitbook.io/astonic-docs/)

## Getting Started

```bash
# Get the latest code
git clone git@github.com:astonic-io/astonic-bindings-ts.git

# Change directory to the the newly cloned repo
cd astonic-bindings-ts

# Install dev dependencies with yarn
yarn

# Install astonic-core submodule dependency with forge
forge install

# Compile the astonic-core dependency contracts with forge
forge build

# Generate types
yarn generatetypes

# Build the types
yarn build
```
