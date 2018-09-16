# webbitcoinwallet
This project implements an online bitcoin wallet service with Node.JS using the bitcoinJS library and blockcypher blockchain explorer. Because of this, you do not have to host the entire blockchain (100+ GB) on a single server, making it possible to run a bitcoin service on a server without alot of storage. (For example, the free Heroku tier).

The server itself does not store private keys. These are passed through Https to the client application.
