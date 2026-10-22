# Fresh BREAKER handoff — missing-parent fixture

Repository: SpanFabric/.github
Base: 5068eb341e90f05b45144f7cde0fa53466052a0b
Material: d64de9d700a1d961ae6184921f582f1f74d61d53
Digest: 3c0a241f473aae11d7f0b2755565fc1a1fb7699305ce5696c5c097e44c523f75
Changed material: tests/verification/test_lifecycle_history.py
Builder ceiling: INDEPENDENT_REVIEW_PENDING

Reconstruct independently; Builder claims and CI are untrusted until checked.
Attack loose/GC/repack storage, GC commit-graph exit0 with incomplete traversal, paired valid/corrupt tips, exact absent 40-hex nonzero grandparent, successful base guard, strict direct+immutable runner history rejection, and positive restoration with malformed objects still present but unreachable.
Reproduce historical setup failure after GC without rerunning/deleting historical Actions run39800181504. Confirm validator/policy/runner/workflows unchanged, full authority/shallow/root/history regressions, old Owner/Breaker evidence inactive, material digest exact, and exact new PR-head verification-gate/bootstrap-integrity/windows prerequisite success.
Do not remediate, merge, accept as Owner, touch UP-003 or persistence PRs, or start MIG-001.
