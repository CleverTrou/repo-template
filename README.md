# repo-template

Use this as the starting point for new repos. Includes:

| Tool | What it does |
|------|-------------|
| [Gitleaks](https://github.com/gitleaks/gitleaks) | Pattern-based secret scan on every push/PR (no license needed for personal accounts) |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Verified secret scan — contacts live APIs to confirm secrets are real |
| [Dependabot](https://docs.github.com/en/code-security/dependabot) | Weekly PRs for outdated dependencies and GitHub Actions versions |

## Creating a new repo from this template

On GitHub: **Use this template → Create a new repository**

After creating, edit `.github/dependabot.yml` and keep only the ecosystems the repo actually uses:
- `npm` — JavaScript / Node.js
- `pip` — Python
- `swift` — Swift Package Manager
- `github-actions` — always keep this one
