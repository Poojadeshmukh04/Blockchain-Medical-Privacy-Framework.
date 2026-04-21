# Blockchain-Medical-Privacy-Framework.
A decentralized framework using Blockchain, Homomorphic Encryption, and Differential Privacy for secure medical data management.

## Project Overview
This study implements a multi-layered security framework for healthcare data. It addresses the "Privacy-Utility Trade-off" by combining decentralized blockchain verification with advanced cryptography.

## Architecture Details
Blockchain Layer: Manages patient permission revocation and secure data transactions between hospitals and researchers.
Cryptographic Layer: Uses Homomorphic Encryption to process encrypted HL7 messages without decryption.
Privacy Layer: Implements Differential Privacy to protect invariant patient information during statistical analysis.

### ## Framework Performance Metrics
[cite_start]The following table summarizes the execution efficiency of the integrated privacy-preserving techniques[cite: 655, 656]:

| Privacy-Preserving Method | Execution Time (Seconds) | Accuracy/Consistency |
| :--- | :--- | :--- |
| **Homomorphic Encryption** | 1.9717 | [cite_start]High (Negligible difference) [cite: 315, 656] |
| **Differential Privacy** | 0.0030 | [cite_start]Meaningful Utility (ε = 1.0) [cite: 617, 656] |
| **Secure Multi-Party Computation** | 0.0000 | [cite_start]100% (Identical to merged data) [cite: 625, 656] |
