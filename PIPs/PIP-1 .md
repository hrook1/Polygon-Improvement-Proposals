# PIP-1: PIP Purpose and Guidelines

Polygon Improvement Proposals (PIPs) describe standards for the Polygon ecosystem, including core protocol specifications such as Heimdall and Bor, client APIs, and contract standards, etc.

### What is a PIP?

PIP stands for Polygon Improvement Proposal. A PIP is a design document providing information to the Polygon community, or describing a new feature for Polygon or its processes or environment. 

PIPs are used by authors to measure, document, and build community consensus, while providing technical specifications and motivation behind a specific feature. 

### PIP Rationale

In a decentralized and self-governed system, a framework is necessary for the developer community to inform, propose, and gather technical feedback on new features. 

By introducing a transparent and versioned repository, the community maintains a historical record of all feature proposals, including their revision history and implementation progress.

## PIP Types

The following are mostly the types of PIPs that will be categorised in:

* Core: Improvements on the Core Components such as Heimdall and Bor as well as changes that are not necessarily consensus critical but may be relevant to core components.

* Contracts: Improvements on the Core Contracts that are deployed on Ethereum.

* Interface: Improvements around client API/RPC specifications and standards, and also certain language-level standards like method names and contract ABIs.

* Informational: Offers recommendations, information, or general thinking on an issue to the community. An informational PIP doesn’t require validator consensus.  

## PIP Flow In All Tracks

#### Idea

Initial post is created on the Polygon community forum.
In addition to making sure your idea is original, it will be your role as the author to make your idea clear to reviewers and interested parties, as well as inviting editors, developers and community to give feedback on the aforementioned channels.

#### Draft

Proposal championed by 1 Polygon POS validator / Member of the Polygon Governance Team (this should be done on the forum post with a comment from a verified validator / Governance Team Member).

#### Review

Once the proposal has been championed it will be directed to the attention of the PIP editors who will work with the author to ensure that the content meets grammatical standards, the argument is original and makes sense. Once any issues are resolved it will be given a PIP number and added to the GitHub repository. 
The author then marks the PIP as ready for and requesting Peer Review. The proposal will be announced in a ‘Polygon Town Hall’, as well as broadcasted to the Discord Announcement channels to let the community know about the latest PIP.

#### Last Call

In the final review window for a PIP before moving to Final, a PIP Editor will assign ‘Last Call’  status (by way of a comment on the community forum post containing the PIP) and set a review end date (last-call-deadline), typically 14 days later.
If this period results in necessary normative changes, the PIP will revert back to Peer Review.

#### Final 

Once the proposal content has addressed all of the feedback has been refined and finalized, which will then be translated to an issue on GitHub on their respective repositories and taken forward by the original Polygon development team based on the type of PIP. That translation of a PIP to GitHub will be undertaken by the original Polygon development team.
This represents the final standard of a PIP and should only be updated to correct errata and add non-normative clarifications.

The original Polygon development team, or any other developer team, will then prioritize and implement the PIP. This will then be tested on the Mumbai Testnet and only then be rolled out as an upgrade on the Mainnet.

## PIP Body

Whenever an Author is submitting a PIP, the Author needs to ensure that the PIP is submitted with as much details as possible so that everyone and anyone reading the draft should be able to understand it.

This is highly important because otherwise, there will be too many iterations on only correcting the body / formatting of the PIP and that would be a sincere waste of time for everyone.

A really good PIP should contain the following:

* Title: The Title of the PIP needs to be concise and accurately explain the purpose of the PIP

* Status: 1 of 4 statuses for the PIP

* Draft: When a new PIP is submitted, the status will remain Draft during the discussion stages. Authors need to ensure that they add this prefix to their Title. During this stage Amendments to the Draft will be subject to discussions.

* Last Call: This is the final review window for a PIP before moving to Final. A PIP editor will assign Last Call status and set a review end date. This will only happen when there is a consensus on the PIP that it has reached a finalized state. Meaning the idea is now refined.

* Final: This state represents the Final standard. No more amendments will be made to the PIP now. The Final state will be called on by the Author and the original Polygon development team.

* Live: A special status for PIPs that are designed to be continually updated and not reach a state of finality. This includes most notably PIP-1.

* Withdrawn: The PIP Author(s) have withdrawn the proposed PIP. This state is final and once a proposal is marked as withdrawn can no longer be resurrected using the PIP number. If the idea becomes relevant at a later date it can be considered under a new proposal. 

* Abstract: A short (~200 word) description of the technical issue being addressed.

* Motivation (*optional): Motivation is critical for PIPs that want to change the Polygon protocol. It should clearly explain why the existing protocol specification is inadequate to address the problem that the PIP solves. PIP submissions without sufficient motivation may be rejected outright.

* Specification: The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Polygon protocols

* Rationale: The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.

* Backwards Compatibility: All PIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The PIP must explain how the author proposes to deal with these incompatibilities. PIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

* Test Cases: Test cases for implementation are mandatory for PIPs that are affecting consensus changes. Other PIPs can choose to include links to test cases if applicable.

* Reference Implementation: An optional section that contains a reference/example implementation that people can use to assist in understanding or implementing this specification.

* Security Considerations: All PIPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. PIP submissions missing the “Security Considerations” section will be rejected. A PIP cannot proceed to status “Final” without a Security Considerations discussion deemed sufficient by the reviewers.

**Copyright Waiver: All PIPs must be in the public domain.**

## PIP Editor Responsibilities

For each new PIP that comes in, an editor does the following:

Read the PIP to check if it is ready, sound and complete. The ideas must make technical sense, even if it doesn’t seem likely to get to Final status.
The title should accurately describe the content.
Check the PIP for language (spelling, grammar, sentence structure, etc.).
If the PIP isn’t ready, the Editor will send it back to the Author for revision, with specific instructions.
Once the PIP has satisfied the above requirements, a PIP Editor will upload the proposal to the GitHub repository. 

### PIP Editors

The current PIP Editors are comprised of:

* References

* The PIP framework, and in particular PIP-1 and PIP-6, was heavily derived from the Ethereum EIP-1 document [Martin Becze, Hudson Jameson, et al., "EIP-1: EIP Purpose and Guidelines," Ethereum Improvement Proposals, no. 1, October 2015. [Online serial]. Available: https://eips.ethereum.org/EIPS/eip-1.],) which was derived from Bitcoin’s BIP-0001 (written by Amir Taaki) which in turn was derived from Python’s PEP-0001 (written by Barry Warsaw, Jeremy Hylton, David Goodger, and Nick Coghlan)

### Copyright

Copyright and related rights waived via CC0.