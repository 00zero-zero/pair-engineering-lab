# Revert playbook

## Purpose

Prefer fast evidence-preserving rollback over emergency history rewriting when a merged change is unsafe.

## Invariants

- The change remains independently reviewable and reversible.
- Upstream authority stays behind pull-request review and merge.
- Authorship and verification evidence remain explicit.

## Verification

Compare the branch with upstream, verify the intended contract, and confirm both authors are mapped correctly before merge.
