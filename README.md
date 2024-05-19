# EigenStark

Scaling EigenLayer with Starks.

Similar to how rollups prove to their L1 smart contract about the rollup state transition, AVSs also need to prove to their L1 contract about their state transitions.

EigenLayer contracts have an example contracts for AVSs that use BLS signatures to register Operators. The L1 AVS contract needs to verify the Operator's signatures but verifying 300 signatures on L1 is expensive, Starknet can help with this cost.

# Starknet AVS ideas
- Aggregation of ZK proofs: Verify many ZK proofs (snarks, starks etc) cheaply on Starknet.
