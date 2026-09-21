# Merge queue discipline

## Purpose

Retest candidate integration states so individually green pull requests cannot race into a broken default branch.

## Invariants

- The change must remain independently reviewable and reversible.
- Repository authority stays in the upstream review and merge boundary.
- Authorship, verification evidence, and resulting history remain explicit.

## Verification

Review the branch diff against upstream, confirm the intended contract is represented accurately, and verify the final commit attribution before merge.
