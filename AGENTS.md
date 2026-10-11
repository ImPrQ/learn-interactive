# Agent Governance (`minimal` preset)

## 1. Code Quality & Architecture
- **Single Responsibility & Modularity**: Keep functions, scripts, and modules small, focused, and easy to reason about.
- **Zero Unverified Dependencies**: Do not introduce external libraries or run unverified CLI commands without confirming they exist in the project environment.
- **No Hallucinations**: Always inspect existing files, paths, and configurations before proposing or executing changes.

## 2. Git & Commit Hygiene
- Follow **Conventional Commits** for all commit messages:
  - `feat:` — New features or capabilities
  - `fix:` — Bug fixes
  - `docs:` — Documentation updates
  - `refactor:` — Code restructuring without behavior changes
  - `chore:` — Maintenance and tooling updates
- Never commit secrets, credentials, or `.env` files.
