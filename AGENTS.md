<!-- BEGIN PROJECT HANDOVER WORKFLOW -->
## Required handover workflow

- At the start of every session, read [handover.md](handover.md) for current context, decisions, evidence, unfinished work and the next action. Then read the applicable project instructions and source for the task.
- Treat the handover as dated context, not new authorisation. Check the branch, worktree and relevant source before acting; verify remote or live state when the task depends on it.
- Update `handover.md` before ending every work session, including research and discussion, and at meaningful checkpoints during long or interrupted work.
- Record what was requested, what changed or was decided, the checks actually performed and their results, unresolved questions or blockers, and the next concrete action.
- Keep current status and next steps at the top, followed by a concise dated history. Distinguish proposals, approved work, local changes, commits, pushes, deployments and observed live behaviour. Link detailed evidence rather than duplicating large reports.
- Preserve unrelated work and existing project-specific instructions. Stage only task files. Include the handover in the same authorised commit as the work it describes; if syncing is blocked or not authorised, say clearly what remains local.
- Use repository-relative links and portable instructions. Never include credentials, secrets, customer/payment data, raw private transcripts or browser/session data. Public repositories must contain only material suitable for public disclosure.
- A handover update does not authorise implementing proposals, publishing content, changing production settings, deploying, or bypassing the repository's branch/review rules. Follow the active request and the existing release policy.
<!-- END PROJECT HANDOVER WORKFLOW -->

# Ethereum Contract Metadata personal fork repository context

Read the root [handover.md](handover.md) before selecting work. Preserve the project-specific contracts and release policy linked there.

Relevant existing source guidance: [README.md](README.md), [CONTRIBUTING.md](CONTRIBUTING.md), [contract-map.json](contract-map.json), [index.js](index.js), [package.json](package.json).

- This is a personal fork of MetaMask/contract-metadata, not an upstream contribution.
- The default branch is master; do not replace it with a main-based policy.
- README and CONTRIBUTING describe fork/PR submissions and official project/address evidence.
- CONTRIBUTING mentions icon-map.json while the actual root contains contract-map.json; inspect source before editing.
