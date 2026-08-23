# pr-assets

Public image hosting for embedding screenshots in pull requests of private Limetric repositories. GitHub's image proxy cannot fetch private raw URLs, so PR-embedded images must be publicly reachable.

**Everything in this repository is publicly accessible.** Only upload screenshots that contain no secrets, credentials, or customer data. Files may be pruned at any time; embedded links in old PRs will then break, which is acceptable.

Uploads are done by the `visual-evidence` skill in [Limetric/agent-skills](https://github.com/Limetric/agent-skills) via the GitHub contents API. Layout: `<repo>/<pr-or-branch>/<random>-<name>.png`.
