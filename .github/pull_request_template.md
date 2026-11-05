## Summary
<what changed and why, in one or two sentences>

Work item: AB#<id>  (use `Fixes AB#<id>` to close it on merge)

## Change type
Check exactly one.

- [ ] **Standard**: routine, low risk, follows an existing pattern (dependency bump, doc fix, small bug fix). Merges after review; no extra fields needed.
- [ ] **Normal**: new capability or anything with real risk. Fill in **Impact** and **Rollback plan** below.
- [ ] **Emergency**: hotfix for a production incident. Deploy first, then post in #taskflow-ops and add a short note below within one working day.

## Impact (required for Normal)
<who or what is affected: services, environments, users, data, downtime expected>

## Rollback plan (required for Normal)
<exact steps to undo this: revert commit, swap slot, shift traffic, flag off; who does it; how long it takes>

## Testing
- [ ] Tests added or updated
- [ ] Verified locally or in dev
- [ ] Not testable; explained here: <reason>

## Release notes
- [ ] I added a label so this appears under the right heading: `enhancement`, `bug`, `breaking-change`, `infra`, `pipelines` or `dependencies`

## Reviewer checklist
- [ ] Change type matches the actual risk
- [ ] Normal changes have both Impact and Rollback filled in
- [ ] No secrets or credentials in the diff
- [ ] Linked work item is correct
