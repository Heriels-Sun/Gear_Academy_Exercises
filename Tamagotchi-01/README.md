# Tamagotchi - 01

## How to Build this smart contract

This is the smart contract for the tamagotchi 01 exercise.
All you need to do to build it is follow the next steps.

Also if you want, we have the smart contract already in the Vara Tesnet 😄

<a style="color: #ffff00; font-size: 28px; text-decoration: none;" target="_blank" href="https://idea.gear-tech.io/programs/0x039d22a2ea92ce7359e7603ea2a1c1ab3dbe931826416978b0c739ecc6170c24?node=wss%3A%2F%2Ftestnet.vara-network.io">
Tamagotchi - 01 🔗</a></br>

**All the commands below are for Linux or Mac**

### Copy the Github repository

First you need to copy the repository of the proyect using the next command.
> Note: You need to have installed _git_

```shell
git clone https://github.com/Heriels-Sun/Gear_Academy_Exercises.git
```

### ⚙️ Install Rust

You also need to have installed _Rust_, and the necessary tools for build

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```shell
rustup toolchain add nightly

rustup target add wasm32-unknown-unknown --toolchain nightly
```

### 🏗️ Build Smart Contract

With all installed and with the repository, you must be in the right directory to build the smasrt contract.

```shell
cd Tamagotchi-01\
```

Now, you are ready to build the smart contract 👌

```shell
cargo build --release
```

### ✅ Run tests

Also, you can run all the test prepared for this smart contract 🧪

```shell
cargo test --release
```
