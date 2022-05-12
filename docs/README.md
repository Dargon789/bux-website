## What is it?

> BUX Engine is a Web3 go library for native Bitcoin integration using best-practices. It can dramatically improve the speed of your app if you’re currently relying on 3rd party APIs for UTXO information.

## How does it work?

> BUX keeps a tight xPub state for you by recording each transaction you make. This means there’s no need for UTXO lookups from 3rd party API services. It does not need or use private keys. It tracks and caches UTXOs, address information, and metadata based on your extended public keys and their transaction history. It provides templates called drafts that simplify transaction creation. When a draft is made it can reserve UTXOs to prevent inadvertant double spend attempts. You just sign the inputs and send it back to BUX to record and broadcast in one shot.

## Why is it needed?

> When you use most Bitcoin wallets, you will notice your deposit address changes each time you use it. Bitcoin wallets rotate addresses for enhanced privacy. They use your master key to derive many child keys and addresses.

> It is easy to build Bitcoin apps that use a single address instead and bypass all of this, but they will have inherantly weaker privacy and many block explorers and other apps may fail when there are long transaction histories associated with a single address.

> In order to build a Bitcoin app that is fast and reliable, it should track which addresses have been used, which unspent outputs are committed and which are available for creating new transactions. This is what BUX does.

## Disclaimer

> BUX is still considered "ALPHA" and should not be used in production until a major v1.0.0 is released.

## Stay Tuned!

Incoming awesomeness, stay tuned :)
