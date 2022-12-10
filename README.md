# Deprecation Notice

This project is deprecated. Consider [LND Admin](https://github.com/janoside/lnd-admin) or [RTL](https://github.com/Ride-The-Lightning/RTL) as a replacement.

# Lightning RPC Explorer

Simple, database-free Lightning network explorer, via gRPC. Built with Node.js, express, bootstrap-v4.

This tool is intended to be a simple, self-hosted explorer for the Lightning network, driven by RPC calls to your own lightning node.

A live demo of the tool is available at https://lightning.chaintools.io

# Features

* Network summary
* Browse nodes and channels, sorted by last update or capacity
* View node and channel details
* Search by node or channel

# Getting started

## Prerequisites

1. Install and run a full, archiving node - [instructions](https://bitcoin.org/en/full-node). Ensure that your node has full transaction indexing enabled (`txindex=1`) and the RPC server enabled (`server=1`).
2. Synchronize your node with the Bitcoin network.
3. [Install LND](https://github.com/lightningnetwork/lnd/blob/master/docs/INSTALL.md)

## Instructions

1. Clone this repo
2. `npm install`
3. `npm run build`
4. Optional: Create file `app/credentials.js` with values to overwrite those in [app/defaultCredentials.js](app/defaultCredentials.js).
5. `npm start`
6. Open [http://127.0.0.1:3004/](http://127.0.0.1:3004/)


# Donate

To support continued development of this tool and/or to support the hosting of the live demo site:

* [Bitcoin](bitcoin:3NPGpNyLLmVKCEcuipBs7G4KpQJoJXjDGe): 3NPGpNyLLmVKCEcuipBs7G4KpQJoJXjDGe
* [Litecoin](litecoin:ME4pXiXuWfEi1ANBDo9irUJVcZBhsTx14i): ME4pXiXuWfEi1ANBDo9irUJVcZBhsTx14i

