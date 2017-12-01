# onechain

For an introduction to ONE's blockchain strategy, please read the following whitepaper:
<br/><span style="padding-left: 2em; margin-bottom: 20px">[Can Blockchain Revolutionize the Supply Chain?](One%20Chain%20White%20Paper.pdf)</span>

Also read our press release announcing the launch of ONE Chain:
<br/><span style="padding-left: 2em; margin-bottom: 20px">[One Network Delivers New ONE Chain - Blockchain Solution](https://www.onenetwork.com/2017/10/one-network-delivers-new-one-chain-solution/)</span>

ONE's approach to blockchain is comprised of two key parts:

 * **Frontchain** - Frontchains are "traditional" blockchains, where writes are carefully controlled 
   by the smart contract, but the distributed ledger's data is visible to *all* blockchain participants.
   The blockchain itself is the "system of record", but the processes
   are limited to those where broad read permissions are acceptable from a business standpoint.
 * **Backchain** - Backchains provide an alternative when frontchains' permission limitations are prohibitive.
   In a backchain, an *orchestrator* (for example ONE) is the system of record for the business
   transactions.  The orchestrator must distribute an audit trail of writes to parties based on their
   permissions.  The orchestrator also writes a *hash* of the transaction data to the blockchain. This provides 
   an immutable record of the business transaction which can later be indpendently 
   verified by the chain participants.

<br/>
ONE operates several github repos in support of these initiatives:

| Repo | Description |
| --- | --- |
| <a href="https://github.com/onenetwork/onechain">onechain</a> | Root repository for One Network Enterprises' blockchain initiatives.  Contains introductory material, whitepapers, and an index of other related repos. |
| <a href="https://github.com/onenetwork/onechain-back">onechain&#8209;back</a> | Implementation (smart contract) for ONE's Backchain |
| <a href="https://github.com/onenetwork/onechain-back-client">onechain&#8209;back&#8209;client</a> | Client API for ONE's Backhain |
| <a href="https://github.com/onenetwork/onechain-back-verify">onechain&#8209;back&#8209;verify</a> | Standalone application which can connect to ONE's Backchain and verify individual transactions in the distributed ledger. |
| <a href="https://github.com/onenetwork/onechain-front">onechain&#8209;front</a> | An index of repos for ONE's Frontchain initiatives. |

Licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
