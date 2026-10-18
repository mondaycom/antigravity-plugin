# Contributing

This repository is the monday.com plugin for Google Antigravity.

- **Skills** (`skills/`) are copied from [mondaycom/skills](https://github.com/mondaycom/skills) and must not
  be edited here. To change a skill, open a pull request in mondaycom/skills. Once it is merged, bump `ref`
  in `skills.json` (and `skills`, to add or remove one), run `scripts/sync-skills.sh` and open a pull request
  here with the result.
- **Everything else** (manifest, README, rules, MCP configuration, logo) is edited directly here through a
  pull request. Bump `version` in `.antigravity-plugin/plugin.json` with every release.
- **Product support:** [support.monday.com](https://support.monday.com).
