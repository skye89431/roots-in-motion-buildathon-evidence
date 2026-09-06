# Acceptance Test Results

## Final orchestrator suite

**Result: 112 passed · 0 failed · exit code 0**

| Test section | Assertions | Result |
|---|---:|---|
| TEST 1: GREEN PATH | 36 | PASS |
| TEST 1b: IDEMPOTENCY | 4 | PASS |
| TEST 1c: UNIQUENESS | 3 | PASS |
| TEST 2: AMBER pre-approval | 15 | PASS |
| TEST 3: AMBER approved resume | 20 | PASS |
| TEST 4: IDEMPOTENCY retry | 6 | PASS |
| TEST 5: REJECTED | 10 | PASS |
| TEST 6: RED | 5 | PASS |
| FINAL VERIFICATION | 8 | PASS |

## GREEN behaviour

The final controlled GREEN path preserved:
- governance = GREEN;
- human approval not required;
- authority = `AGENT_AUTONOMOUS`;
- no AIRecommendation required for GREEN human review;
- execution by `SYSTEM:WINNIE`.

## AMBER behaviour

The final controlled AMBER path preserved:
- governance = AMBER;
- status = `PAUSED_APPROVAL`;
- human approval required;
- AI recommendation created;
- human decision approval recorded;
- execution resumed after approval.

## Movement-origin assertion

The final Sweet Potato movement-origin test was corrected so the assertion resolves:

```text
transaction.supplyForecastId
→ selected SupplyForecast
→ forecast seller
→ grounded seller business/location data
→ movement.origin assertion
```

No seller name was hardcoded.

The correction changed the **test assertion**, not production orchestration logic.

## Production-code integrity

The reported verification found no changes to the production orchestration paths checked during the final movement-origin correction. The change was confined to the orchestrator test assertion.
