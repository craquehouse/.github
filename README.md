# .github

Org-wide defaults and shared conventions for [craquehouse](https://github.com/craquehouse)
repositories. GitHub applies the community-health files here (Code of Conduct,
contributing guidelines, issue/PR templates, funding) to any repo in the org that
doesn't provide its own.

## What lives here

| Path | Purpose |
| --- | --- |
| `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md` | Org-wide policies |
| `.github/ISSUE_TEMPLATE/`, `.github/pull_request_template.md` | Default issue/PR templates |
| `.github/safe-settings/` | Org repository settings reconciled by [safe-settings](https://github.com/github/safe-settings) |
| `.github/workflows/` | Shared automation: Renovate, safe-settings, stale |
| `.editorconfig`, `.oxfmtrc.json`, `.prettierignore`, `.shellcheckrc` | Formatting/lint defaults |
| `.mise/`, `.lefthook.toml`, `lefthook.common.toml` | Tooling and git-hook conventions |
| `.renovaterc.json5` | Renovate preset (extends `craquehouse/renovate-config`) |

Individual repos may override any of these by shipping their own copy.
