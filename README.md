# Roots In Motion — Future Caribbean Buildathon 2026

**Founder:** Tasia-Skye Robinson  
**Track:** Open Track  
**Buildathon:** Future Caribbean Buildathon 2026

## What this repository is

This is a **public Buildathon evidence repository**, not the full Roots 246 production codebase.

It exists to show what was built and tested during the Buildathon while protecting credentials, private datasets, proprietary operating material and commercially sensitive implementation details.

## Buildathon question

> Can multiple specialist agents coordinate one changing Caribbean commerce transaction from supply to a governed, fulfilment-ready outcome?

Fresh produce in Barbados was used as the pressure test.

## Core transaction chain

**SUPPLY → MARKET INTELLIGENCE → COMMERCIAL VIABILITY → DEMAND → WINNIE GOVERNANCE → ACTION / MOVEMENT → OUTCOME / LEARNING**

## Agentic operating model

- **Supply Agent** — interprets seller and forecast evidence.
- **Market Intelligence Agent** — interprets wider market evidence.
- **Commercial Viability Agent** — tests whether a specific transaction makes economic sense.
- **Demand Agent** — evaluates grounded demand and provenance.
- **Winnie** — governs what evidence is permitted to prove and whether the system may act.
- **In Motion / Execution** — coordinates permitted actions.
- **Outcome Intelligence** — turns transaction outcomes into reusable network intelligence.

### Critical distinction

**The agents determine what the evidence means. Winnie determines what that evidence is allowed to authorise. In Motion coordinates what happens next.**

## Controlled execution paths

### GREEN
A transaction with sufficient evidence can execute autonomously.

Observed controlled behaviour:
- governance returned GREEN;
- no human approval required;
- listing created;
- seller commitment created;
- movement planned;
- execution attributed to `SYSTEM:WINNIE`.

### AMBER
A transaction without sufficient evidence for autonomous action pauses for human judgement.

Observed controlled behaviour:
- governance returned AMBER;
- status moved to `PAUSED_APPROVAL`;
- human approval was recorded;
- execution resumed;
- listing, seller commitment and movement were created after approval.

### RED / Rejected
Where governance does not permit execution, the system stops rather than silently proceeding.

## Acceptance evidence

The final orchestrator acceptance suite completed with:

**112 assertions passed · 0 failed · exit code 0**

Coverage included:
- GREEN path
- idempotency
- uniqueness
- AMBER pre-approval
- AMBER approval + resume
- retry behaviour
- rejected path
- RED path
- final verification

See [`TEST_RESULTS.md`](TEST_RESULTS.md).

## What this proves

The controlled prototype demonstrates:
1. multiple evidence sources can inform one transaction;
2. one evidence object can inform multiple specialist agents;
3. different interfaces/systems can initiate or receive Roots actions;
4. Winnie controls what each evidence item is permitted to prove and whether Roots may act;
5. a completed transaction can create reusable network intelligence.

## What this does **not** claim

This repository does not claim live commercial deployment at scale.

The next tests are:
1. a live seller + buyer + product transaction;
2. real logistics movement, capacity and exceptions;
3. commercial proof of who pays and what value repeats;
4. a second corridor beyond the initial Barbados fresh-produce test.

## Public-repository scope

The following are intentionally **not published** here:
- credentials or `.env` files;
- Shopify tokens or secrets;
- private datasets;
- Winnie operating spreadsheets;
- internal Shogo runtime files;
- advisor correspondence;
- private commercial evidence;
- full proprietary production implementation.

## Supporting submission evidence

The Future Caribbean submission pack also contains:
- Final Pitch
- Judge Walkthrough
- Business + Commercial Case
- Technical + Agentic AI Case
- TRL + Acceptance Testing evidence
- Evidence Index + Links

---

**Fresh produce was the pressure test. Roots 246 is the infrastructure question.**
