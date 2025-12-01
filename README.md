Shutter API: Encryption as a Service in Arbitrum
Funding Ask

40,000 USD

Submitted on

31 Jul, 2025

Milestones

4

Category

Developer Tooling

Details

We aim to bring Shutter API, a powerful, developer-friendly threshold encryption and distributed key management service, to the Arbitrum One ecosystem.

Shutter enables developers to easily integrate encrypted commit-reveal workflows, time-lock encryption, and privacy-preserving mechanisms without relying on trusted hardware or custom infrastructure.

Shutter API is already live on Gnosis Chain and used in production by Snapshot (Shielded voting, the default setting Arbitrum DAO votes), Shutter Predict (
), Paddle Battle (
), Ethereum time capsule (
) and many others.

Shutter functions as encryption-as-a-service. It allows developers to build fairer, more secure applications where user inputs remain private until the appropriate reveal condition is met. These capabilities can improve the UX and unlock many new use cases for DAOs, DeFi, auctions, sealed-bid RFPs, prediction markets, gaming and more, any use case where timing and fairness matter. By deploying, maintaining, and supporting Shutter API on Arbitrum One we aim to equip its developer ecosystem with a lightweight but powerful cryptographic primitive to unlock a wide range of applications based on information symmetry. This primitive could later be extended to Orbit chains.
What innovation or value will your project bring to Arbitrum? What previously unaddressed problems is it solving? Is the project introducing genuinely new mechanisms.

It’s commonly acknowledged that blockchains suffer from information asymmetry, when actors can act on privileged early info (e.g., frontrunning and malicious MEV). A few additional moments give sophisticated actors and bots an unfair advantage over others, like knowing your opponent’s move before you play Rock-Paper-Scissors.
Shutter’s encryption API ensures information remains locked until the reveal trigger without relying on hardware trust assumptions, enabling truly fair commit-reveal, sealed auctions, prediction markets, governance and many other use cases.

What is the current stage of your project.

Shutter API is fully deployed on Gnosis Chain. We're now ready to bring it to Arbitrum One as a pilot to later expand to other chains in the Arbitrum ecosystem (Arbitrum Nova and Orbits).

Do you have a target audience? If so, which one.

Direct Beneficiaries:

Developers and Builders: Shutter API offers a plug-and-play solution for integrating threshold encryption into dApps. Developers can implement commit-reveal schemes, time-lock encryption, and shielded interactions without building or maintaining their own cryptographic infrastructure. This significantly reduces complexity and accelerates the development of privacy-aware applications.
Indirect Beneficiaries:

DAOs and Governance Users:
Users gain access to more secure and fair voting mechanisms, protecting decisions from manipulation and premature influence.

DeFi Users:
Benefit from reduced front-running and MEV exploits through encrypted order flows, auctions, and commitment-based interactions.

Users of Commit-Reveal-Enabled Tools:
Applications like prediction markets, sealed-bid RFPs, and multiplayer strategy games can now implement commit-reveal workflows that ensure fairness and prevent information asymmetry. See more examples here.

Do you know about any comparable protocol, event, game, tool or project within the Arbitrum ecosystem.

No Arbitrum-native tools that we found provide an encryption-as-a-service dev tooling.

CoFHE is emerging with homomorphic encryption. However, this involves heavy operations and hardware setup, unlike Shutter’s lightweight, off-chain commit-reveal API. Furthermore, it targets on-chain computation, not off-chain commit-reveal privacy primitives. Shutter’s API remains more developer-friendly and purpose-built for fairness workflows.

Have you received a grant from the DAO, Foundation, or any Arbitrum ecosystem related program or conducted any IRL like a hackathon or workshop.

No grants.

However, Shutter got a small, 2,500 ARB, reward from JokeRace for deploying Shielded Voting with Snapshot.

Have you received a grant from any other entity in other blockchains that are not Arbitrum.

Yes. However, non of these grants have been for the Shutter API.

10 ETH – Public Nouns DAO

60 ETH – Octant

80,000 OP – Optimism Missions

150,000 OP – Optimism Retro Funding 5

What is the idea/project for which you are applying for a grant.

