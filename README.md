# Release Channel Only

This repository is an artifact-only update channel.

Rules:

- Do not commit or upload application source code.
- Do not add product documentation, screenshots, roadmaps, or changelogs here.
- Do not enable Issues, Discussions, Wiki, or Projects in this repository.
- Only the following release assets are allowed:
  - Windows installer artifact
  - updater signature artifact
  - `latest.json`
- All releases must be published automatically from the private source repository workflow.
- Do not publish assets manually unless recovery is strictly required.
- Normal source-code pushes do not update this repository.
- Only tagged or approved releases from the private source repository may update this repository.
- Keep release titles and asset names neutral. Do not add extra product information.

If this repository contains anything beyond the policy above, treat it as a drift incident and clean it immediately.
