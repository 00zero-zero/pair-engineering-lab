# Review evidence chain

A merged change should preserve a traceable chain from intent to implementation, verification, review, and integration.

The pull request description captures the intended change. Commits record implementation history and authorship. Automated checks provide machine-generated evidence tied to the exact revision. Human review records semantic judgment about correctness, risk, and maintainability. The merge event binds those artifacts to the upstream history.

When any link is missing, later maintainers have to reconstruct decisions from incomplete evidence. Keeping the chain explicit improves rollback, incident analysis, and long-term repository archaeology.

The chain should remain independently auditable without granting contributors direct write access to the canonical repository.
