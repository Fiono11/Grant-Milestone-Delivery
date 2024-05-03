# Milestone Delivery :mailbox:

> ⚡ Only the GitHub account that submitted the application is allowed to submit milestones. 
> 
> Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with `>`, such as this one, can be removed.

**The delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/Grants-Program/blob/master/docs/Support%20Docs/milestone-deliverables-guidelines.md).**  

* **Application Document:** [DAOsign](https://github.com/w3f/Grants-Program/blob/master/applications/DAOsign.md)
* **Milestone Number:** 1

**Context**
> The first milestone in DAOsign's collaboration with Polkadot centers on the development of smart contracts, specifically designed to enhance the security and functionality of DAOsign proofs. 
These deliverables, including the implementation of a Smart Contract with the EIP712/EIP2771 standard within the Ink! framework. This will ensure that proofs of authority, signature, and agreement are securely stored on the Polkadot blockchain. 
This foundational work not only advances the technical capabilities of DAOsign's platform but also aligns with the broader aim of fostering a more secure, transparent, and efficient environment for decentralized agreements and policies.
**Deliverables**
> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. 
If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work. 
> 
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

| Number | Deliverable               | Link                                                                                                                   | Notes                                                                                                                                                   |
|--------|---------------------------|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0a.    | License                   |  [LICENSE](https://github.com/DAOsign/polkadot-smart-contracts/blob/main/LICENSE)                                                                                                                      | Apache 2.0                                                                                                                                              |
| 0b.    | Documentation             | [Autogenerated documentation](https://daosign.github.io/polkadot-smart-contracts/), [Readme](https://github.com/DAOsign/polkadot-smart-contracts?tab=readme-ov-file#overview)                                                                                                                   | Inline documentation of the code and a basic tutorial that explains how a user can use DAOsign Smart Contract developed in ink! for proof verification. |
| 0c.    | Testing and Testing Guide |         https://github.com/DAOsign/polkadot-smart-contracts?tab=readme-ov-file#testing                                                                                                               | Unit tests to ensure functionality and robustness. The guide describe how to run these tests.                                                           |
| 0d.    | Docker                    |   https://github.com/DAOsign/polkadot-smart-contracts?tab=readme-ov-file#with-docker                                                                                                                     | Dockerfile(s) that can be used to test all the functionality delivered with this milestone.                                                             |
| 0e.    | Article                   | https://medium.com/@daosign/daosign-smart-signature-protocol-is-now-secured-with-polkadot-smart-contracts-387f3f3d9d17 | Article that explains what was done as part of the grant.                                                                                               |
| 1.     | Smart Contracts           |   https://github.com/DAOsign/polkadot-smart-contracts/tree/main/contracts                                                                                                                     | DAOsign proofs stored on Polkadot Blockchain using Agreement Contract, EIP712/EIP2771 standard implementation on Ink!                                   |

**Additional Information**
> Any further comments on the milestone that you would like to share with us.