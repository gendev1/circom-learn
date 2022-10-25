# Learn Circom

This repo is collection of examples that have been written to learn circom and ZK Circuits.

## Command Line Commands

```sh
circom multipler2.circom --r1cs --wasm --sym --c
```

r1cs - generates r1cs constraint system circuit
wasm - generates multipler2_js directory (multiplier2.wasm) and files to generate witness
sym - generates symbols file for debugging and printing
c - generates multiplier2_cpp directory ( multiplier2.cpp, multiplier2.dat, main.cpp, makeFile, etc)
