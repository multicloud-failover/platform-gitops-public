## Summary

- What changed?
- Why was this change needed?

## Scope

- Affected clouds: AWS / GCP / both
- Affected resources: Deployment / Service / Ingress / Gateway / Secret integration / autoscaling / capacity / other
- Namespace or cluster-scoped impact:

## Risk Review

- Could this affect both primary and DR at the same time?
- Are any cluster-scoped resources changed?
- Does this require a coordinated platform change from `infra-terraform-public`?

## Rollback

- Exact rollback path:
- Is `git revert` sufficient?
- Any follow-up action required after revert?

## Validation

- [ ] Manifest validation workflow passed
- [ ] Image/tag/path references are correct
- [ ] README or runbook update was added if operator behavior changed
