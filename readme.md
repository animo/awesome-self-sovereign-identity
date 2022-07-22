# Awesome Self-Sovereign Identity [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of self-sovereign identity resources.

Self-sovereign identity (SSI) is a term used to describe the digital movement that recognizes an individual should own and control their identity without the intervening administrative authorities. SSI allows people to interact in the digital world with the same freedom and capacity for trust as they do in the offline world (by [The Sovrin Foundation](https://sovrin.org/faq/what-is-self-sovereign-identity)).

## Contents

<!--lint ignore awesome-toc-->
- [Contents](#contents)
- [🤔 Philosophy & Concepts](#-philosophy--concepts)
- [🏛️ Political, Legal and Ethical Implications](#️-political-legal-and-ethical-implications)
- [📄 Technical Specifications](#-technical-specifications)
- [🛠 Tools & Technologies](#-tools--technologies)
- [💁‍♂️ Products & Services](#️-products--services)
- [📡 Networks](#-networks)
- [📚 Resources](#-resources)
- [📆 Events](#-events)
- [💪 Contribute](#-contribute)
- [🖋️ License](#️-license)

## 🤔 Philosophy & Concepts

To understand the philosophy of self-sovereign identity these starting guides and explanations have been collected.

- [Self-Sovereign Identity: The Ultimate Beginners Guide!](https://tykn.tech/self-sovereign-identity/) - Complete starters guide to the concepts and technology of SSI.
- [A Beginner's Guide to Self-Sovereign Identity](https://domilabs.io/beginners-guide-ssi/) - Non technical article on the concept of SSI and its pillars and values.
- [Self-Sovereign Identity (SSI) Explained](https://www.youtube.com/watch?v=kJAapPG_jBY) - Illustrated video that explains SSI in 3 minutes using two examples. 
- [Self-Sovereign Identity (SSI) Foam Figure Explainer](https://www.youtube.com/watch?v=81GkdBRmsbE) - An explanation of SSI using an example of renting a car. Includes a comparison of SSI and traditional identity models.
- [Decentralized Identity Explained](https://www.youtube.com/watch?v=Ew-_F-OtDFI) - An explanation of what decentralized identity is.
- [The Path To Self-Sovereign Identity](http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html) - Article that originally explained and coined the term self-sovereign identity, starts with different identity models as a whole.
- [A Technology-free definition of SSI](https://github.com/jandrieu/rebooting-the-web-of-trust-fall2016/raw/master/topics-and-advance-readings/a-technology-free-definition-of-self-sovereign-identity.pdf) - Topic paper for Rebooting Web of Trust III.
- [Why Self-Sovereign Identity is Important](https://github.com/WebOfTrustInfo/rwot7-toronto/blob/master/final-documents/convincing-dad.md) - How to convince your dad, your sister, your nephew and your best friend that SSI is a good idea.
- [7 Myths of Self-sovereign Identity](https://medium.com/evernym/7-myths-of-self-sovereign-identity-67aea7416b1) - Seven myths of SSI by Timmothy Ruff.
- [19 FAQs on Verifiable Credentials and Self-Sovereign Identity](https://academy.affinidi.com/faqs-on-verifiable-credentials-and-self-sovereign-identity-3c3a505878bc) - Definition based FAQ that explains important SSI terminology and shows what a DID and VC actually look like.
- [Ideology & Architecture of Self-Sovereign Identity](https://www.youtube.com/watch?v=JzM_Brpk95E&feature=youtu.be) - Insights and reflections around historical, technological and ethical aspects of SSI.
- [Self-Sovereign Identity: Decentralized digital identity and verifiable credentials](https://livebook.manning.com/book/self-sovereign-identity/welcome/v-11/) - Manning book on SSI containing both high- and low-level concepts and explanations. 
- [The Invisible Man, TEDxAmsterdam](https://www.youtube.com/watch?v=6OfcbgcxGNM) - The story of Toufic El-Rjula, a refugee that lost his birth certificate. He now pledges for digital identities using SSI.
- [Web Of Trust Self-Sovereign Identity Repository](https://github.com/WebOfTrustInfo/self-sovereign-identity) - Articles and documents associated with designing and implementing identity technology using self-sovereign identity principles.
- [DIF FAQ](https://identity.foundation/faq/) - The Decentralized Identity Foundation's general-purpose knowledgebase, uses color coding to indicate presumed level of familiarity.

## 🏛️ Political, Legal and Ethical Implications

- [The Growth Factors of Self-Sovereign Identity Solutions in Europe](https://www.researchgate.net/publication/349899411_The_growth_factors_of_self-sovereign_identity_solutions_in_Europe) - Thesis on the business, technology, legal and governance aspects of SSI. 
- [Sovereignty, privacy, and ethics in blockchain-based identity management systems](https://research.tudelft.nl/en/publications/sovereignty-privacy-and-ethics-in-blockchain-based-identity-manag) - Article about the ethics of self-sovereign identity systems. 
- [Self-Sovereignity for Refugees? The Contested Horizons of Digital Identity](https://www.tandfonline.com/doi/pdf/10.1080/14650045.2020.1823836) - Article that examines the implications of SSI for border politics and migration management. 

## 📄 Technical Specifications

Here you will find an overview of the technical specifications, grouped by level and sorted by community.

An overview of the technical specifications can be found in [this simplified map](https://github.com/decentralized-identity/decentralized-identity.github.io/blob/master/assets/map-of-adjacent-orgs-and-specs--sept-2020--one-sided.pdf) and [here](https://github.com/decentralized-identity/decentralized-identity.github.io/blob/master/assets/crosscommunity-architecture-survey-oct-2020.pdf) in a more detailed fashion.  

### Verifiable Credentials / Trusted Data Storage & Exchange

#### W3C
- [W3C Verifiable Credentials](https://www.w3.org/TR/vc-data-model/) - Specification of verifiable credentials (VCs).
- [W3C Verifiable Credentials Implementation Guidelines](https://www.w3.org/TR/vc-imp-guide/) - Implementation guidelines for verifiable credentials.

---
- [Data Integrity](https://w3c-ccg.github.io/data-integrity-spec/) - Specifications describing mechanisms for ensuring the authenticity and integrity of structured digital documents using cryptography, such as digital signatures and other digital mathematical proofs (used to be LD Proofs).

#### Decentralized Identity Foundation (DIF)
- [DIF Presentation Exchange](https://identity.foundation/presentation-exchange/) - Credential format and transport agnostic specification to articulate proof requirements and submit proofs.
- [DIF Credential Manifest](https://identity.foundation/credential-manifest) - Common data format for describing the inputs a subject must provide for credential issuance.

#### Hyperledger Foundation
- [Hyperledger Indy Improvement Proposals](https://github.com/hyperledger/indy-hipe/blob/master/index.md) - Specifications of Indy protocols and standards.
- [Hyperledger Aries RFCs](https://github.com/hyperledger/aries-rfcs/tree/main/features)

### DID Communication (DIDComm) and Sub-protocols
#### W3C
- [CHAPI](https://w3c-ccg.github.io/credential-handler-api/) - Credential Handler API: specification defining capabilities that enable third-party Web applications to handle credential requests and storage events.

#### DIF
- [DIF DIDComm Messaging (v2)](https://identity.foundation/didcomm-messaging/spec) - A secure, private communication methodology built atop the decentralized design of DIDs.

#### Hyperledger Foundation
- [x] [Aries RFC 0005 : DIDComm v1](https://github.com/hyperledger/aries-rfcs/tree/main/concepts/0005-didcomm) - First version of the DIDComm protocol spec. Refer to v2 specs.

### DIDs, Anchors and Registries
#### W3C
- [Decentralized Identifiers](https://www.w3.org/TR/did-core/) - Core specification of decentralized identifiers (DIDs).
- [Decentralized Identifier Resolution](https://w3c-ccg.github.io/did-resolution/) - Specification related to algorithms and guidelines for resolving DIDs and dereferencing DID URLs.
- [DID Specification Registries](https://www.w3.org/TR/did-spec-registries/) - Official registry for all known global parameters, properties, and values used by the Decentralized Identifier ecosystem
	- [did:key Method](https://w3c-ccg.github.io/did-method-key/) - Specification describing a non-registry based DID Method based on expanding a cryptographic public key into a DID Document.

--- 

- [WebKMS](https://w3c-ccg.github.io/webkms/) - Cryptographic Key Management Systems for the Web.


#### DIF
- [SideTree](https://identity.foundation/sidetree/spec/) - Protocol for creating scalable DID networks that can run atop any existing decentralized anchoring system.
- [Key Event Receipt Infrastructure (KERI) collected resources](https://keri.one/keri-resources/) - Collected list of resources on Key Event Receipt Infrastructure.

## 🛠 Tools & Technologies

### Hyperledger Foundation

- [Hyperledger Aries](https://www.hyperledger.org/use/aries) - Shared, reusable, interoperable tool kit designed for initiatives and solutions focused on creating, transmitting and storing verifiable digital credentials.
	- [Aries Toolbox](https://github.com/hyperledger/aries-toolbox) - Tools for developing agents and testing that they are compatible with other agents in the ecosystem.
	- [Aries Framework .NET](https://github.com/hyperledger/aries-framework-dotnet) - Provides a universal library for building Aries SSI applications for the cloud, mobile and IoT stack.
	- [Aries Framework Go](https://github.com/hyperledger/aries-framework-go) - A flexible toolkit to enable the usage of DIDs, DIDComm and verifiable credential exchange.
	- [Aries Framework JavaScript](https://github.com/hyperledger/aries-framework-javascript) - A framework for building SSI agents and DIDComm services for desktop, mobile and in the cloud, built using TypeScript.
	- [Aries Mobile Agent React Native](https://github.com/hyperledger/aries-mobile-agent-react-native) - An open source Aries mobile agent build with React Native and Aries Framework JavaScript.
	- [Aries Mobile Agent Xamarin](https://github.com/hyperledger/aries-mobileagent-xamarin) - An open source Aries mobile agent build with Xamarin and Aries Framework .NET.
	- [Aries Cloud Agent Python](https://github.com/hyperledger/aries-cloudagent-python) - An easy to use Aries agent for building SSI services using any language that supports sending/receiving HTTP requests.
- [Hyperledger Indy](https://www.hyperledger.org/use/hyperledger-indy) - Tools, libraries, and reusable components for providing digital identities rooted on blockchains or other distributed ledgers
	- [Indy SDK](https://github.com/hyperledger/indy-sdk) - Everything needed to build applications that interact with an Indy distributed identity ledger.
- [Hyperledger Fabric](https://www.hyperledger.org/use/fabric) - Enterprise-grade permissioned distributed ledger framework for developing solutions and applications.
- [Hyperledger Besu](https://www.hyperledger.org/use/besu) - Ethereum client designed to be enterprise-friendly for both public and private permissioned network use cases.
- [Hyperledger Ursa](https://www.hyperledger.org/use/ursa) - Shared cryptographic library, it enables implementations to avoid duplicating other cryptographic work and hopefully increase security in the process.

### DIF
- [ION](https://github.com/decentralized-identity/ion) - Public, permissionless, DID network that implements the blockchain-agnostic Sidetree protocol on top of Bitcoin (as a 'Layer 2' overlay) to support DIDs/DPKI (Decentralized Public Key Infrastructure) at scale.
- [sidetree.js](https://github.com/transmute-industries/sidetree.js) - Simple-as-possible TypeScript implementation of the Sidetree version 1.0 protocol.
- [DIDComm Implementations](https://github.com/decentralized-identity/didcomm-messaging/#implementations) - Links to some implementations of the DIDComm v2 spec.
- [Universal DID Resolver](https://github.com/decentralized-identity/universal-resolver) - Universal DID resolver implementation and method specific drivers.
- [Universal DID Registrar](https://github.com/decentralized-identity/universal-registrar) - Universal DID registrar implementation and method specific drivers.
- [JavaScript: DID Resolver](https://github.com/decentralized-identity/did-resolver) - A simple common interface for JavaScript applications to resolve DID documents from Decentralized Identifiers (DIDs).
  - [ethr DID Resolver](https://github.com/decentralized-identity/ethr-did-resolver) - Use Ethereum addresses as fully self managed Decentralized Identifiers and wrap them in a DID Document.
  - [web DID Resolver](https://github.com/decentralized-identity/web-did-resolver) - Use domains accessed through https as Decentralized Identifiers and retrieve an associated DID Document.
- [Rust: did-key.rs](https://github.com/decentralized-identity/did-key.rs) - Provide basic support for `did:key` methods.

### Others
- [IOTA Identity](https://github.com/iotaledger/identity.rs) - Implementation of the decentralized identity standards such as DIDs and VCs by W3C for the IOTA Tangle.
- [JavaScript: DID Client (did-io)](https://github.com/digitalbazaar/did-io) - A DID resolution library for JavaScript.
- [JavaScript: DID](https://github.com/ceramicnetwork/js-did) - A simple library to interact with DIDs that conform to the DID-provider interface.
- [JavaScript: vc-js](https://github.com/digitalbazaar/vc-js) - A JavaScript library for issuing and verifying Verifiable Credentials.
- [JavaScript: vc.js](https://github.com/transmute-industries/vc.js) - Support Verifiable Credentials in JavaScript.

## 💁‍♂️ Products & Services

Notable self-sovereign identity products and services that are in production.

- [esatus Wallet](https://esatus.com/esatus-ssi-wallet-app-ab-sofort-fuer-ios-und-android-verfuegbar/?lang=en) - A mobile wallet by esatus.
- [esatus SeLF](https://self-ssi.com/en/) - An institutional agent by esatus.
- [Evernym Products and Services](https://www.evernym.com/products/) - Various self-sovereign identity projects by Evernym, such as a mobile wallet, a mobile wallet SDK and an end-to-end SSI platform.
- [Lissi Wallet](https://lissi.id/mobile) - A mobile wallet by Lissi.
- [Lissi Cloud Agent](https://lissi.id/institutions) - An institutional agent by Lissi hosted in the cloud.
- [Spherity Cloud Identity Wallet](https://spherity.com/cloud-identity-wallet/) - An institutional agent by Spherity hosted in the cloud.
- [Tykn Products and Services](https://tykn.tech/product-suite/) - Various self-sovereign identity projects by Tykn, such as a mobile wallet, a web wallet and an end-to-end SSI platform.
- [Trinsic Studio](https://trinsic.id/trinsic-studio/) - An end-to-end self sovereign identity platform by Trinsic.
- [Trinsic Wallet](https://trinsic.id/trinsic-wallet/) - A mobile wallet by Trinsic.
- [Trinsic Mobile Wallet SDK](https://trinsic.id/mobile-wallet-sdk/) - A SDK by Trinsic to extend self-sovereign identity to mobile app.
- [uPort](https://www.uport.me/) - A self-sovereign identity and user-centric data platform.

## 📡 Networks

- [Sovrin Network](https://sovrin.org/) - A decentralized identity network based on Hyperledger Indy.
- [Cheqd Network](https://www.cheqd.io) - An identity network that enables payment rails between issuer, holder & verifier

## 📚 Resources

Resources that are not about specific concepts such as meetups, newsletters, etc.

- [In Search of Self-Sovereign Identity Leveraging Blockchain technology](https://ieeexplore.ieee.org/document/8776589) - Article about finding a mathematical definition for SSI.
- [Verifiable Credentials Use Cases](https://www.w3.org/TR/vc-use-cases/) - Concrete example scenarios that make use of Verifiable Credentials.
- [Self-Sovereign Identity: Why Blockchain?](https://www.ibm.com/blogs/blockchain/2018/06/self-sovereign-identity-why-blockchain/) - Exploration of the place blockchain has in SSI.
- [W3C DID use cases](https://www.w3.org/TR/did-use-cases/) - List W3C requirements and specifications.
- [Matching Identity Management Solutions to Self-Sovereign Identity Principles](https://www.slideshare.net/TommyKoens/matching-identity-management-solutions-to-selfsovereign-identity-principles) - A list and comparison of nearly 50 identity management solutions based on SSI requirements.
- [Become a Hyperledger Aries Developer](https://www.edx.org/course/becoming-a-hyperledger-aries-developer) - Quick course on how to get started with Hyperledger Aries.
- [Become a Hyperledger Indy Developer](https://github.com/hyperledger/aries-cloudagent-python/blob/main/docs/GettingStartedAriesDev/README.md) - Quick course on how to get started with Hyperledger Indy.
- [Identosphere](https://newsletter.identosphere.net) - A newsletter providing the latest news in decentralized identity to your inbox each week.
- [Technometrica](http://news.windley.com) - Phil Windley's attempt to make sense of the technology that interests him.
- [Tykn newsletter](https://tykn.tech/subscribe-newsletter) - A monthly curated compilation of digital identity content.
- [Verifiable Credentials 101 (SSI Meetup)](https://ssimeetup.org/verifiable-credentials-101-ssi-tyler-ruff-webinar-11/) - A SSI Meetup webinar by Tyler Ruff about VCs.
- [SSI Wallets](https://github.com/Gimly-Blockchain/ssi-wallets) - An overview of SSI wallets, by [Gimly](https://gimly.io)

## 📆 Events

Notable events concerning self-sovereign identity.

- [SSIMeetup](https://ssimeetup.org) - An open, collaborative community to help SSI evangelists around the world, independent of company interests or standards.
- [Internet Identity Workshop](https://internetidentityworkshop.com/) - An event that is held twice every year that discusses user-centric identity related topics and technologies.

## 💪 Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## 🖋️ License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Animo Solutions has waived all copyright and
related or neighboring rights to this work.

<!-- ## Other / Uncategorized


- [Decentralized Identity Foundation (DIF)](https://identity.foundation/) - An engineering-driven organization focused on developing the foundational elements necessary to establish an open ecosystem for decentralized identity and ensure interoperability between all participants.
- [Hyperledger Foundation](https://www.hyperledger.org/) - Open source community focused on developing SSI frameworks, tools and libraries.
- [Trust over IP Foundation (TOIP)](https://trustoverip.org/) - Foundation aimed at defining SSI architecture.
- W3C
- d

- [The Verifiable Organizations Network (VON)](https://github.com/bcgov/von)

## Awesome list

### Mentione badge

```
[![Mentioned in Awesome Self-Sovereign Identity](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/animo/awesome-self-sovereign-identity)
```

### Awesome linter

https://github.com/sindresorhus/awesome-lint -->
