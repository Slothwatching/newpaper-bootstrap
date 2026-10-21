# Agent Instructions

- Keep public application code in this repository.
- Internal maintainers: before implementing each user-requested change or attempting a submission, record the intent in `../newpaper-ops/INTENT_LOG.md`. Reuse the stable intent ID for retries of the same request. Record the request, why the user wants it, and the expected outcome or constraints. Preserve the user's wording when it matters; mark an unknown reason as pending clarification rather than inventing it.
- Append each submission attempt's result and code PR or commit reference under that intent, including failures, rejected PRs, cancellations, and unmerged work. Preserve earlier attempts. Record meaningful outcomes rather than raw terminal transcripts.
- Commit and push the private intent records even when the code change is rejected or unfinished. Distinguish submitted PRs from changes approved and merged. The private log does not require peer approval.
- When a decision changes, retain the original entry, mark it as superseded or cancelled, and link the replacement intent ID with the reason for the change.
- External contributors without access to the private repository should explain their intent in the public PR, omitting confidential details. An internal maintainer records it in the private log. Never require an external contributor to obtain private access.
- Submit changes to this public repository through PRs. For work by either `vwu996` or `felixleung828`, the other maintainer must approve before merge. External PRs need both maintainers' approval. Do not approve on someone else's behalf. Keep private intent details out of public PRs; reference only the intent ID where appropriate.
- Git history records the implementation. Do not repeat code diffs in the intent log.
- Never commit secrets, tokens, passwords, or customer data to either repository.
