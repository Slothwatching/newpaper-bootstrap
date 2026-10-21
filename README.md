# newpaper

Public application repository. Clone it alongside the private `newpaper-ops` repository under the same parent directory.

Git history here shows what changed. Internal maintainers record each user's reason and expected outcome in `../newpaper-ops/INTENT_LOG.md` before implementation, using a stable intent ID. Append each submission attempt and its outcome, including failed, rejected, cancelled, or unmerged work, with code PR or commit references when available. Push the private record regardless of whether the code is accepted. Preserve changed decisions as superseded entries linked to their replacements.

Both maintainers use branches and PRs to change `main`; either may merge a PR without the other's approval. Direct pushes to `main` are blocked. Required CI checks will be added after the CI workflow is working. Contributors without private repository access can explain their intent in a public PR; an internal maintainer transfers it to the private log. Keep confidential details out of public PRs.

The workspace opens both repositories together; it does not automatically synchronize files. Do not duplicate code diffs in the intent log or commit credentials or customer data to either repository.

Open `../newpaper-ops/newpaper.code-workspace` in VS Code to work with both repositories together.
