### Title: Revert Community Pool Tax Rate to 2%


---


### Summary  

This `param-change` proposal aims to revert the `community_tax` parameter from 10% back to 2%, reinstating the baseline rate that was in effect prior to [**Proposal88](https://www.mintscan.io/cosmos/proposals/88/).


### Parameter Change

This is a proposed parameter change managed by the "distribution module" in the Cosmos SDK.

**Parameter**: `community_tax`

`community_tax`: Defines the portion of block rewards (newly minted ATOM) that are diverted into the Community Pool, before the rest is distributed to stakers and validators. This parameter is modifiable through an on-chain `param-change` proposal.

**Parameter and Proposed Value**


| Module         | Parameter      | Current Value | Proposed Value |

|----------------|----------------|---------------|----------------|

| x/distribution | community_tax  | 0.10 (10%)    | 0.02 (2%)      |


If the parameter is set to:

0.02 → 2% of minted rewards go to the Community Pool

0.10 → 10% of minted rewards go to the Community Pool


---


### Background  

[**Proposal 88**](https://www.mintscan.io/cosmos/proposals/88/) raised the community tax from 2% to 10% to enable long-term funding of the **Atom Accelerator DAO (AADAO)** and similar initiatives. This tax increase facilitated allocations of 588,000 ATOM via [**Proposal 95**](https://www.mintscan.io/cosmos/proposals/95/), and an additional 975,811 ATOM (plus a 100,000 ATOM bonus) via [**Proposal 865**](https://www.mintscan.io/cosmos/proposals/865/).


As of Q1 2025, AADAO has entered "maintenance mode" and has declined to renew or revise its mandate. In view of these circumstances, the justification for maintaining a 10% tax no longer applies.


---


### Rationale for Reversion to 2%


1. **Original Purpose of Tax Rate Increase No Longer Applies**  


2. **Avoid Capital Oversupply and Misallocation**  

   An excessive buildup of idle capital can attract value-extractive or poorly scoped spending proposals. 


3. **Decouple Tax Policy from Broader Governance Discussions**  

   The Community Pool tax rate should reflect the network’s actual operational needs; not serve as a catch-all for opportunism or act as a default placeholder for unresolved Treasury discussions and decisions.


4. **Preserve Hub Autonomy with Fiscal Discipline**  

   A 2% tax rate maintains a credible funding stream while keeping governance of the Hub's public resources independent, sovereign, tractable and reasonable.


5. **Give More to Stakers**  

   Assuming ~9.6 ATOM minted per block and ~4.36 million blocks/year:

   - Reducing the tax from 10% to 2% returns **0.768 ATOM per block** to stakers.

   - This results in approximately **3.34 million additional ATOM/year** in staking rewards.


---


### **Clarification on Scope**  

This proposal **does not eliminate or reduce** existing Community Pool funds, which currently total approximately 9.29 million ATOM. Decisions concerning the active balance, usage, governance structure, or potential reforms of the Community Pool should be addressed through subsequent and distinct governance proposals.

---


### **Conclusion**  

Reducing the community tax rate to 2% is a prudent adjustment in the absence of an active, Cosmos Hub governance-approved funding mandate. This parameter change helps mitigate inadvertent capital accumulation, improves validator and staker economics, and reinforces fiscal discipline without compromising the Hub’s ability to fund public goods and services independently.

It also establishes a more appropriate baseline for future governance discussions concerning long-term treasury management frameworks and strategic capital deployment from the Community Pool.


---

### Links

[**Cosmos Hub Forum Discusssions**](https://forum.cosmos.network/t/proposal-draft-reverse-proposal-88-revert-community-pool-tax-rate-to-2/15397)

---


### **Voting Options**


- **YES** – I support reducing the Community Pool tax rate from 10% to 2%.

- **NO** – I support retaining the current Community Pool 10% tax rate.

- **ABSTAIN** – I have a conflict of interest; or wish to participate without expressing a preference.

- **NO WITH VETO** – I believe this proposal is (1) irrelevant to the Cosmos Hub, (2) maliciously and or unjustly harms minority interests, or (3) violates Cosmos Hub governance rules and or norms.


