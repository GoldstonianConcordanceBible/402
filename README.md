PONS 402

Status: GENESIS v2 — CONTROL PLANE BUILD
Default Posture: FAIL CLOSED
Core Doctrine: CAN ≠ MAY

PONS 402 is the governance, authorization, provenance, audit, and human-accountability control plane for PONS-controlled actions.

It does not claim control over third-party or immutable protocols merely because a PONS-controlled actor interacts with them.

⸻

WHAT 402 DOES

PONS 402 evaluates whether a PONS-controlled action may proceed.

It governs:

* PONS-controlled agents
* PONS-controlled wallets
* PONS-controlled treasuries
* PONS-controlled execution services
* PONS-controlled Labs
* PONS-controlled launch workflows
* PONS-controlled payment workflows
* PONS-controlled deployment workflows
* human approvals
* policy versions
* evidence
* provenance
* accounting reconciliation requirements
* Control Tower decisions

⸻

WHAT 402 DOES NOT DO

PONS 402 does not:

* turn AI recommendations into legal authority
* treat payment success as authorization
* treat wallet possession as governance authority
* treat token existence as a legal right
* claim control over third-party protocol code
* store private keys
* store seed phrases
* store signing secrets
* certify legal compliance by itself
* make an AI model the final source of human authority

⸻

CORE DOCTRINE

CAN ≠ MAY

Technical capability does not establish authorization.

A system may technically be capable of performing an action without being authorized to perform it.

⸻

CONTROL THE CORE. DISTRIBUTE THE RAILS.

PONS may use:

* public blockchains
* external protocols
* APIs
* facilitators
* AI models
* wallets
* marketplaces
* bridges
* payment systems
* launchpads

while maintaining an internal constitutional control layer over PONS-controlled authority.

⸻

AUGMENTATION WITHOUT ABDICATION

AI may:

* analyze
* monitor
* classify
* recommend
* simulate
* prepare
* reconcile
* report

AI does not automatically become:

* legal authority
* treasury authority
* fiduciary authority
* governance authority
* signing authority

⸻

PROVENANCE = THE SUPPLY CHAIN OF TRUST

Every material PONS-controlled action should be attributable to:

* originating request
* evidence
* applicable policy
* reviewer
* approval
* wallet
* entity
* contract
* execution result
* transaction
* accounting treatment
* resulting state

⸻

CONTROL SCOPE RULE

PONS 402 governs PONS-controlled authority and execution pathways. It does not claim authority over third-party or immutable protocols that do not implement a 402 enforcement hook.

Where a third-party system cannot enforce PONS 402 directly, PONS must enforce governance at a boundary it controls.

Examples include:

* agent
* wallet
* treasury
* API
* execution service
* signer
* deployment workflow
* Control Tower
* human operator

⸻

EVIDENCE RULE

Absence of verified evidence does not prove absence of a control. It produces NOT_ESTABLISHED. When that control is mandatory, execution remains HOLD.

PONS 402 does not convert missing evidence into certainty.

⸻

FAIL-CLOSED RULE

Missing, stale, contradictory, revoked, unsupported, expired, or unverifiable mandatory information must not result in automatic execution.

The system returns:

APPROVE

HOLD

or

DENY

No mandatory gate defaults to approval.

⸻

CANONICAL EXECUTION MODEL

REQUEST

↓

NORMALIZE

↓

RESOLVE OBJECTS

↓

VALIDATE SCHEMA

↓

EVALUATE POLICY

↓

HUMAN GATE WHERE REQUIRED

↓

SIMULATE WHERE REQUIRED

↓

CONTROL TOWER DECISION

↓

SEPARATE EXECUTION COMPONENT

↓

VERIFY RESULT

↓

RECONCILE

↓

ARCHIVE EVIDENCE

⸻

CANONICAL DECISION STATES

APPROVE

All mandatory controls required for the proposed action are satisfied.

Approval remains scoped to the exact authorized action.

⸻

HOLD

Execution must stop pending additional evidence, review, reconciliation, verification, or correction.

⸻

DENY

Execution is prohibited under the current policy state.

⸻

CANEXECUTE

The internal decision system should preserve explainable state.

It should not rely exclusively on a Boolean.

The authoritative internal decision is:

APPROVE

HOLD

or

DENY

A final execution adapter may derive:

canExecute: true

only when:

decision == APPROVE

Otherwise:

canExecute: false

⸻

EVIDENCE CLASSES

Every material claim should be classified as one of:

VERIFIED

Confirmed through authoritative evidence.

CORROBORATED

Supported by multiple independent sources or records.

AUTHOR_ORIGINATED

Provided by the project operator or originating source but not yet independently verified.

PROPOSED

Planned architecture or policy not yet implemented.

FUTURE_EXPERIMENT

Defined for later testing.

NOT_ESTABLISHED

Available evidence is insufficient to establish the claim.

CONTRADICTED

Available evidence materially conflicts with the claim.

⸻

HUMAN ACCOUNTABILITY

PONS 402 preserves accountable human governance for material actions.

AI recommendations are evidence inputs.

They are not signatures.

They are not legal approvals.

They are not treasury authority.

Where policy requires a Human Gate, approval must identify:

* accountable reviewer
* reviewer role
* action ID
* policy version
* scope
* relevant wallet
* relevant destination
* relevant contract
* relevant asset
* amount or maximum amount
* expiration
* simulation evidence where applicable
* approval decision

⸻

SEPARATION OF DUTIES

PONS 402 recognizes distinct control functions including:

* REQUESTER
* TECHNICAL_REVIEWER
* 402_REVIEWER
* TREASURY_APPROVER
* EXECUTION_OPERATOR
* POST_EXECUTION_AUDITOR

During Genesis, one person may occupy more than one function.

If so, that overlap must be recorded as:

CONTROL_CONCENTRATION

PONS 402 must not claim independent separation of duties where it does not actually exist.

⸻

APPROVAL BINDING

A material approval must be bound to the exact relevant execution parameters.

These may include:

* action ID
* policy version
* chain ID
* wallet ID
* destination
* contract address
* function selector
* asset
* maximum amount
* contract digest
* implementation digest
* simulation digest
* expiration

A material change invalidates the prior approval.

The action returns to:

HOLD

⸻

DECISION ≠ SIGNING

The PONS 402 decision engine must not contain signing credentials.

The Control Tower evaluates.

The signer executes only a valid, bounded authorization.

The intended separation is:

DECISION PLANE

↓

SCOPED AUTHORIZATION

↓

EXECUTION PLANE

This reduces the risk that a compromised AI model can convert its own recommendation directly into asset movement.

⸻

PAID ≠ AUTHORIZED

PONS 402 and x402 are distinct.

PONS 402 is the governance layer.

x402 may serve as an external machine-payment rail.

A successful payment does not override governance.

Payment signing or settlement must not automatically transform:

HOLD

or

DENY

into:

APPROVE

⸻

WALLET POSSESSION ≠ AUTHORITY

Control of a blockchain address does not independently establish permission to use it.

Wallet authority derives from:

* policy
* current registry state
* human authorization where required
* transaction scope
* evidence
* execution limits

⸻

TOKEN ≠ LEGAL RIGHT

A token must not automatically be interpreted as:

* equity
* debt
* ownership
* company shares
* revenue rights
* royalties
* yield
* guaranteed liquidity
* guaranteed appreciation
* redemption rights
* governance power

unless those rights are expressly created and separately documented.

⸻

PONS LABS

A Lab is a governed PONS object.

PONS 402 can govern PONS-controlled participation involving a Lab.

This may include:

* agent activity
* treasury activity
* wallet activity
* execution activity
* API activity
* deployment activity
* launch approval
* research activity
* accounting
* evidence
* Control Tower decisions

PONS 402 does not claim that a third-party launchpad, token contract, DEX, bridge, or immutable protocol automatically inherits 402 rules.

⸻

CURRENT LAB REGISTRY

Genesis v2 includes public registry records for:

* XLAB
* NLAB
* ELAB
* DLAB
* ABCLAB
* TLAB

Initial classification:

AUTHOR_ORIGINATED

Initial operational status:

HOLD

These records remain HOLD until required verification and governance conditions are satisfied.

⸻

THIRD-PARTY IDENTIFIERS

Some Lab concepts may reference public companies, technologies, or third-party brands.

Unless separately established by evidence, no:

* sponsorship
* endorsement
* partnership
* licensing
* ownership
* authorization
* official affiliation

should be inferred.

Specialist review may be required before public use of third-party marks.

⸻

WALLET REGISTRY

Genesis v2 uses public opaque wallet IDs rather than publishing unnecessary operational topology.

Public records may contain:

* wallet ID
* public address
* observed chain
* observed account type
* evidence class
* status
* evidence references

Sensitive operational relationships belong in an appropriately restricted governance system.

No secrets belong in either location.

⸻

NETWORK POLICY

The current intended PONS execution environment is:

Robinhood Chain Mainnet

Chain ID: 4663

Native gas asset: ETH

Other networks require explicit policy approval.

The existence of an address on an EVM-compatible network is not, by itself, proof of role or ownership.

⸻

CONTROL TOWER

ENOCH ONE may function as the supervisory intelligence layer of the PONS Control Tower.

The Control Tower may:

* synthesize evidence
* detect contradictions
* inspect gate state
* identify missing evidence
* monitor risk
* produce recommendations
* route decisions for human review
* generate reports
* reconcile policy state

The Control Tower does not independently manufacture legal or governance authorization.

⸻

AI HOMEBoy

AI Homeboy may provide shared AI infrastructure supporting PONS and ENOCH ONE.

AI infrastructure remains subordinate to PONS 402 governance.

The AI provider is infrastructure.

It is not sovereign authority.

⸻

CONTROL MATURITY

PONS 402 does not use an LLM score as the authoritative measure of readiness.

Each material control progresses through four stages:

DOCUMENTED

↓

ENFORCED

↓

TESTED

↓

VERIFIED

The authoritative maturity record is:

CONTROL-MATRIX.md

⸻

REPOSITORY STRUCTURE

PONS 402 Genesis v2 includes:

README.md

CONSTITUTION.md

ARCHITECTURE.md

CONTROL-MATRIX.md

SECURITY.md

THREAT-MODEL.md

DISCLOSURES.md

CONTRIBUTING.md

CHANGELOG.md

schemas/

policies/

registry/

engine/

tests/

examples/

reviews/

.github/

⸻

MACHINE-READABLE CONTROL

The intended progression is:

DOCTRINE

↓

SCHEMA

↓

POLICY

↓

VALIDATOR

↓

GATE

↓

AUTHORIZATION

↓

DECISION

↓

EXECUTION

↓

EVIDENCE

↓

RECONCILIATION

↓

AUDIT

⸻

REVIEW ARCHITECTURE

PONS 402 separates AI-assisted review into four passes.

PASS A — REPOSITORY CONTROL REVIEW

Pinned repository and commit SHA.

No unsupported blockchain claims.

PASS B — EVIDENCE RECONCILIATION

Deterministically collected evidence is reconciled against repository claims.

PASS C — ADVERSARIAL CONTROL TEST

Explicit attacks are tested against expected fail-closed behavior.

PASS D — SPECIALIST ESCALATION

Legal, regulatory, accounting, tax, trademark, privacy, AML, sanctions, or other specialist issues are escalated to appropriate humans.

Combined AI output should be labeled:

PONS 402 MULTI-MODEL ADVERSARIAL RESEARCH MEMORANDUM

AI consensus alone is not audit certification.

⸻

SECURITY

Never commit:

* private keys
* seed phrases
* mnemonics
* signing shares
* API secrets
* RPC credentials
* facilitator credentials
* privileged recovery procedures
* confidential legal communications
* unnecessary exploit-relevant topology

⸻

NORTH STAR

PONS 402 exists to make machine-scale execution accountable.

The technical hierarchy is:

CONSTITUTION

↓

POLICY

↓

HUMAN ACCOUNTABILITY

↓

MACHINE ASSISTANCE

↓

AUTHORIZED EXECUTION

↓

EVIDENCE

↓

AUDIT

Never:

MACHINE AUTHORITY → HUMAN EXCUSE

⸻

STATUS

PONS 402 — GENESIS v2

This repository is under active development.

Presence in this repository does not constitute production approval.

Until a mandatory control is documented, enforced, tested, and verified where required, the system must remain appropriately restricted.

FAIL CLOSED.

CAN ≠ MAY.