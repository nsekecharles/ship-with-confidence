# Failure Scenario Simulator

Simulate failures to ensure graceful degradation and recovery.

## What to check
- Downstream timeouts/errors
- Partial failures in multi-step workflows
- Data corruption and rollback strategies
- Circuit breakers and retries

## Prompts
- "Walk through this flow when dependency X times out."
- "Where do we lose data or double-write?"

## Output
- Failure matrix (scenario → expected behavior)
