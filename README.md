# Learning CosmWasm

This repository is for internal use to allow new developers to learn smart contract development with Rust and CosmWasm. The project is a step-by-step and modular implementation of a kind of liquid staking derivative.

## Goal

The goal is not build a production quality smart contract but only a toy example.

The contract should allow any user to `execute`:

* Deposit tokens inside the contract and receive an equivalent amount of share.

* Withdraw tokens from the contract depending on the amount of user shares and tokens inside the contract.

* Be Crazy by burning a certain amount of tokens inside the pool.

You have to design all the details of the contract storage and add the query you thing are useful for the proper working of the contract.

## How to start

Download the cw-template as a starting point for the project.

Create the contract.

Create unit tests.

Create multi-tests.
