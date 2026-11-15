# Ethereum Contract Metadata personal fork handover

Last updated: **15 November 2026, Australia/Brisbane**.

## Current work and immediate next action

The current task is to establish portable project context and a required session read/update workflow.
This is a documentation checkpoint prepared from the default-branch source, preserving existing project rules.
No application source, dependency, provider setting or production data was changed by this inventory.

**Next concrete action:** Inspect the actual metadata schema and fork divergence, then confirm the exact address/logo change and its official-source evidence before editing.

**Repository state:** [InfoAddict/eth-contract-metadata](https://github.com/InfoAddict/eth-contract-metadata), default branch `master`.
The source SHA below predates this documentation change. The commit containing this file identifies its documentation revision; verify the current remote before assuming a local checkout is synced. No deployment result is claimed.

## Purpose and source map

Forked Ethereum contract address metadata and logo mapping.

**Declared stack:** JavaScript package exporting an Ethereum contract-address metadata map and image assets.

- index.js: package entrypoint.
- contract-map.json and permitted-fields.json: metadata and allowed-field source.
- images/: logo assets; test/: package checks.

## Source checkpoint and milestones

- Source repository: [InfoAddict/eth-contract-metadata](https://github.com/InfoAddict/eth-contract-metadata).
- Visibility at inventory: public.
- Default branch: `master`.
- Exact pre-documentation head: `f6465d1c6d20be0ed190a1d8b7a432eff6366ba9`.
- Source tree SHA: `4947ede8f24c8ea7189d72842e89dd6e3aa5a823`.
- These identify the source inspected, not a newly verified deployment.

- [f6465d1](https://github.com/InfoAddict/eth-contract-metadata/commit/f6465d1c6d20be0ed190a1d8b7a432eff6366ba9) (2018-07-26, UTC): Delete hst.png.
- [a6e95f2](https://github.com/InfoAddict/eth-contract-metadata/commit/a6e95f26d0114f30b1a0ad5ef2746c9de5f89b3d) (2018-07-26, UTC): Add files via upload.
- [966a891](https://github.com/InfoAddict/eth-contract-metadata/commit/966a891dd9c79b873fd8968a0155b067ca630502) (2018-07-16, UTC): Merge pull request #110 from iqeon/master.
- [37639fe](https://github.com/InfoAddict/eth-contract-metadata/commit/37639fe617a9bcbc97d266462dbf8ddb64cf6f26) (2018-07-16, UTC): Merge pull request #94 from 0xProject/add-weth.
- [edc7e66](https://github.com/InfoAddict/eth-contract-metadata/commit/edc7e66ecb0d1ad06109e8676ca7016358f7de96) (2018-07-09, UTC): Merge pull request #111 from AugurProject/update-rep-token-address.

Commit titles report recorded changes. They are not fresh test, CI, browser or provider results.

## Existing decisions and boundaries

- This is a personal fork of MetaMask/contract-metadata, not an upstream contribution.
- The default branch is master; do not replace it with a main-based policy.
- README and CONTRIBUTING describe fork/PR submissions and official project/address evidence.
- CONTRIBUTING mentions icon-map.json while the actual root contains contract-map.json; inspect source before editing.

Preserve the relevant existing instructions and release route. This checkpoint does not create a portfolio-wide publishing policy.

## Outstanding work and uncertainty

- The latest fork commits date to July 2018 and concern uploaded/deleted assets.
- No current token/logo submission or maintenance task was identified.
- Do not interpret the upstream contribution checklist as proof that any existing token entry is currently verified.

No identifiable project-specific chat was found in the reviewed history inventory for this repository.
That is a coverage limit, not proof that no other chat, local work or decision exists.
The matching local checkout was clean on `master` at `f6465d1c6d20be0ed190a1d8b7a432eff6366ba9`, matching this remote source snapshot, in the 15 November inventory. Recheck before editing.

## Portable source references

- [README.md](README.md).
- [CONTRIBUTING.md](CONTRIBUTING.md).
- [contract-map.json](contract-map.json).
- [index.js](index.js).
- [package.json](package.json).

Existing specialised status/design/operating documents remain supporting records; they were not replaced.
Read linked documents for the selected task and reconcile their dates against current source.

## Evidence and validation limits

- Fresh authenticated GitHub reads established metadata, branch source, root paths and the commit history above.
- Selected source documentation and declared manifests informed this record.
- No application build, test, dependency install, rendered-browser check or live-provider workflow was run.
- Deployment, credentials, service readiness and current runtime behaviour remain unverified here.
- README completion labels and older evidence retain their original dates and scope.
- Recheck the branch head before publishing, and merge concurrent handover changes instead of overwriting them.

## Resume sequence

1. Read [AGENTS.md](AGENTS.md) and this handover, then the linked project contracts relevant to the request.
2. Inspect the actual branch/worktree and current remote source. Preserve unrelated and untracked work.
3. Inspect the actual metadata schema and fork divergence, then confirm the exact address/logo change and its official-source evidence before editing.
4. Verify only the selected task with appropriate checks; obtain any release authority required by the current request.
5. Update this handover before finishing, distinguishing local, committed, pushed, deployed and observed results.

## Session log

### 15 November 2026

- Requested: portable handover and required session continuity.
- Prepared: this source-based handover and the shared workflow in AGENTS.md; existing instruction text retained.
- Checked: remote source metadata, commit messages and available project documents.
- Not checked: application/runtime behaviour, provider/deployment state or other machines. Local status is limited to the dated inventory above.
- Next: Inspect the actual metadata schema and fork divergence, then confirm the exact address/logo change and its official-source evidence before editing.

## Resume prompt

> Read AGENTS.md and handover.md. Check the current source and worktree, preserve other work, and continue only the next scoped task. Treat historical claims as dated evidence. Update handover.md with actual checks and unfinished work before finishing.
