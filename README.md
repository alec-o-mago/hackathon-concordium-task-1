# Concordium Hackathon - Task 1

## Installing Rust and Cargo

I downloaded Rustup from https://win.rustup.rs/x86_64 and ran the installer:

![01](/images/01.png)

![02](/images/02.png)

Then I copy-pasted this command in the terminal to install Wasm:

```
rustup target add wasm32-unknown-unknown
```

![03](/images/03.png)

Then I Installed Cargo-Concordium from https://distribution.concordium.software/tools/windows/signed/cargo-concordium_2.7.0.exe, renamed it to "cargo-concordium.exe", and moved it to my ".cargo\bin" folder.
Giving an individual file permission to run does not apply to Windows.

Then I verified the instalation with:

```
cargo concordium --help
```

![04](/images/04.png)


## Installing Concordium Client

I downloaded Concordium Client from https://distribution.concordium.software/tools/windows/signed/concordium-client_5.0.2-0.exe, renamed to "concordium-client.exe" moved it to a folder on one of my %PATH% folders.

Then I verified the instalation with:

```
concordium-client --help
```

![05](/images/05.png)

## Running testnet code

I connected to the public node with the following command:

```
concordium-client consensus status --grpc-port 10000 --grpc-ip node.testnet.concordium.com
```

![06](/images/06.png)

## Setting up a wallet

I installed the Concordium Wallet on Brave Browser from the Chrome Web Store


## Importing the key


