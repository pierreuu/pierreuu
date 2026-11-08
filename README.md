# pierreuu

**Zero-Knowledge & Blockchain Engineer | Rust · CUDA · zkVMs**

I build cryptographic software, accelerate zero-knowledge proving systems, and develop blockchain infrastructure, with a focus on Rust, GPU computing, and cross-chain verification.

## Core Skills

- **Zero-knowledge proofs:** Groth16, PLONK, STARK/eSTARK, Circom, Plonky2, Polygon zkEVM, RISC Zero, and SP1.
- **Cryptography in Rust:** BN254 and BLS12-381 pairings; Groth16/PLONK implementation principles and Rust SNARK library development, using snarkjs as a reference.
- **GPU acceleration:** CUDA implementations of NTT, MSM, Merkle trees, Poseidon, and Poseidon2; integration and debugging of cryptographic acceleration libraries, including Icicle.
- **Blockchain infrastructure:** zkVMs and compilers, cross-chain bridges, EVM state migration, MPT proofs, signature verification, and order-book DEXs.

## Experience

### Circuit / ZK Development

- Researched Polygon Agglayer bridge architecture and X Layer integration; deployed and ran an Agglayer cross-chain environment.
- Implemented full X Layer L2 state export and import into a new optimistic chain, including correctness checks for the exported state.
- Built Circom circuits for Bitcoin Merkle proofs, Sui Ed25519 transaction signatures, Ethereum MPT proofs, and Ethereum ECDSA transaction signatures; generated Groth16 proofs for on-chain verification.
- Implemented Bitcoin Merkle proof and block-hash verification, plus Ethereum transaction/receipt MPT proof and block-hash verification, with RISC Zero and SP1. Generated Groth16 proofs for on-chain verification and validated CUDA acceleration for both zkVMs.
- Combined EIP-4844 PoE techniques with ZK circuits and smart-contract verification to reduce gas costs.
- Investigated BitVM2 and BitVM3; implemented and debugged garbled circuits for SHA-256 and elliptic-curve point addition used in ECDSA.

### Selected ZK & Protocol Engineering Work

- **Plonky2 — 7× faster proof generation:** Independently designed, implemented, and integrated GPU acceleration for Merkle tree construction, Poseidon, and Poseidon2.
- **Polygon zkEVM — 2× faster batch proving:** Optimized the prover and independently designed GPU-accelerated Merkle tree construction. Built a Rust batch prover from an open-source implementation, fixing bugs and achieving **20× the speed of zkevm-proverjs** for internal development and debugging.
- **CUDA cryptography — order-of-magnitude speedups over CPU:** Accelerated NTT, MSM, Merkle trees, and Poseidon hashing. Identified an upstream bug while integrating Icicle and submitted a PR to help resolve it.
- **Rust cryptography:** Independently implemented pairing algorithms for BN254 and BLS12-381; studied Groth16 and PLONK papers in depth to support Rust SNARK implementation.
- **zkVMs & proof-system internals:** Contributed to OlaVM's virtual machine and compiler; researched Miden and Plonky2, and analyzed Plonky2's STARK and Polygon zkEVM's eSTARK proving code in depth.
- **Order-book DEX:** Contributed to a dYdX-based exchange, implemented an account-mapping feature, and analyzed matching-engine performance.
