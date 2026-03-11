# JouleBridge Data Contracts

This directory is the source of truth for system-to-system data shapes.

Contracts that belong here:

- canonical event
- proof envelope
- sync batch
- evidence pack
- evidence pack request
- settlement record
- policy bundle
- device registration
- device heartbeat

Change rule:

1. update contract here first
2. version the change
3. update producer
4. update consumer

Do not hide shared contracts inside individual product folders.
