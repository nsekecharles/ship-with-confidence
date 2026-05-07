# Load Reasoning

Reason about load, bottlenecks, and scaling behavior before running a full load test.

## What to check
- Expected QPS, concurrency, payload sizes
- Critical path calls and fan-out
- Caching opportunities
- Backpressure behavior

## Prompts
- "Given N users and M actions per user, estimate QPS and hotspots."
- "What is the most expensive code path and how does it scale?"

## Output
- A simple load model and bottleneck hypotheses
