# Test pyramid boundaries

## Purpose

Place fast contract tests near code and reserve expensive system tests for cross-boundary behavior.

## Invariants

- The change remains independently reviewable and reversible.
- Upstream authority stays behind pull-request review and merge.
- Authorship and verification evidence remain explicit.

## Verification

Compare the branch with upstream, verify the intended contract, and confirm both authors are mapped correctly before merge.
