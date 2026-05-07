# Query Analysis

Find slow or risky database queries and access patterns.

## What to check
- Missing indexes
- N+1 queries
- Full table scans
- Unbounded result sets

## Prompts
- "List every query affected and its expected cardinality."
- "Is there any path that can return unbounded rows?"

## Output
- Query inventory + index recommendations
