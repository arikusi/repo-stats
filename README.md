# repo-stats

Automated GitHub traffic tracker for all [arikusi](https://github.com/arikusi) public repositories.

Runs daily via GitHub Actions using [jgehrcke/github-repo-stats](https://github.com/jgehrcke/github-repo-stats). Automatically discovers new public repos — no manual configuration needed.

## Reports

| Repository | Report |
|---|---|
| deepseek-mcp-server | [view report](arikusi/deepseek-mcp-server/latest-report/report.html) |
| nakkas | [view report](arikusi/nakkas/latest-report/report.html) |
| supervis | [view report](arikusi/supervis/latest-report/report.html) |
| claude-sage | [view report](arikusi/claude-sage/latest-report/report.html) |
| sahaf | [view report](arikusi/sahaf/latest-report/report.html) |
| arikusi-marketplace | [view report](arikusi/arikusi-marketplace/latest-report/report.html) |
| xinis-engine | [view report](arikusi/xinis-engine/latest-report/report.html) |
| arikusi | [view report](arikusi/arikusi/latest-report/report.html) |

## Tracked metrics

* Unique and total views per day
* Unique and total clones per day
* Top referrers and paths
* Stargazer and fork evolution

## Setup

Requires a classic PAT with `repo` scope, stored as `GHRS_GITHUB_API_TOKEN` repository secret.
