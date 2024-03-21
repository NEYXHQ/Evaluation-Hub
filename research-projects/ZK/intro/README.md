## Comments on paper: zkSNARKs in a Nutshell

[zkSNARKs in a nutshell](https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/) is a great introductory article for people unfamiliar with zero knowledge proofs. 
Here is GPT summary

## coding as a Polynomial Problem:
Transforming statements to be proven into mathematical forms (polynomial equations).

## Succinctness through Random Sampling: 
Making proofs shorter and quicker to verify by using random sampling techniques.

## Homomorphic Encoding/Encryption: 
Allowing computations to be performed on encrypted data, maintaining privacy while proving that the computation was done correctly.

## Zero-Knowledge: 
The prover can convince the verifier that a statement is true without revealing any specific information about the statement itself.

The possibilities of zkSNARKs are impressive; you can verify the correctness of computations without having to execute them, and you will not even learn what was executed – just that it was done correctly. Unfortunately, most explanations of zkSNARKs resort to hand-waving at some point, and thus they remain something “magical”, suggesting that only the most enlightened actually understand how and why (and if?) they work. The reality is that zkSNARKs can be reduced to four simple techniques, and this article aims to explain them. Anyone who can understand how the RSA cryptosystem works, should also get a pretty good understanding of currently employed zkSNARKs.

## Part 1
RSA encryption and its pivotal role in zero-knowledge proofs, a concept integral to zkSNARKs. It elucidates RSA's homomorphic properties, enabling encrypted data verification without exposing the original values. The section demonstrates how a prover can validate computations through encrypted messages, ensuring the verifier learns only the result's correctness, not the data itself. This principle is foundational for understanding zkSNARKs, as it illustrates how cryptographic techniques can underpin privacy-preserving verification processes, crucial for secure and confidential blockchain transactions and computational validations.
