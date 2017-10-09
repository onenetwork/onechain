# onechain

Root repository for [One Network Enterprises](https://www.onenetwork.com)' blockchain initiatives.

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
| [onechain](htts://github.com/onenetwork/onechain) | Root repository for One Network Enterprises' blockchain initiatives.  Contains introductory material, whitepapers, and an index of other related repos. |
| [onechain-back](htts://github.com/onenetwork/onechain-back) | Implementation (smart contract) for ONE's Backchain |
| [onechain-back-client](htts://github.com/onenetwork/onechain-back-client) | Client API for ONE's Backhain |
| [onechain-back-verify](htts://github.com/onenetwork/onechain-back-verify) | Standalone application which can connect to ONE's Backchain and verify individual transactions in the distributed ledger. |
| [onechain-front](htts://github.com/onenetwork/onechain-front) | Root repository for ONE's frontchains.  Will contain an index of specific frontchain initiative repos. |

Licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