We are applying to deploy, maintain, and support the Shutter API on Arbitrum One, as a pilot to potentially expand to Arbitrum Nova and Orbits. This will bring threshold encryption as a service to the ecosystem. The Shutter API is a cryptographic building block that provides commit-reveal and time-lock encryption capabilities via a lightweight, easy to integrate API. No need for developers to run heavy infrastructure or rely on trusted hardware. This enables the creation of privacy-preserving workflows on Arbitrum, with real cryptographic guarantees of fairness and information symmetry.

The core idea is to give Arbitrum a plug-and-play encryption layer developers can use for fair coordination and decision-making in DAOs, DeFi, onchain games, auctions, and more. Developers interact with the API through simple HTTP calls that trigger distributed key generation (DKG), encryption, and threshold decryption coordinated by the Shutter key network. By separating encryption logic from the app-layer, we allow teams to focus on their product logic while trusting Shutter to manage secure cryptographic operations.

Use Cases Include:

Sealed Bid Auctions: Like our Shutterized OTC Token Auction, where bids are encrypted and revealed simultaneously to prevent strategic last-second bidding.
Bounty and Betting Platforms: Encrypted submission of predictions or challenge responses, revealed only when the outcome is known.
Procurement Tools: Shutterized Procurement allows vendors to submit confidential proposals, which are revealed only at the evaluation deadline.
Onchain Games: Like Shutterized Texas Holdem or Diplomacy, where secrecy is part of the strategy, moves are committed in encrypted form and later revealed.
Negotiation Tools & Time-Lock Gifts: Sending data, tokens, or instructions encrypted with a delayed reveal, perfect for unlocking at future events or times.
This grant will support:

Adapting and testing Shutter API for Arbitrum One.
Building reference use cases to showcase how developers can integrate threshold encryption in their own dApps.
Writing documentation, setup guides, and walkthroughs for developer adoption.
Threshold encryption isn’t just about hiding data; it’s about leveling the playing field in systems where information timing is critical. Notably, DeFi needs a level playing field to improve user experience; having this tooling can give Arbitrum an edge as the DeFi L2, which is one of Arbitrum’s Strategic Objectives (SOS).

Shutter API on Arbitrum One will bring these capabilities to developers in a frictionless, well-documented way, empowering them to create fairer, more secure applications without needing to be cryptographers.

Outline the major deliverables you will obtain with this grant.

Fully integrated encryption API tailored for Arbitrum One

Documentation with HOWTO guides

At least three deployed use cases in Arbitrum One:

Sealed-Bid RFPs for DAOs: Enables DAOs to conduct confidential proposal or procurement rounds, with bids encrypted until the reveal phase.
Sealed Predictions: A simple predictions app where submissions are encrypted and only revealed after a defined future time or event.
Front-Running-Protected DEX (testnet): A prototype decentralized exchange that uses encrypted transaction flow, with encryption at the dapp level (via js library) to prevent MEV and front-running.
Please explain how your idea/project aligns with the Arbitrum ecosystem goals.

This proposal is aligned with Arbitrum’s ecosystem goals, particularly the Arbitrum’s Strategic Objectives (SOS) in the following ways:

DeFi Integrity and Fairness: Arbitrum’s position as a leading DeFi hub depends not just on scale but on credible market infrastructure. This project introduces mechanisms that improve fairness in DeFi, auctions, and prediction markets, supporting more trustworthy, manipulation-resistant DeFi interactions.

Developer Tooling Expansion: The project fills a current tooling gap by providing privacy infrastructure that can be adopted without requiring specialized cryptographic knowledge. This aligns with Arbitrum’s focus on empowering developers with composable, production-ready tools.

Ecosystem Innovation through Privacy: Arbitrum’s SOS explicitly calls for privacy primitives that unlock new use cases. This project expands what’s possible, from sealed-bid coordination to onchain games, without adding protocol-level complexity.

Improved Developer Experience: By removing the need to build and maintain complex infrastructure for privacy-preserving workflows, the project reduces time-to-market for builders and contributes to a smoother dev onboarding process, a stated priority in Arbitrum's strategic roadmap.

What is your requested grant.

$40,000

Website.

https://shutter.network/

Please provide a detailed breakdown of the budget in term of utilizations, costs and other relevant information.

