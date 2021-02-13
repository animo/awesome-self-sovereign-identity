# Awesome Self-Sovereign Identity

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of self-sovereign identity resources.

Self-sovereign identity (SSI) is a term used to describe the digital movement that recognizes an individual should own and control their identity without the intervening administrative authorities. SSI allows people to interact in the digital world with the same freedom and capacity for trust as they do in the offline world. (by [Sovrin Foundation](https://sovrin.org/faq/what-is-self-sovereign-identity))

## Contents

<details><summary>Click to expand</summary>

- [Awesome Self-Sovereign Identity](#awesome-self-sovereign-identity)
  - [Contents](#contents)
  - [FAQ](#faq)
    - [Does Self-sovereign identity require a blockchain?](#does-self-sovereign-identity-require-a-blockchain)
    - [Is any personal data stored on a blockchain?](#is-any-personal-data-stored-on-a-blockchain)
  - [Basic Introduction](#basic-introduction)
  - [Collected Knowledge](#collected-knowledge)
  - [Specifications](#specifications)
    - [Decentralized Identifiers (DIDs)](#decentralized-identifiers-dids)
      - [Open Source Building Blocks](#open-source-building-blocks)
    - [Verifiable Credentials (VCs)](#verifiable-credentials-vcs)
      - [Open Source Building Blocks](#open-source-building-blocks-1)
  - [Networks](#networks)
  - [Projects and Applications](#projects-and-applications)
    - [Hyperledger Aries](#hyperledger-aries)
      - [Open Source Building Blocks](#open-source-building-blocks-2)
      - [Implementations](#implementations)
    - [Hyperledger Indy](#hyperledger-indy)
    - [IOTA](#iota)
      - [Open Source Building Blocks](#open-source-building-blocks-3)
      - [Implementations](#implementations-1)
    - [Universal Ledger Agent](#universal-ledger-agent)
    - [uPort](#uport)
  - [Papers, Books and Articles](#papers-books-and-articles)
  - [Inspiration](#inspiration)
  - [Contribute](#contribute)
  - [License](#license)

</details>

## FAQ

### Does Self-sovereign identity require a blockchain?

No not necessarily, but it does provide some useful features.

This article by IBM tries to give a clear overview on the subject: [
Self-sovereign identity: Why blockchain?](https://www.ibm.com/blogs/blockchain/2018/06/self-sovereign-identity-why-blockchain)

### Is any personal data stored on a blockchain?

No. Personal data should never be stored in a blockchain, and in a **true** self-sovereign identity system no personal data is ever stored on a blockchain.

## Basic Introduction

In 2016 Christopher Allen first came up with the vision for self-sovereign identity. With it came a proposal list of 10 guiding principles that make a digital identity self-sovereign. Since then these principles have been at the core of every self-sovereign identity solution. It could be stated that an identity can not be called self-sovereign if it does not conform to these principles.

- [10 Principles of Self-Sovereign Identity](http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html) - The Evolution of Identity, with the Path to self-sovereign identity and it's 10 Guiding Principles by Christopher Allen
- [Self-Sovereign Identity: The Ultimate Beginners Guide](https://tykn.tech/self-sovereign-identity/)
- [Video: Understanding Self-Sovereign Identity Through the Example of Renting a Property](https://www.youtube.com/watch?v=81GkdBRmsbE)
- [Video: Explaining Decentralized Identity Visually](https://www.youtube.com/watch?v=Ew-_F-OtDFI)
- [How to Convince Dad\* of the Importance of Self-Sovereign Identity](https://github.com/WebOfTrustInfo/rwot7/blob/master/final-documents/convincing-dad.md) - \*and your sister and your daughter and your best friend and your nephew.
- [Web Of Trust Self-Sovereign Identity Repository](https://github.com/WebOfTrustInfo/self-sovereign-identity) - Articles and documents associated with designing and implementing identity technology using self-sovereign identity principles
  - [7 Myths of Self-Sovereign Identity](https://github.com/WebOfTrustInfo/self-sovereign-identity/blob/master/7-myths-of-self-sovereign-identity.md) - by Timmothy Ruff

## Collected Knowledge

- [Decentralized Identity Foundation](https://identity.foundation) - Focused on developing the foundational components of an open, standards-based, decentralized identity ecosystem
- [SSI Meetup Webinars](https://ssimeetup.org/blog) - Webinars about Self-Sovereign Identity
- [Matching Identity Management Solutions to Self-Sovereign Identity Principles](https://www.slideshare.net/TommyKoens/matching-identity-management-solutions-to-selfsovereign-identity-principles/1) - An analysis of almost 50 (blockchain based) digital identity solutions matched against SSI principles

## Specifications

### Decentralized Identifiers (DIDs)

- [Official W3C Specification](https://w3c-ccg.github.io/did-spec/)
- [Decentralized Identifiers 101 (SSI Meetup)](https://ssimeetup.org/decentralized-identifiers-did-fundamental-block-self-sovereign-identity-drummond-reed-webinar-2/) - A SSI Meetup webinar by Drummond Reed about DIDs
- [Uniresolver](https://uniresolver.io/) - Online Universal DID Resolver

#### Open Source Building Blocks

- [JavaScript: DID Client (did-io)](https://github.com/digitalbazaar/did-io) - A DID resolution library for Javascript
- [JavaScript: DID](https://github.com/ceramicnetwork/js-did) - A simple library to interact with DIDs that conform to the DID-provider interface.
- [JavaScript: DID Resolver](https://github.com/decentralized-identity/did-resolver) - a simple common interface for javascript applications to resolve DID documents from Decentralized Identifiers (DIDs).
  - [ethr DID Resolver](https://github.com/decentralized-identity/ethr-did-resolver) - use ethereum addresses as fully self managed Decentralized Identifiers and wrap them in a DID Document
  - [web DID Resolver](https://github.com/decentralized-identity/web-did-resolver) - use domains accessed through https as Decentralized Identifiers and retrieve an associated DID Document
- [Rust: did-key.rs](https://github.com/decentralized-identity/did-key.rs) - provide basic support for `did:key` methods

### Verifiable Credentials (VCs)

- [Official W3C Data Model](https://www.w3.org/TR/vc-data-model/)
- [Verifiable Credentials 101 (SSI Meetup)](https://ssimeetup.org/verifiable-credentials-101-ssi-tyler-ruff-webinar-11/) - A SSI Meetup webinar by Tyler Ruff about VCs
- [Verifiable Credentials Use Cases](https://www.w3.org/TR/vc-use-cases/) - Concrete example scenarios that make use of Verifiable Credentials

#### Open Source Building Blocks

- [JavaScript: vc.js](https://github.com/transmute-industries/vc.js) - support Verifiable Credentials in JavaScript.
- [JavaScript: vc-js](https://github.com/digitalbazaar/vc-js) - a Javascript library for issuing and verifying Verifiable Credentials

## Networks

- [Sovrin Network](https://sovrin.org/) - A decentralized identity network based on Hyperledger Indy

## Projects and Applications

### Hyperledger Aries

- [Hyperledger Aries](https://github.com/hyperledger/aries) - Toolkit designed for creating, transmitting and storing verifiable digital credentials.
  - [Hyperledger Aries (SSI Meetup)](https://ssimeetup.org/hyperledger-aries-open-source-interoperable-identity-solutions-nathan-george-webinar-30/) - A SSI Meetup webinar by Nathan George about Hyperledger Aries
- [Becoming a Hyperledger Aries Developer Course](https://www.edx.org/course/becoming-a-hyperledger-aries-developer)
- [Becoming an Indy/Aries Developer](https://github.com/hyperledger/aries-cloudagent-python/blob/master/docs/GettingStartedAriesDev/README.md)

#### Open Source Building Blocks

- [Aries Cloud Agent Python](https://github.com/hyperledger/aries-cloudagent-python)
- [Aries Framework .NET](https://github.com/hyperledger/aries-framework-dotnet)
- [Aries Framework Go](https://github.com/hyperledger/aries-framework-go)
- [Aries Framework JavaScript](https://github.com/hyperledger/aries-framework-javascript)
- [Aries Mobile Agent React Native](https://github.com/animo/aries-mobile-agent-react-native)
- [Aries Mobile Agent Xamarin](https://github.com/hyperledger/aries-mobileagent-xamarin)
- [Aries SDK Ruby](https://github.com/hyperledger/aries-sdk-ruby)
- [Aries Toolbox](https://github.com/hyperledger/aries-toolbox) - Tools for developing agents and testing that they are compatible with other agents in the ecosystem.

#### Implementations

- [Trinsic](https://trinsic.id/) - builds on top of Aries Framework .NET
  - [Trinsic Studio - End-to-end Self Sovereign Identity Platform](https://trinsic.id/trinsic-studio/)
  - [Trinsic Wallet - Mobile Wallet App](https://trinsic.id/trinsic-wallet/)
  - [Mobile Wallet SDK](https://trinsic.id/mobile-wallet-sdk/)
- [The Verifiable Organizations Network (VON)](https://github.com/bcgov/von) - built on top of Aries Cloud Agent Python
- [Evernym](https://www.evernym.com/)
  - [Verity - Platform for Issuing and Verifying Digital Credentials](https://www.evernym.com/products/)
  - [Connect.Me - Mobile Wallet App](https://www.evernym.com/products/)
  - [Mobile Wallet SDK](https://www.evernym.com/products/)

### Hyperledger Indy

- [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy) - Distributed Ledger built for decentralized identity.

### IOTA

- [The Case For a Unified Identity](https://files.iota.org/comms/IOTA_The_Case_for_a_Unified_Identity.pdf)

#### Open Source Building Blocks

- [IOTA Identity](https://github.com/iotaledger/identity.rs)

#### Implementations

- [Selv - Mobile Wallet App](https://selv.iota.org/demo/app)

### Universal Ledger Agent

- [Universal Ledger Agent](https://github.com/rabobank-blockchain/universal-ledger-agent) - Framework for managing Self-Sovereign Identity data.
  - [Introduction Paper](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/universal-ledger-agent.md)
  - [Zero-Knowledge Proofs](https://github.com/WebOfTrustInfo/rwot9-prague/blob/master/topics-and-advance-readings/zero-knowledge-proofs-and-vc-in-social-housing.md)

### uPort

- [uPort](https://www.uport.me/) - A self-sovereign identity and user-centric data platform

## Papers, Books and Articles

## Inspiration

- [Ideology & Architecture of Self-Sovereign Identity (Odyssey Connect 2020)](https://youtu.be/JzM_Brpk95E) - Historical, technological and ethical aspects of Self-Sovereign Identity.
- [The Invisible Man (TEDxAmsterdam 2018)](https://www.youtube.com/watch?v=6OfcbgcxGNM) - The story of Toufic El-Rjula, a refugee that lost his birth certificate. He now pledges for digital identities using SSI which he tries to achieve with his company [Tykn](https://tykn.tech).

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Animo Solutions has waived all copyright and
related or neighboring rights to this work.
