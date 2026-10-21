# newpaper

Public application repository. Clone it alongside the private `newpaper-ops` repository under the same parent directory.

Git history here shows what changed. Internal maintainers record each user's reason and expected outcome in `../newpaper-ops/INTENT_LOG.md` before implementation, using a stable intent ID. After implementation, add the code PR or commit reference and result, then commit and push the record. Preserve changed decisions as superseded entries linked to their replacements.

Submit changes through PRs: one maintainer authors the change and the other approves before merge. External PRs need both maintainers' approval. Contributors without private repository access can explain their intent in the public PR; an internal maintainer transfers it to the private log. Keep confidential details out of public PRs.

The workspace opens both repositories together; it does not automatically synchronize files or enforce approvals. Do not duplicate code diffs in the intent log or commit credentials or customer data to either repository.

Open `../newpaper-ops/newpaper.code-workspace` in VS Code to work with both repositories together.
