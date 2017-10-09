# onechain

Root repository for [One Network Enterprises](http://www.onenetwork.com)' blockchain initiatives.

ONE's approach to blockchain is comprised of two key parts:

 * **Frontchain** - frontchains are "traditional" blockchains, where writes are carefully controlled 
   by the smart contract, but the distributed ledger's data is visible to *all* blockchain participants.
   The blockchain itself is the "system of record", but the processes
   are limited to those where broad read permissions are acceptable from a business standpoint.
 * **Backchain** - backchains provide an alternative when frontchains' permission limitations are prohibitive.
   In a backchain, an *orchestrator* (for example ONE) is the system of record for the business
   transactions.  The orchestrator must distribute an audit trail of writes to parties based on their
   permissions.  The orchestrator also writes a *hash* of the transaction data to the blockchain.  
   This provides an immutable record of the business transaction which can later be indpendently 
   verified by the chain participants.

ONE operates several github repos in support of these initiatives:

| Repo | Description |
| --- | --- |
| [`onechain`](https://github.com/onenetwork/onechain) | Root repository for One Network Enterprises' blockchain initiatives.  Contains introductory material, whitepapers, and an index of other related repos. |
| [`onechain-back`](https://github.com/onenetwork/onechain-back) | Implementation (smart contract) for ONE's Backchain |
| [`onechain-back-client`](https://github.com/onenetwork/onechain-back-client) | Client API for ONE's Backhain |
| [`onechain-back-verify`](https://github.com/onenetwork/onechain-back-verify) | Standalone application which can connect to ONE's Backchain and verify individual transactions in the distributed ledger. |
| [`onechain-front`](https://github.com/onenetwork/onechain-front) | An index of repos for ONE frontchain initiatives. |

Licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