API Adaptation & Integration.
$15,000
Modify Shutter API for Arbitrum workflows and environments.

Use Case Development.
$17,500
Build 3 pilot apps: DAO voting, sealed auction, prediction.

Documentation & Demos
$5,000
API docs, example code, deployment guides.

Feedback report.
$2,500
Measuring, reporting and implementing feedback.

Provide a list of the milestones, with the USD amount of the grant associated to it, the deliverables that will be provided, and the estimated completion time.

Milestone 1. API Integration.
Deliverable: Arbitrum-compatible API with encryption/decryption flows.
Timeline: 4 weeks (~Dec 19th, 2025)
Funding ask: $15,000

Milestone 2. Documentation & Examples
Deliverable: Complete dev guide + public demos.
Timeline: +2 weeks (~Jan, 2nd 2026)
Funding Ask: $5,000

Milestone 3. Three Use Cases Live on Arbitrum One.
Deliverable: Three working commit-reveal apps on Arbitrum mainnet.

Sealed-Bid RFPs for DAOs: Enables DAOs to conduct confidential proposal or procurement rounds, with bids encrypted until the reveal phase.
Sealed Predictions: A simple predictions app where submissions are encrypted and only revealed after a defined future time or event.
Front-Running-Protected DEX (testnet): A prototype decentralized exchange that uses encrypted transaction flow, with encryption at the dapp level (via js library) to prevent MEV and front-running. Timeline: +8 weeks (~Mar, 6th 2026) Funding ask: $17,500
Milestone 4. Feedback report.
Deliverable: Deployed use cases feedback report in the Shutter Forum and potentially on the Arbitrum Forum.
Timeline: +4 weeks (~Apr, 3rd 2026)
Funding Ask: $2,500

Are milestones clearly defined, time-bound, and measurable with quantitative metrics where applicable? What are your reference KPI, if applicable, for each milestone.

Technical Excellence
KPI: Achieve a Net Promoter Score (NPS) of ≥8 from partner teams using Shutter API by the final milestone.

Milestone: Tied to Milestone 4 – Mainnet Pilot & Feedback

Why: High satisfaction from real integrations will validate the API’s reliability and usability, especially in the absence of direct competitors.

Community Traction
KPI: Reach 50+ GitHub stars on the Shutter API repo by the grant end.

Milestone: Monitored across all milestones, with emphasis during Milestone 3 – Docs & Examples

Why: Indicates growing visibility and interest beyond core partners.

User Adoption
KPI: At least 3 applications on Arbitrum One integrating Shutter API by project completion.

Milestone: Tied to Milestone 4 – Mainnet Pilot & Feedback

Why: Demonstrates practical utility and ecosystem fit across multiple domains.

These KPIs provide a well-rounded framework to assess performance and impact at each project stage.

What is the estimated maximum time for the completion of the project.

Full completion in 4 months, maximum 6 months.

How should the Arbitrum community measure the success of this grant.

API operational on Arbitrum One.

≥ 3 distinct deployed use cases

Active developer and DAO engagement metrics.

What is the economic plan for maintaining operations or continuing the growth of your project after the grant period.

Shutter is funded through Shutter DAO treasury and prior contributor grants. The API uses a split-fee business model, aligning usage with sustainability through low-friction adoption.

Market Needs: For developers building apps and interfaces, what specific challenges or opportunities do they face in Arbitrum.

There is a clear and growing demand for trust-minimized tools that improve fairness and protect user intent in governance and DeFi. Our integration with Snapshot was initiated at Snapshot’s request, and it now serves as the default shielded voting option for the Arbitrum DAO. We are also collaborating with Kleros and Decent, who view encrypted voting as essential to secure governance.

In DeFi, billions have been lost to MEV, much of it due to early access to sensitive information. Shutter API tackles this at the application layer, enabling sealed bids, encrypted orders, and commit-reveal flows, without requiring changes to Arbitrum’s base protocol. This meets a real and pressing need for privacy tools that are both effective and easy to adopt.

Composability: How can your proposed developer tooling (existing or new) facilitate seamless interaction between different protocols and tools built on Arbitrum, the Nova ecosystem and other Orbit chains.

