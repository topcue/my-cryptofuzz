# My CryptoFuzz - fuzzing ECC, RSA
## Index
  - [Overview](#overview) 
  - [Getting Started](#getting-started)
  - [PoC](#PoC)
## Overview
- This is a toy project to partially expand the function of cryptofuzz.
- The fuzzing target is **crypto++**. additional fuzzing of **RSA** and **ECC-related** ciphers that are not present in cryptofuzz is possible.
- **One unknown vulnerability(OOM)** was found in ECC-related ciphers.

## Getting Started
### Depencies
- clang++-8

## PoC

[oom](https://github.com/topcue/my-cryptofuzz/blob/master/ecc/log/oom-09a67d07733134dcc0f62c3048353a477f451580)
