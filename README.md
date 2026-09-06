# Roots In Motion — Future Caribbean Buildathon 2026

**Founder:** Tasia-Skye Robinson  
**Track:** Open Track  
**Buildathon:** Future Caribbean Buildathon 2026

## What this repository is

This is a **public Buildathon evidence repository**, not the full Roots 246 production codebase.

It exists to document what was built and tested during the Future Caribbean Buildathon while protecting credentials, private datasets, proprietary operating material and commercially sensitive implementation details.

The repository intentionally provides evidence of system behaviour and testing rather than the full proprietary implementation.

## Buildathon question

> Can multiple specialist agents coordinate one changing Caribbean commerce transaction from supply to a governed, fulfilment-ready outcome?

Fresh produce in Barbados was used as the initial pressure test.

## Core transaction chain

**SUPPLY → MARKET INTELLIGENCE → COMMERCIAL VIABILITY → DEMAND → GOVERNANCE → ACTION / MOVEMENT → OUTCOME / LEARNING**

## Agentic operating model

The prototype coordinates specialist capabilities across a transaction:

- **Supply Agent** — interprets supply-side evidence.
- **Market Intelligence Agent** — interprets relevant market evidence.
- **Commercial Viability Agent** — assesses transaction viability.
- **Demand Agent** — interprets demand-side evidence.
- **Winnie** — proprietary Roots 246 governance infrastructure.
- **In Motion / Execution** — coordinates permitted transaction actions.
- **Outcome Intelligence** — captures transaction outcomes as reusable network intelligence.

The public repository intentionally abstracts proprietary governance logic, decision mechanisms and implementation.

## Controlled execution paths

The prototype was tested across three governed execution conditions.

### GREEN

Where the transaction met the conditions for autonomous execution, the system proceeded without human intervention.

Observed controlled behaviour:

- GREEN path reached;
- no human approval required;
- listing created;
- seller commitment created;
- movement planned;
- autonomous execution completed.

### AMBER

Where human judgement was required, autonomous execution did not continue.

Observed controlled behaviour:

- AMBER path reached;
- execution paused;
- human approval was recorded;
- the same transaction resumed;
- listing created;
- seller commitment created;
- movement planned following approval.

### RED / Rejected

Where execution was not permitted, the system stopped rather than silently proceeding.

This provided a controlled test of the system's ability not only to act, but also to pause or stop when required.

## Acceptance evidence

The final orchestrator acceptance suite completed with:

**112 assertions passed · 0 failed · exit code 0**

Coverage included:

- GREEN autonomous path;
- AMBER pre-approval behaviour;
- AMBER approval and resume;
- RED / rejected behaviour;
- idempotency;
- uniqueness;
- duplicate-execution protection;
- retry behaviour;
- transaction continuity;
- final verification.

See [`TEST_RESULTS.md`](TEST_RESULTS.md).

## What the Buildathon prototype demonstrates

The controlled prototype demonstrates that:

1. **Multiple evidence sources can inform one transaction.**
2. **One evidence object can inform multiple specialist agents.**
3. **Different interfaces and systems can initiate or receive Roots actions.**
4. **Governance can control autonomous, human-reviewed and stopped execution paths.**
5. **A completed transaction can produce intelligence reusable by the wider network.**

Together, these tests demonstrate the operating pattern:

**EVIDENCE → SPECIALIST REASONING → GOVERNANCE → ACTION → OUTCOME → LEARNING**

## Why this matters

Caribbean commerce does not necessarily begin with an absence of products, demand, businesses, knowledge or routes.

The coordination challenge is connecting what already exists well enough for commerce to move.

Roots In Motion tests whether agentic infrastructure can help coordinate that journey across fragmented evidence, specialist reasoning, governance and execution.

The Buildathon prototype uses fresh produce as the pressure test.

The wider infrastructure question is whether the same coordination model can eventually support more products, participants, systems and Caribbean corridors.

## What this does not claim

This repository does **not** claim that Roots In Motion is already commercially deployed at scale.

The Buildathon established controlled technical proof.

The next stage is real-world validation through:

1. a live seller + buyer + product transaction;
2. real logistics movement, capacity and exceptions;
3. commercial validation of who pays, what value is created and what becomes repeatable;
4. testing the coordination model beyond the initial Barbados use case.

The distinction is deliberate:

**The Buildathon tested whether the system can coordinate.  
The next test is whether that coordination creates repeatable value in the real economy.**

## Public repository scope

This repository is intentionally limited.

The following are **not published**:

- credentials or `.env` files;
- API keys, tokens or secrets;
- private datasets;
- private seller or buyer information;
- proprietary Roots 246 operating material;
- Winnie architecture;
- Winnie governance logic;
- Winnie rules and decision mechanisms;
- Winnie implementation;
- internal runtime files;
- advisor correspondence;
- private commercial evidence;
- full proprietary production implementation.

Their exclusion from this public evidence repository is intentional and should not be interpreted as their absence from the wider project.

## Repository contents

### `ARCHITECTURE.md`

Public-level description of the prototype architecture and agentic coordination pattern.

### `BUILDATHON_EVIDENCE.md`

Summary of the evidence produced during the Buildathon.

### `TEST_RESULTS.md`

Controlled acceptance-test evidence and final orchestrator test result.

### `SECURITY.md`

Public repository security and disclosure boundaries.

### `NOTICE.md`

Repository scope, ownership and intellectual-property notice.

## Supporting submission evidence

The wider Future Caribbean Buildathon submission package contains:

- Project Overview / Executive Summary
- Final Pitch
- Demo + Judge Walkthrough
- Business + Commercial Case
- Technical + Agentic AI Case
- TRL + Acceptance Testing Evidence
- Evidence Index + Links

## Current status

**BUILDATHON PROTOTYPE: CONTROLLED TECHNICAL PROOF COMPLETED**

**Final orchestrator acceptance result: 112 assertions passed · 0 failed**

**Next pressure test: real commerce.**

---

**Roots In Motion**  
A Roots 246 initiative.

© 2026 Tasia-Skye Robinson. All rights reserved.e infrastructure question.**