Shutter API is designed as a plug-and-play building block that developers can integrate directly into their Arbitrum dApps. It abstracts the complexity of encryption infrastructure, allowing teams to focus on product development while accessing a state-of-the-art, trust-minimized encryption service, without needing to build or maintain it themselves.

Developers interact with it through straightforward endpoints, making it simple to compose with existing contracts and interfaces on Arbitrum One.

While the initial scope of this grant focuses on deployment and support on Arbitrum One, the architecture allows for future extension to Orbit chains, Arbitrum Nova, and Stylus-based applications, ensuring continued compatibility as the ecosystem evolves.

Adoption: If your grant focuses on a Growth or Orbit Chain developer tool, how would you ensure its widespread adoption within the developer community.

Our strategy focuses on real integrations and developer activation:

Deploy on Arbitrum One:
Complete a stable, production-ready deployment as the foundation for broader adoption.

Documentation and Support:
Publish high-quality guides and walkthroughs to ensure developers can easily integrate Shutter API.

Three Use Cases Live:
At least three Arbitrum-native projects showcasing different use cases like governance and auctions.

If working on Orbit Chain Onboarding and Tooling: How would you adapt your existing developer tooling (or propose a new tool) to simplify building applications on custom Arbitrum Layer 3 chains (Orbit Chains).

This grant focuses on deploying Shutter API on Arbitrum One, but we recognize the potential to extend support across Orbit chains. We’re open to expanding the scope to develop a generalized encryption service for the entire Arbitrum ecosystem.

This would require adapting relayer coordination, key management, and configuration tools to support diverse Orbit environments.

Instagram.

N/A

If applying for a growth oriented grant: Please provide success metrics for the grant with milestone-oriented disbursements.

N/A

LinkedIn.

https://www.linkedin.com/company/brainbot-gmbh/

Discord.

N/A

Others.

N/A

Do you acknowledge that your team will be subject to a KYC requirement.

Yes

Do you acknowledge that, in case of approval, you will have to provide a report at the completion of the grant and, three months later, complete a survey about your experience.

Yes

Team experience and completeness.

brainbot GmbH, based in Germany, has been advancing decentralized infrastructure since 2014. The team behind Shutter Network has consistently delivered impactful open-source software in the Ethereum ecosystem and beyond. Before launching Shutter, brainbot built several core components of Web3 infrastructure, including:

Contributing to the original Ethereum Python client – One of the earliest implementations contributing to Ethereum’s launch and stability.
Raiden Network – An off-chain state channel protocol for scalable token transfers on Ethereum.
Beamer Bridge – A fast, trust-minimized cross-chain bridge for L2-to-L1 and L2-to-L2 messaging.
Since 2021, brainbot has been focused on advancing threshold encryption for application-layer privacy. The team’s most notable contributions to this space include:

Shielded Voting – Integrated into Snapshot, enabling vote privacy and protecting over 298,000 votes across 600+ DAOs, including Arbitrum DAO (where it is the default setting).
Shielded Trading – Live on Gnosis Chain, preventing front-running through encrypted mempool mechanics.
Shutter API – A developer-friendly encryption-as-a-service API, live on Gnosis Chain, powering time-locked predictions (e.g. Shutter Predict), sealed-bid auctions, and commit-reveal workflows.
The team working on the Arbitrum deployment includes:

Luis Bezzenberger – Product Manager
Leads technical scoping, product design, and coordination across engineering and external integrations. Luis has overseen the rollout of Shutter protocols and products and its use in Snapshot, Gnosis Chain, and several Shutter API based dapps.

Loring Harkness – Business Development & Partnerships
Manages strategic partnerships, grant relationships, and developer ecosystem alignment. Previously supported Shutter's integrations in governance and public goods funding contexts.

Anthony Caravello – Marketing
Oversees storytelling, product marketing, and technical content that makes Shutter tools understandable and useful for developers and governance communities.

Ulrich Petri – Developer
Focused on backend logic and protocol-level integration of Shutter’s threshold encryption stack.

Tatu Karki – Communications

Yousra Lembachar – Developer
Specializes in interface development, frontend integrations, and improving developer experience for projects adopting the API.

Shutter’s cryptographic experience and the live deployment of the Shutter API qualify us to deliver and maintain Shutter API on Arbitrum One.