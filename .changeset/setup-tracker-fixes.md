---
"mattpocock-skills": patch
---

`setup-matt-pocock-skills` now creates missing triage labels on GitHub/GitLab (#616), fixes the GitLab template's `glab` commands (#635), reads GitHub issues with `--json` so labels and body come through (#733), names the "Label in our tracker" column in `triage-labels.md` (#801), and fixes the GitHub tracker recipes for native blockers and sub-issues, exact wayfinder frontier selection, PR reads in non-TTY output, and comment-before-close ordering (#855, #873, #1118, #1138). Re-run `/setup-matt-pocock-skills` to refresh `docs/agents/`.
