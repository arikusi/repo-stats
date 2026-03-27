# repo-stats

Automated GitHub traffic tracker for all [arikusi](https://github.com/arikusi) public repositories.

Runs daily via GitHub Actions using [jgehrcke/github-repo-stats](https://github.com/jgehrcke/github-repo-stats). Automatically discovers new public repos — no manual configuration needed.

## Tracked metrics

* Unique and total views per day
* Unique and total clones per day
* Top referrers and paths
* Stargazer and fork evolution

## Reports

Stats are published via GitHub Pages:

* [deepseek-mcp-server](https://arikusi.github.io/repo-stats/arikusi/deepseek-mcp-server/)
* [nakkas](https://arikusi.github.io/repo-stats/arikusi/nakkas/)
* [supervis](https://arikusi.github.io/repo-stats/arikusi/supervis/)

## Setup

Requires a classic PAT with `repo` scope, stored as `GHRS_GITHUB_API_TOKEN` repository secret.
