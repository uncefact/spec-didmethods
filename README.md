# spec-didmethods

Guidance for implementers on the use of DID methods for verifiable credentials

# Status

Raw - work has not yet started

# Goals

Decentralised identifiers (DIDs) play a key role in the issuing and verification of linked credentials. For example, in an AEO mutual recognition use case, a key dependency is the cryptographically verifiable connection between the subject of one VC and the issuer of the next. 

The W3C DID specification is designed to allow market innovation to drive DID methods (eg did:key, did:web, did:ethr, etc).  Whilst this is a good decision in principle, it has led to a proliferation of candidate DID methods – a total of 134 methods are listed in https://w3c.github.io/did-spec-registries/#did-methods at the time of writing this document. This proliferation presents a challenge for implementers. Which methods should be used for which purpose?  Which methods are sufficiently stable and trustworthy for production implementations?  The short answer is that only a small handful of the 134 methods are suitable for implementation. 

This repository provides guidance for implementers on the choice of DID methods.

