---
layout: default
---

# Solana Developer's Guide

Table of contents
* TOC
{:toc}


# Prerequisites

## Solana

## Programming Languages

1. [Rust Book](https://doc.rust-lang.org/book/title-page.html)

# Online resources

## Core learning


## Learning with practise


## Learning with people

- StackOverflow

# Setting up development environment

1. [Solana Tool Suite](https://docs.solana.com/cli/install-solana-cli-tools)
2. [Solana Development Tutorial](https://solongwallet.medium.com/solana-development-tutorial-things-you-should-know-before-structuring-your-code-807f0e2ee43)
3. [Serum Academy](https://serum-academy.com/en/) The goal of Serum Academy is to teach people how to use Serum ecosystem and build projects on Solana and Serum.
4. [Examples using SPL](https://github.com/solana-labs/solana-program-library/tree/master/examples)
5. [Rust SDK](https://docs.rs/solana-sdk/1.6.8/solana_sdk/) [Github](https://github.com/solana-labs/solana/tree/master/sdk)
6. [Docker Minimal](https://github.com/solana-labs/solana/tree/master/sdk/docker-solana)
7. [Rust Programming on Solana](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/#entrypoint-rs-programs-and-accounts)
8. [Rust In Blockchain](https://rustinblockchain.org)
9. [brson's blog](https://brson.github.io/blog/index.html)

## Hardware

## IDE

## Framework

# Development

## Writing contracts

1. On Chain programs can be written in C, Rust and are compiled by LLVM. JS Bindings are available for most of the programs provided by Solana for common use cases.
2. [Developing with Rust](https://docs.solana.com/developing/on-chain-programs/developing-rust)
3. [Developing with C](https://docs.solana.com/developing/on-chain-programs/developing-c)
4. Solana Python SDK [solana-py](https://github.com/michaelhly/solana-py)
5. Solana JavaScript API [solana-web3.js](https://github.com/solana-labs/solana-web3.js)

### Design Patterns

### Getting inspiration for writing contracts

## Testing contracts

### Writing JS Bindings

## Deploying contracts

## Upgrading contracts

# Interesting Programs

1. Solana Programs Library (SPL) - The Solana Program Library (SPL) is a collection of on-chain programs targeting the Sealevel parallel runtime. These programs are tested against Solana's implementation of Sealevel, solana-runtime, and deployed to its mainnet.[API Docs](https://docs.rs/solana-program/1.4.17/solana_program/index.html) [Developer Doc](https://spl.solana.com)
    1. Token Program [Developer Doc](https://spl.solana.com/token) - This is the most interesting program. This is where you can create, mint, transfer, delegate and do all the "core" stuff. This is implemented as [SPL Token](https://docs.rs/spl-token/3.0.1/spl_token/index.html), which is an ERC20-like Token program for the Solana blockchain  [Source Code](https://github.com/solana-labs/solana-program-library/tree/master/token) [JS Lib](https://github.com/solana-labs/solana-program-library/blob/master/token/js/client/token.js)
        1. [Non Fungible Token](https://spl.solana.com/token#non-fungible-tokens) - An NTF is simply a token type where only a single token has been minted. [Creating NFTs](https://spl.solana.com/token#example-create-a-non-fungible-token)
    2. Name Service - [Developer Doc](https://spl.solana.com/name-service) - This is another interesting service for issuing and managing ownership of: domain names, Solana Pubkeys, URLs, twitter handles, ipfs cid's etc. [Source Code](https://github.com/solana-labs/solana-program-library/tree/master/name-service) [JS Binding](https://github.com/solana-labs/solana-program-library/blob/master/name-service/js/src/bindings.ts)


# Other useful links

1. [Wormhole](https://github.com/certusone/wormhole) (ETH - SOL bridge) [Medium Blog Post](https://medium.com/certus-one/introducing-the-wormhole-bridge-24911b7335f7)
