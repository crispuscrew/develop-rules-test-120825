<!-- PR for /release branches. Keep it delta-only relative to the release issue. -->

## Related Issue
<!-- Use a closing keyword e.g., Closes #123.
     Note: GitHub auto-closes the issue ONLY after this PR is merged
     into the repository’s default branch (e.g., main). -->
Closes #...

## Version
<!-- Target version, e.g., vX.Y.Z -->
vX.Y.Z

## Delta vs Issue
<!-- Anything done here beyond what's described in the release issue (if any). Keep it short. -->

## Checklist
- [ ] Branch name is `release/vX.Y.Z`
- [ ] CHANGELOG updated
- [ ] Release commit present (empty or summary)
- [ ] Tag `vX.Y.Z` created and pushed (as per process)
- [ ] CI green
- [ ] Merge via **squash**

## Verification
<!-- How the release was verified: QA summary, smoke tests, artifacts. -->
1. ...
2. ...

## Risk / Rollback
<!-- Potential issues; how to revert quickly if needed (revert PR, remove/retag, rollback plan). -->
- Risk: ...
- Rollback: ...
