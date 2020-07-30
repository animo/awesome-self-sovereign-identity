# Awesome Self-Sovereign Identity

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of self-sovereign identity resources.

Self-sovereign identity (SSI) is a term used to describe the digital movement that recognizes an individual should own and control their identity without the intervening administrative authorities. SSI allows people to interact in the digital world with the same freedom and capacity for trust as they do in the offline world. (by [Sovrin Foundation](https://sovrin.org/faq/what-is-self-sovereign-identity))

## Contents

- [Awesome Self-Sovereign Identity](#awesome-self-sovereign-identity)
  - [Contents](#contents)
  - [Basic Introduction](#basic-introduction)
  - [Specifications](#specifications)
    - [Decentralized Identifiers (DIDs)](#decentralized-identifiers-dids)
    - [Verifiable Credentials (VCs)](#verifiable-credentials-vcs)
  - [Networks](#networks)
  - [Projects and Applications](#projects-and-applications)
    - [Hyperledger Indy](#hyperledger-indy)
    - [Hyperledger Aries](#hyperledger-aries)
        - [Open Source Building Blocks](#open-source-building-blocks)
        - [Implementations](#implementations)
    - [uPort](#uport)
    - [Universal Ledger Agent](#universal-ledger-agent)
  - [Papers, Books and Articles](#papers-books-and-articles)
  - [Inspiration](#inspiration)
  - [Contribute](#contribute)
  - [License](#license)

## Basic Introduction

- [Introduction to Self-Sovereign Identity and Its 10 Guiding Principles](https://medium.com/metadium/introduction-to-self-sovereign-identity-and-its-10-guiding-principles-97c1ba603872) - Introductory medium article on SSI and it's 10 principles
- [Web Of Trust Self-Sovereign Identity Repository](https://github.com/WebOfTrustInfo/self-sovereign-identity) - Articles and documents associated with designing and implementing identity technology using self-sovereign identity principles
  - [10 Principles of Self-Sovereign Identity](https://github.com/WebOfTrustInfo/self-sovereign-identity/blob/master/self-sovereign-identity-principles.md) - by Christopher Allen
  - [7 Myths of Self-Sovereign Identity](https://github.com/WebOfTrustInfo/self-sovereign-identity/blob/master/7-myths-of-self-sovereign-identity.md) - by Timmothy Ruff

* [Decentralized Identity Foundation](https://identity.foundation) - Focused on developing the foundational components of an open, standards-based, decentralized identity ecosystem
* [SSI Meetup Webinars](https://ssimeetup.org/blog) - Webinars about Self-Sovereign Identity
* [Matching Identity Management Solutions to Self-Sovereign Identity Principles](https://www.slideshare.net/TommyKoens/matching-identity-management-solutions-to-selfsovereign-identity-principles/1) - An analysis of almost 50 (blockchain based) digital identity solutions matched against SSI principles

## Specifications

> TODO: ssi is a concept, based on the same principles. But all tools use the same underlying technology. mostly set by the W3C and DIF

### Decentralized Identifiers (DIDs)

- [Official W3C Specification](https://w3c-ccg.github.io/did-spec/)
- [Decentralized Identifiers 101 (SSI Meetup)](https://ssimeetup.org/decentralized-identifiers-did-fundamental-block-self-sovereign-identity-drummond-reed-webinar-2/) - A SSI Meetup webinar by Drummond Reed about DIDs
- [Uniresolver](https://uniresolver.io/) - Online Universal DID Resolver

### Verifiable Credentials (VCs)

- [Official W3C Data Model](https://www.w3.org/TR/vc-data-model/)
- [Verifiable Credentials 101 (SSI Meetup)](https://ssimeetup.org/verifiable-credentials-101-ssi-tyler-ruff-webinar-11/) - A SSI Meetup webinar by Tyler Ruff about VCs
- [Verifiable Credentials Use Cases](https://www.w3.org/TR/vc-use-cases/) - Concrete example scenarios that make use of Verifiable Credentials

## Networks

- [Sovrin Network](https://sovrin.org/) - A decentralized identity network based on Hyperledger Indy

## Projects and Applications

### Hyperledger Indy

- node, sdk, ...

- [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy) - Distributed Ledger built for decentralized identity.
-

### Hyperledger Aries

- https://www.edx.org/course/becoming-a-hyperledger-aries-developer
- https://github.com/hyperledger/aries-cloudagent-python/blob/master/docs/GettingStartedAriesDev/README.md
- [Hyperledger Aries](https://www.hyperledger.org/projects/aries) - Toolkit designed for creating, transmitting and storing verifiable digital credentials.
  - [Hyperledger Aries (SSI Meetup)](https://ssimeetup.org/hyperledger-aries-open-source-interoperable-identity-solutions-nathan-george-webinar-30/) - A SSI Meetup webinar by Nathan George about Hyperledger Aries

##### Open Source Building Blocks

- [Aries Cloud Agent Python]
- [Aries Framework .NET]
- [Aries Framework Go]
- [Aries Framework JavaScript]
- [Aries Mobile Agent Xamarin]
- [Aries SDK Ruby]

##### Implementations

- [Trinsic Cloud Platform] - built on top of Aries Framework .NET
  - [iOS Wallet]
  - [Android Wallet]
  - [Cloud Agent]
- [VON Network] - built on top of Aries Cloud Agent Python
- [esatus]
- [Evernym]
  - Verity
  - Connect.Me

### uPort

- [uPort](https://www.uport.me/) - A self-sovereign identity and user-centric data platform

### Universal Ledger Agent

- [Universal Ledger Agent](https://github.com/rabobank-blockchain/universal-ledger-agent) - Framework for managing Self-Sovereign Identity data.
  - [Introduction Paper](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/universal-ledger-agent.md)
  - [Zero-Knowledge Proofs](https://github.com/WebOfTrustInfo/rwot9-prague/blob/master/topics-and-advance-readings/zero-knowledge-proofs-and-vc-in-social-housing.md)

## Papers, Books and Articles

## Inspiration

- [The Invisible Man (TEDxAmsterdam)](https://www.youtube.com/watch?v=6OfcbgcxGNM) - The story of Toufic El-Rjula, a refugee that lost his birth certificate. He now pledges for digital identities using SSI which he tries to achieve with his company [Tykn](https://tykn.tech).

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Karim Stekelenburg &amp; Timo Glastra have waived all copyright and
related or neighboring rights to this work.
