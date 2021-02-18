# Project: Subvector Commitment from Lattice (from 2020.07.04)

SVC是标准commitment的扩展, 有多个重要的应用, 举例: 
* 用于构造Authenticated Data Structure
* 用于将IOP编译为SNARK

### 研究内容: 基于格中的困难问题的SVC

### 研究计划: 阅读下列文章, 尝试分析构造SVC所需假设的性质, 探索能否基于LWE或者SIS构造

- [CT-RSA 2015]
Revisiting Cryptographic Accumulators, Additional Properties and Relations to other Primitives

- [ASIACRYPT 2010] Aniket Kate and Gregory M. Zaverucha and Ian Goldberg  
Constant-Size Commitments to Polynomials and Their Applications 

- [IEEE S&P 2020] Towards Scalable Threshold Cryptosystems (polynomial commitment的快速实现)
参考资料 https://zhuanlan.zhihu.com/p/304168510

- [PKC 2013] Dario Catalano and Dario Fiore 
Vector Commitments and Their Applications

- [ICALP 2016] Benoit Libert and Somindu C. Ramanna and Moti Yung   
Functional Commitment Schemes: From Polynomial Commitments to Pairing-Based Accumulators from Simple Assumptions

- [ePrint 2020] Sergey Gorbunov, Leonid Reyzin, Hoeteck Wee, and Zhenfei Zhang  
Pointproofs: Aggregating Proofs for Multiple Vector Commitments. https://eprint.iacr.org/2020/419

- [ePrint 2020] Alin Tomescu and Ittai Abraham and Vitalik Buterin and Justin Drake and Dankrad Feist and Dmitry Khovratovich  
Aggregatable Subvector Commitments for Stateless Cryptocurrencies

- [CRYPTO 2019] Russell W. F. Lai and Giulio Malavolta  
Subvector Commitments with Application to Succinct Arguments (这篇文章我读的比较熟, 除了安全性证明)

# Project: MPC in the head

## Zero-Knowledge Proofs

- [STOC 2007] Yuval Ishai, Eyal Kushilevitz, Rafail Ostrosky, Amit Sahai  
Zero-Knowledge from Secure Multiparty Computation 

(Please find the full version of this paper via SCI-hub)
This paper proposes the MPC-in-the-head paradigm for the construction of ZKP

- [USENIX 2016] Irene Giacomelli Jesper Madsen Claudio Orlandi 
ZKBoo: Faster Zero-Knowledge for Boolean Circuits (first efficient instantiation of MPC-in-the-head)

- [CCS 2017] Post-Quantum Zero-Knowledge and Signatures from Symmetric-Key Primitives (improvement of ZKBoo)

- [CCS 2018] Improved Non-Interactive Zero Knowledge with Applications to Post-Quantum Signatures (use preprocessing technique)

- [CCS 2017] Ligero: Lightweight Sublinear Arguments Without a Trusted Setup

- [CCS 2020] Ligero++: A New Optimized Sublinear IOP

For ligero/ligero++, please consider how to cast them in the framework of IKOS. 












