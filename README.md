# api-rate-limiter-service

Distributed sliding-window and token bucket rate limiter service with Redis backplane in TypeScript.

## Architecture & Design

This project implements a high-reliability distributed architecture designed for production workloads.
### Core Components
- `token_bucket`: Core subsystem handling specific domain logic, invariants, and performance guarantees.
- `sliding_window`: Core subsystem handling specific domain logic, invariants, and performance guarantees.
- `redis_storage`: Core subsystem handling specific domain logic, invariants, and performance guarantees.
- `leaky_bucket`: Core subsystem handling specific domain logic, invariants, and performance guarantees.
- `tiered_tiers`: Core subsystem handling specific domain logic, invariants, and performance guarantees.
- `metrics_exporter`: Core subsystem handling specific domain logic, invariants, and performance guarantees.

## Testing and Verification

Run the test suite via standard tooling.
