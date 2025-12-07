# Agoriz

Agoriz develops open infrastructure for direct, peer-to-peer economic exchange.
Our focus is on building tooling that allows users to transact without intermediaries, custodial risk, or mandatory identification.

## Overview

Agoriz maintains a set of protocols and tools for permissionless payments over public blockchain networks. The objective is to provide reliable primitives for sending and receiving value using only user-controlled keys, while keeping the system transparent and predictable from a technical standpoint.

The project is currently under active development. Some components are available for use, while others are in progress and will be released over time.

## Core Principles

**User-controlled funds**
All mechanisms are designed so that the user retains full control over their private keys and assets.

**Minimal assumptions**
Components avoid dependencies on centralized services when possible. Protocol rules are deterministic and verifiable.

**Network-based fees only**
The system is being redesigned to remove platform-level fees, leaving only the underlying network costs required by the blockchain used in the transaction.

**Interoperability**
The protocol aims to support multiple EVM-compatible networks and maintain consistent behavior across them.

**Transparent architecture**
Implementation details, transaction flows, and interfaces are documented to allow independent verification and auditing.

## Current Components

### Agoriz Protocol (in active development)

A multi-chain gateway for peer-to-peer value transfer.
Supports:

* Ethereum, Polygon, and other EVM-compatible networks
* Non-custodial transfers
* Configurable transaction parameters
* Deterministic fee behavior (network-only as development progresses)

### API Layer (experimental)

REST endpoints designed to simplify interaction with the protocol.
Intended usage:

* creating payment requests
* retrieving transaction metadata
* network-agnostic integration for frontend clients

### SDK and Integration Tools (in progress)

A set of libraries to interact with the protocol programmatically.
Goals include:

* simplified payment flows for applications
* utilities for signature handling
* helpers for multi-network deployments
  These components are not yet stable.

## Development Approach

The project favors correctness, resilience, and test coverage over rapid feature release.
Code and documentation are published incrementally as components reach a stable baseline.

## Contributing

Contribution guidelines, issue templates, and development instructions will be added once the repository structure stabilizes.
For now, feedback and technical discussion are welcome through GitHub issues.
