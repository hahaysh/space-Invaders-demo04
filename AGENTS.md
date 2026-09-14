# Agent guidelines

- Protect existing user changes, files, App metadata, and commit history. Do not
  overwrite or delete them without explicit approval.
- Never expose secrets in files, logs, commits, or external transfers.
- Read README.md (entry guide), PRD.md (product requirements), TRD.md (technical
  design), and other relevant existing documents before making changes. Follow
  them; flag conflicts or missing decisions rather than inventing requirements.
- Keep changes small and limited to the approved task; avoid unrelated cleanup.
- Report validation actually performed, its scope, and its results. Clearly
  distinguish verified behavior from failures, blocked checks, and unverified
  assumptions. Never claim an unrun check passed.
- Keep planning separate from execution: proposals alone do not authorize file
  changes, installation, or execution of the proposed work.
- Before pushing, opening a PR, or deploying, review the diff and validation
  results for unintended changes and secrets, and obtain explicit user approval
  for the specific remote action. Local editing approval is not publication
  approval.
