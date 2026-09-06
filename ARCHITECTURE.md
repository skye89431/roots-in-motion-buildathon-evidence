# Architecture Evidence

## Canonical transaction flow

```text
SUPPLY
  ↓
MARKET INTELLIGENCE
  ↓
COMMERCIAL VIABILITY
  ↓
DEMAND
  ↓
WINNIE GOVERNANCE
  ↓
ACTION / MOVEMENT
  ↓
OUTCOME / LEARNING
```

## Responsibility and authority boundaries

| Component | Responsibility | Output | Authority boundary |
|---|---|---|---|
| Supply Agent | Understand grounded supply from seller / forecast evidence | Supply confidence / state | Cannot authorise execution |
| Market Intelligence Agent | Interpret wider market evidence | Observed market signal | Cannot declare transaction viability |
| Commercial Viability Agent | Test transaction economics | VIABLE / NEGOTIATE / NOT VIABLE | Cannot invent missing cost evidence |
| Demand Agent | Test grounded demand and provenance | Demand confidence / state | Cannot authorise movement |
| Winnie | Evaluate evidence, confidence and governance rules | GREEN / AMBER / RED | Controls execution authority |
| In Motion / Execution | Coordinate the permitted next action | Listing / commitment / movement / execution events | Acts only inside Winnie authority |
| Outcome Intelligence | Capture what happened | Reusable transaction signal | Outcome is evidence, not universal proof |

## Agentic loop

```text
EVIDENCE
  → UNDERSTANDING
  → SPECIALIST REASONING
  → DECISION
  → AUTHORITY
  → ACTION
  → OUTCOME
  → NEW EVIDENCE
```

## Governance states

### GREEN
- autonomous execution permitted
- no human approval required

### AMBER
- transaction pauses
- human approval required
- execution may resume after approval

### RED
- execution not permitted
- unsafe action stops

## Interoperability principle

Roots is designed as a coordination layer rather than a replacement for every seller, buyer, logistics or commerce interface.

Different interfaces may initiate or receive Roots actions while transaction-scoped governance and execution controls preserve a single governed transaction state.
