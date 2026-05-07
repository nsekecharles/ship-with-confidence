# Coupling Detector

Detect tight coupling and hidden dependencies that make systems brittle.

## What to check
- Cross-module imports that violate boundaries
- Shared mutable state
- Leaky abstractions
- Circular dependencies

## Prompts
- "What new dependencies were introduced and are they necessary?"
- "If this component fails or changes, what breaks?"

## Output
- Dependency graph (text) + risk areas
