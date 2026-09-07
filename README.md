# legacy-sync-engine

Bi-Directional Legacy Sync Engine Real-time sync between a modern and a ~20-year-old on-prem SQL database with conflict resolution.

Solving:
- Change detection without wrecking a legacy system performance.
- Bi-directional infinite loop problem
- conflict resolution and consistency
- Networking on on-prem constraints
- How all solved with semantic index to produce sub-second latency from on-prem database

Simulation constraints setting before the project:
1. Legacy system: Microsoft SQL Server (2008 / 2012)
2. Kafka 
3. Case study + runnable demo using docker compose
