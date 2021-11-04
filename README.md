# Vertex ⚔️

<p align="center">Vertex is a modern runtime for decentralised infrastructure.</p>

## Features 🗞️

- **Written in Rust** ☄️ - codebase is very performant, native to all platforms and architectures and safe
- **Powered by WebAssembly and WASI** 💪 - capable of running practically anything, from Bitcoin Core to web servers to databases, written in any language you want (that compiles to WASM/WASI)
- **Hyperfast** 🏎️ - Vertex runs ~20% slower than native code (performance will increase over time) due to lack of a virtual machine or operating system
- **Ultrasecure** 💂 - features available to apps have to be whitelisted, Vertex uses capability-based security
- **Powerful** 👾 - it's built to scale, so whether you have a Raspberry Pi or a mini-datacenter, Vertex will use all resources at its disposal

## Vertex vs Docker

- Booting up (aka, cold starts) 💤 - 100x faster on Vertex than Docker
- Runtime performance ⏱️ - 10-50% faster than Docker due to the lack of virtualisation
- Tiny apps 🐭 - apps on Vertex are much smaller, usually <10MB, whereas Docker images will regularly exceed hundreds of MB
- More secure 🔒 - Vertex uses a capability-based security policy, which is a restricted sandbox by default
