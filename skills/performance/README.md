# Performance

Validation skills focused on latency, throughput, and cost.

Use these skills to reason about how your system will behave under load and to catch inefficient patterns before they become production bottlenecks.

## Skills

| File | Description |
|------|-------------|
| [load-reasoning.md](./load-reasoning.md) | Simulate your system under increasing load and identify bottlenecks before they appear in production. |
| [query-analysis.md](./query-analysis.md) | Detect inefficient database access patterns including N+1 queries, missing indexes, and over-fetching. |

## When to use

Run a performance skill before pushing when you:

- Add or modify database queries
- Introduce loops or bulk data processing
- Add new API endpoints or change response payloads
- Integrate with external services
