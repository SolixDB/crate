# SolixDB – The Universal Solana Indexing Layer

One tool. Any RPC. Your database.

---

## What is SolixDB?

SolixDB is an open-source developer tool that simplifies Solana blockchain indexing.  
This crate currently serves as the **official Rust namespace reservation** for the future SolixDB Rust SDK.

The full implementation today is available for JavaScript/TypeScript:

- **NPM:** `npm install solixdb`
- **Documentation:** https://docs.solixdb.xyz
- **GitHub:** https://github.com/SolixDB/crate

A full Rust SDK is planned — this crate will eventually host native Solana indexing utilities written in Rust.

---

## Current Status

This crate is a placeholder and contains only minimal code:

```rust
use solixdb::info;

fn main() {
    println!("{}", info());
}
