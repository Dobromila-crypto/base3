# Understanding Layer 2 Blockchains
## What is Layer 2?
Layer 2 networks are built on top of Ethereum to improve speed and reduce costs.
They process transactions separately but rely on Ethereum for security.
## Why Layer 2 Networks Exist
Ethereum mainnet can become congested.
High demand leads to higher gas fees.
Layer 2 helps reduce this pressure.
## Types of Layer 2 Solutions
- Optimistic Rollups
- ZK Rollups
- State Channels
- Sidechains
### Optimistic Rollups
They assume transactions are valid unless challenged.
Fraud proofs are used to detect incorrect transactions.
### ZK Rollups
They use zero-knowledge proofs to validate transactions.
This allows fast confirmation with strong security guarantees.
## Summary
Layer 2 solutions are essential for Ethereum scalability.
They enable lower fees and improved user experience.
## Ethereum Scalability Problem
Ethereum processes a limited number of transactions per second.
When network demand increases, gas fees rise significantly.
This creates a scalability bottleneck.
## Security Model of Layer 2
Layer 2 networks inherit security from Ethereum by settling transaction data on mainnet.
This ensures that users can ultimately rely on Ethereum for dispute resolution.
## Data Availability
Rollups publish transaction data to Ethereum.
This allows independent verification of transaction validity.
ZK Rollups rely on cryptographic validity proofs.
These proofs allow transactions to be verified without revealing full computation details.
## Transaction Throughput (TPS)
Ethereum processes roughly 15–20 transactions per second.
Layer 2 networks significantly increase effective throughput by batching transactions.
## Gas Fee Mechanics
On Ethereum, users pay gas for computational work.
Layer 2 reduces this by aggregating multiple transactions into a single batch submission.
## Finality and Settlement
Transactions on Layer 2 are finalized after being posted to Ethereum.
Withdrawal periods may vary depending on rollup type.
Fraud proofs allow anyone to challenge invalid transactions during a dispute window.
Validity proofs mathematically guarantee correctness before settlement.
