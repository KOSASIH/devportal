---
description: 'Yellow paper: https://icon.foundation/download/IISS_Paper_v2.0_EN.pdf'
---

# Governance - IISS

## Basic IISS Overview

* ICON Incentives Scoring System \(hereinafter referred to as "IISS"\) is an evaluation system for accurately measuring and compensating the contributions of ICONists within the ICON Network. 
* The ICON Network defines 7 contribution items based on the 'Delegated Proof of Contribution' incentive protocol to identify and promote significant contribution activities to the decentralized network. Each ICONists can demonstrate its contribution to the ecosystem via delegation.
* I-Score is the ecosystem contribution score. IISS calculates and distributes I-Score for each contributing item every 43,200 blocks and determines the ICX issuance accordingly. After then, I-Score can be converted to ICX via Public Treasury. Based on the advanced on-chain governance system, IISS determines the issuance amount of ICX for the ecosystem.
* ICON Network's on-chain governance-based crypto economy is designed to work flexibly depending on the network situation that the network can develop successfully in a decentralized environment.

## Delegated Proof of Contribution

* Delegated Proof of Contribution \(DPoC\) is the incentive protocol to determine the contributions in the ecosystem. IISS works based on DPoC mechanism. 3 types of contribution items can be demonstrated by IISS.
* Representative
  * A Public Representative \(P-Rep\) is a full node on the ICON Network that participates in consensus and governance.
  * P-Reps consist of the top 22 Main P-Reps and 78 Sub P-Reps, and are elected by ICONists.
  * Block Validation Reward 
    * Block Validation Rewards are given to the top 22 Main P-Reps for block production and verification.
  * Representative Reward
    * Representative Rewards are given to all 100 P-Reps according to the delegated amount of ICX received.
* ICONist
  * All ICONists can receive the reward in return for delegate ICX to P-Reps.
  * All ICONists can contribute to the network through the delegation of ICX.
  * Therefore, ICONist can receive rewards according to the delegated amount of ICX.
* Contribution Items

| Item | Description |
| :--- | :--- |
| Block Validation Reward \(β1\) | Reward for block production and verification when a representative produces and verifies a block |
| Representative Reward \(β2\) | Reward for delegation when a Representative is delegated by ICONists |
| Representative Delegation Reward \(β3\) | Reward for delegation of a representative when ICONists delegate a representative |

## Governance Variables

* The following table introduces the governance variables mentioned above. The governance variables consist of a total of seven items: reward variables for the entity delegated ICX, reward rates for the ICONist delegated ICX, and variables for setting the amount of Step, the fee for the network.
* Governance Variable determines the amount of reward for each contribution item.

| Variables | Name | Explanation |
| :--- | :--- | :--- |
| i\_rep | Expected Monthly Reward per Representative | Expected reward amount for representative is determined by the weighted average of each representative suggestion. Each P-Reps suggest this amount based on their expenditure and profit. |
| s | Step Price | Minimum transaction fee in the ICON network which is determined by representatives. |

