# Starknet-Tech-Stacks-Mindmap

Welcome to the Starknet Tech Stacks Mindmap repository! This open collaboration project aims to explore and document the various technology stacks associated with Starknet, a powerful blockchain platform.

In this repository, you will find a comprehensive mind map that visually organizes the different components, frameworks, tools, and languages relevant to Starknet development. The mind map serves as a valuable reference for developers, researchers, and enthusiasts interested in leveraging Starknet's capabilities.

![alt text](./images/Starknet.jpg)

The mind map is organized into the following categories:

- **Languages**
- **Frameworks**
- **Tools**
- **Components**
- **Resources**

## Table of Contents

- [Cairo](#cairo)
  - [Cairo VM](#cairo-vm)
    - [cairo-lang](#cairo-lang)
    - [cairo-vm](#cairo-vm)
  - [Scarb](#scarb)
  - [Starknet Contracts](#starknet-contracts)
    - [protostar](#protostar)
  - [Kakarot](#kakarot)
  - [Cairo Book](#cairo-book)
- [starknet_in_rust](#starknet-in-rust)
- [starknet.py](#starknetpy)
- [Starknet Edu](#starknet-edu)
  - [Starknet Book](#starknet-book)
  - [Starknet Cairo 101](#starknet-cairo-101)
  - [Starknet Accounts](#starknet-accounts)
  - [Starknet ERC721](#starknet-erc721)
  - [Starknet ERC20](#starknet-erc20)
- [Madara](#madara)
- [Blockifier](#blockifier)
- [Sequencer](#sequencer)
  - ~~[lambda_starknet_sequencer](#lambda_starknet_sequencer)~~
- [OpenZeppelin/cairo-contracts](#openzeppelincairo-contracts)
- [alexandria](#alexandria)
- [dojo](#dojo)
  - [Sozu](#sozu)
  - [Katana](#katana)
  - [Torii](#torii)
- [juno](#juno)
- [starknet-rs](#starknet-rs)
- [starkli](#starkli)
- [quickly on-board new developers by examples](#quickly-on-board-new-developers-by-examples)
  - [cairo-by-example](#cairo-by-example)
  - [StarknetByExample](#starknetbyexample)

## Cairo

Repository:
https://github.com/starkware-libs/cairo

### Cairo VM

#### cairo-lang

Written in Python and is currently in production

Repository:
https://github.com/starkware-libs/cairo-lang

#### cairo-vm

Written in Rust will replace the Python one. Formerly known as cairo-rs.

Repository:
https://github.com/lambdaclass/cairo-vm

### Scarb

Cairo package manager

https://github.com/software-mansion/scarb

### Starknet Contracts

#### protostar

Toolchain for developing and testing contracts

Repository:
https://github.com/software-mansion/protostar

### Kakarot

Kakarot is an zkEVM written in Cairo. Can be used to run Ethereum smart contracts on Starknet.

Repository:
https://github.com/kkrt-labs/kakarot

### Cairo Book

Repository:
https://github.com/cairo-book/cairo-book.github.io

## starknet_in_rust

Written in Rust and make use of cairo-rs declare, deploy and interact with contracts

Repository:
https://github.com/lambdaclass/starknet_in_rust

## starknet.py

Pyhton SDK for Starknet

Repository:
https://github.com/software-mansion/starknet.py

## Starknet Edu

Repository:
https://github.com/starknet-edu

- Starknet Book: https://github.com/starknet-edu/starknetbook
- Starknet Cairo 101: https://github.com/starknet-edu/starknet-cairo-101
- Starknet Accounts: https://github.com/starknet-edu/starknet-accounts
- Starknet ERC721: https://github.com/starknet-edu/starknet-erc721
- Starknet ERC20: https://github.com/starknet-edu/starknet-erc20

## Madara

Utilizing the Substrate framework and integrating the Cairo VM for the building of appchain / layer3.

Substrate is an open-source Rust framework to build customizable blockchains.

The Cairo VM is specifically designed to efficiently generate Validity Proofs for program execution.

By employing state tracking and a smart contract to verify these proofs on L2, appchain created by Madara ensures secure integration with Starknet.

Repository:
https://github.com/keep-starknet-strange/madara

## Blockifier

A Rust implementation for the transaction-executing component in the StarkNet sequencer

Repository:
https://github.com/starkware-libs/blockifier

## Sequencer

- ~~lambda_starknet_sequencer~~

  A Starknet decentralized sequencer implementation

  Repository:
  https://github.com/lambdaclass/lambda_starknet_sequencer

## OpenZeppelin/cairo-contracts

Repository:
https://github.com/OpenZeppelin/cairo-contracts

## alexandria

A collection of useful algorithms and data structures implemented in Cairo

Repository:
https://github.com/keep-starknet-strange/alexandria

## dojo

Game engine and toolchain for building onchain games

- [Sozu](#sozu)
- [Katana](#katana)
- [Torii](#torii)

## juno

Full node Starknet client implementation.

## starknet-rs

starknet-rs, Complete Starknet library in Rust.

## starkli

CLI tool for Starknet.

## quickly on-board new developers by examples

### cairo-by-example

Repository:
https://github.com/lambdaclass/cairo-by-example/

### StarknetByExample

Repository:
https://github.com/NethermindEth/StarknetByExample

## Contribute

We encourage you to contribute to this project by suggesting additions, modifications, or corrections to the existing mind map. Your contributions can help expand the knowledge base and provide a valuable resource for the Starknet community. Whether you have expertise in specific tech stacks or want to learn more about Starknet's ecosystem, your involvement is greatly appreciated.

To contribute, simply fork this repository, make your changes, and submit a pull request.

Let's work together to create a comprehensive and up-to-date mind map of Starknet tech stacks. Join us in shaping the future of decentralized applications on Starknet!

Feel free to customize this description to fit your specific project goals and vision.
