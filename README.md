## PolkadotKit for iOS, Android - Device Native Light Client Wrappers

1.1 Overview

Implement Device Native light client packages for Apple and Android product platforms.

Current light client solutions require either third-party frameworks or a JavaScript runtime environment. The PolkadotKit project removes the need for this additional layer. This will make it easier for native mobile developers to create apps that operate in a trustless decentralized manner.

This will complete the currently missing first solution to [embedding smoldot into a mobile application](https://github.com/smol-dot/smoldot?tab=readme-ov-file#can-i-embed-smoldot-into-a-mobile-application-or-an-application-in-general).

1.2 Details

Produce Swift and Kotlin packages, as well as the Rust scaffolding code and bindings needed to call into the smoldot Rust library.

<< IMAGE >>

This project will implement the code bounded by the purple box in the diagram above.

1.3 Implementation

**Smoldot Swift**

* Published to [Swift Package Index](https://swiftpackageindex.com/finsig/smoldot-swift).
*  [GitHub repository](https://github.com/finsig/smoldot-swift)
* [Reference documentation](https://finsig.github.io/smoldot-swift/documentation/smoldotswift/)
* [Example App](https://github.com/finsig/smoldot-swift-example)

**Smoldot Kotlin**

* Published to [Maven Central Repository](https://swiftpackageindex.com/finsig/smoldot-swift).
* [GitHub repository](https://github.com/finsig/smoldot-kotlin)
* [Reference documentation](https://finsig.github.io/smoldot-kotlin/)
* [Example App](https://github.com/finsig/smoldot-kotlin/smoldotkotlinexample)

