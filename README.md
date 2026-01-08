# 🧱 Tiny Python Blockchain

A minimal, educational blockchain implementation in Python to demonstrate how blocks are linked using cryptographic hashes (no GPUs were harmed).

## How it works
- Starts with a **Genesis Block** 
- Each block stores:
  - index
  - timestamp
  - data
  - `previous_hash`
- SHA-256 hashing links every block to the one before it
- Change one block → the chain immediately complains

## Key Concepts
- Block structure
- Hash chaining
- Tamper-evident design (trust issues included)

## Limitations
- No proof-of-work (math stays calm)
- No networking or peers
- No transactions or wallets
- Single-node, in-memory only

## Purpose
Built to understand blockchain fundamentals — not to replace Bitcoin (yet).

> Immutable*  
> \*unless you edit the Python file lol


