# Secret scanning workflow

## Purpose

Detect credential material before merge and define a revocation path when prevention fails.

## Invariants

- The change must remain independently reviewable and reversible.
- Repository authority stays in the upstream review and merge boundary.
- Authorship, verification evidence, and resulting history remain explicit.

## Verification

Review the branch diff against upstream, confirm the intended contract is represented accurately, and verify the final commit attribution before merge.
