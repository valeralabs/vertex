<h1 align="center"> Vertex ⚔️ </h1>

<p align="center">Vertex is a modern runtime for decentralised, user-owned infrastructure.</p>

## Features 🗞️

- **Written in Rust** ☄️ - codebase is very performant, native to all platforms and architectures and safe
- **Powered by WebAssembly and WASI** 💪 - capable of running practically anything, from Bitcoin Core to web servers to databases, written in any language you want (that compiles to WASM/WASI)
- **Hyperfast** 🏎️ - Vertex runs ~20% slower than native code (performance will increase over time) due to lack of a virtual machine or operating system
- **Ultrasecure** 💂 - features available to apps have to be whitelisted, Vertex uses capability-based security
- **Powerful** 👾 - it's built to scale, so whether you have a Raspberry Pi or a mini-datacenter, Vertex will use all resources at its disposal

### In the runtime

Vertex not only acts a simple runtime, but has advanced features. It has built-in services for Lightlane networking (anonymising all traffic, handles encryption and routing in the runtime), databases and high-performance storage, as well as AI services for monitoring services ondevice. Everything runs locally, nothing goes to the "cloud". 

Apps are stored on P2P nodes, with indexing happening with a Stacks smart contract. Everything is trustless, decentralised and encrypted. Extreme privacy and security by default, while beating other runtimes for features and usability. 

- File system, OS-level features (env vars, etc)
- GPU, ASIC support
- Storage

## Vertex vs Docker

- Booting up (aka, cold starts) 💤 - 100x faster on Vertex than Docker
- Runtime performance ⏱️ - 10-50% faster than Docker due to the lack of virtualisation
- Tiny apps 🐭 - apps on Vertex are much smaller, usually <10MB, whereas Docker images will regularly exceed hundreds of MB
- More secure 🔒 - Vertex uses a capability-based security policy, which is a restricted sandbox by default
