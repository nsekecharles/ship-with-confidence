# Reliability

Validation skills focused on correctness under failure.

Use these skills to stress-test your system's behavior at the edges — catching unhandled scenarios, missing error handling, and fragile assumptions before they cause incidents.

## Skills

| File | Description |
|------|-------------|
| [edge-case-hunter.md](./edge-case-hunter.md) | Identify unexpected inputs, boundary conditions, and scenarios that could cause crashes or incorrect behavior. |
| [failure-scenario-simulator.md](./failure-scenario-simulator.md) | Simulate infrastructure and dependency failures to verify the system degrades gracefully. |

## When to use

Run a reliability skill when you:

- Add new business logic or data processing
- Integrate with external services or APIs
- Handle user-submitted or third-party data
- Modify error handling or retry logic
