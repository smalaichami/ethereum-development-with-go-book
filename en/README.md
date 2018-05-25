# Introduction

This book is to serve as a general help guide for those wanting to develop ethereum applications using the Go programming language.

This book is composed of many examples that I wish I had encountered before when I first started Ethereum development with Go. This book will walk you through most things that you should be aware of in order for you to be a productive Ethereum developer using Go.

Ethereum is quickly evolving and things may go out of date sooner than anticipated. I strongly suggest opening an [issue](https://github.com/miguelmota/ethereum-development-with-go-book/issues) or making a [pull request](https://github.com/miguelmota/ethereum-development-with-go-book/pulls) if you observe things that can be improved. This book is completely open and free and available on [github](https://github.com/miguelmota/ethereum-development-with-go-book).

## Ethereum

> Ethereum is an open-source, public, blockchain-based distributed computing platform and operating system featuring smart contract (scripting) functionality. It supports a modified version of Nakamoto consensus via transaction based state transitions.

-[Wikipedia](https://en.wikipedia.org/wiki/Ethereum)

Ethereum is a blockchain that allows developers to create applications that can be ran completely decentralized, meaning that no single entity can take it down or modify it. Each application deployed to Ethereum is executed by every single full client on the Ethereum network.

## Solidity

Solidity is a turing complete programming language for writing smart contracts. Solidity gets compiled to bytecode which is what the Ethereum virtual machine exectues.

## Etherscan

Etherscan is a website for exploring and drilling down on data that lives on the blockchain. These type of website are known as "Block Explorers" because they allow you to explore the contents of a block, which is a fundamental component of the blockchain. The block contains the data of all the transactions that have been mined within the allocated block time. The block explorer also allows you to view events that were emitted during the execution of the smart contract as well as things such as how much was paid for the gas and amount of ether was transacted, etc.

## go-ethereum

In this book we'll be using the [go-ethereum](https://github.com/ethereum/go-ethereum), the official Ethereum implementation in Go, to interact with the blockchain. Go-ethereum, also known as `geth` for short, is the most popular Ethereum client and because it's in Go, it provides everything we'll ever need for reading and writing to the blockchain.

## Author

This book is written and maintained by [Miguel Mota](https://github.com/miguelmota).