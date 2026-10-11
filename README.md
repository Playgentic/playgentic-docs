# playgentic docs

Website for [playgentic](https://github.com/playgentic/playgentic) (the Playwright-BDD suite scaffold) and [playgentic-agents](https://github.com/playgentic/playgentic-agents) (the agent plugin for Claude Code, GitHub Copilot and Codex).

It's a static site with no build step. It deploys to GitHub Pages at https://playgentic.github.io/playgentic-docs/ on every push to `main` (`.github/workflows/pages.yml`).

| Path | What |
| --- | --- |
| `index.html` | landing page |
| `docs/` | getting started, template guide, repo setup, agent harness |
| `playground/` | a deterministic app-under-test with stable `data-testid` selectors, useful as an end-to-end target for the agents |
| `assets/` | shared CSS and JS |

Preview locally with `python3 -m http.server`, then open http://localhost:8000.
