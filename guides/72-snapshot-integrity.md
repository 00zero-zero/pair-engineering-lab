# Snapshot integrity

## Purpose

Bind each snapshot to a source position and digest so recovery can verify that materialized state is complete and untampered.

## Design notes

- Keep the authority boundary explicit so operational convenience cannot silently redefine correctness.
- Surface failure and saturation as typed outcomes rather than hidden fallback behavior.
- Preserve enough provenance to explain the decision path after a retry, recovery, or incident.

## Verification

Review the branch against upstream, verify the contract under both normal and failure conditions, and confirm the final GitHub commit maps both credited authors correctly.
