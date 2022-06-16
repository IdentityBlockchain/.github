# Identity Blockchain

## About

IdentityBlockchain uses state-certified electronic identities (eIDs) to establish blockchain identities and a consensus protocol called Proof of Identity (PoI). 

PoI is ”green” and enables many applications that are impossible to implement without verified identity on the blockchain, e.g., direct democracy and universal basic income, encrypted messaging, etc.

IdentityBlockchain, as presented here, aims to preserve identity anonymity by using zk-SNARKs and an anonymizing protocol for identity onboarding.

IdentityBlockchain will be a fork of Avalanche blockchain based on PoI.

The material that follows is under construction, bit it can offer a glimpse into the overlying ideas and concepts.

## Description

### Notation

| Symbol      | Meaning     |
| :---        |    :----:   |
| K      | <p align="left">State CA certified public key of e.g. eID</p>       |
| K(value)   | <p align="left">value encrypted with the public key K</p>        |
| K<sup>-1</sup> | <p align="left">Private key corresponding to the public key K</p>    |
| P | <p align="left">Person key, used to access IdentityBlockchain as an unknown Person</p>    |
| H | <p align="left">SHA256</p>    |
