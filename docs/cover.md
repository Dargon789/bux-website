# **BUX**

> Best-practice Bitcoin UTXO & xPub Management Suite

#### What is it?

BUX Engine is a Web3 go library for native Bitcoin integration using best-practices. It can dramatically improve the speed of your app if you’re currently relying on 3rd party APIs for UTXO information.

#### How does it work?

BUX keeps a tight xPub state for you by recording each transaction you make. This means there’s no need for UTXO lookups from 3rd party API services. It does not need or use private keys. It tracks and caches UTXOs, address information, and metadata based on your extended public keys and their transaction history. It provides templates called drafts that simplify transaction creation. When a draft is made it can reserve UTXOs to prevent inadvertant double spend attempts. You just sign the inputs and send it back to BUX to record and broadcast in one shot.

[Learn More](#bux-tldr)
[Get Started](getting_started.md)

![color](#ecfcff)
