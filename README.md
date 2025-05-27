# ink-learn-flipper

Flipper, the Ink! Hello World.

Commented and explained version, based on the smart contracts tutorial from the [Pop Docs](https://learn.onpop.io/contracts).

[ink!](https://use.ink/) is the programming language designed for developing smart contracts in blockchains built with the Polkadot Substrate framework.
It is built with Rust, a language with a strong memory security guarantee, an advanced type system, and integral development tools.


## What is Flipper?

It is a smart contract that stores a boolean value and lets to ‘flip’ it or consulting it. It is interesting to comprehend how to:

- Define storage on ink!
- Create public messages (`#[ink(message)]`)
- Build and compile to Wasm
- Test a smart contract, including unit and end-to-end tests
- Deploy a smart contract, locally or on production.
