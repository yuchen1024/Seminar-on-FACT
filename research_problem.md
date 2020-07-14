# Problem: Efficient NIZK for cross domain/composite statement

1. Example

How to prove knowledge of $x \in \{0,1\}^*$ such that g^{H(x)} = y, where $y \in \mathbb{G}$ is a public value. 

SHA(g^x) = pk

2. Related works

* [CRYPTO 2018] Non-Interactive Zero-Knowledge Proofs for Composite Statements

key idea: commit the intermediate value, then we can decomposite the arithmetic statement and the algebra statement

dissect zk-SNARK in the crs model

* [PKC 2019] Efficient Non-Interactive Zero-Knowledge Proofs in Cross-Domains without Trusted Setup

public-coin zk-SNARK (MPC-in-the-head)    only consider committed input 











