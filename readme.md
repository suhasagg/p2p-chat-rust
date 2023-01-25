# P2P Chat Client

This is a simple demonstration of a peer to peer chat client, written entirely in rust utilising the libp2p library.

## Demo

On two seperate computers connected to the same LAN, run:
```sh
git clone https://github.com/suhasagg/p2p-chat-rust
cd rust-p2p-chat
cargo run
```

The peers should discover one another, and you can message between them. The last 32 messages of history are stored if one peer disconnects.

## Test
```sh
cargo test
```