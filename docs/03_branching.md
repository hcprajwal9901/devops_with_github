# Branching Strategy

## Branches
- **main** → Stable, production-ready branch.
- **dev** → Integration branch for testing features.
- **feature/*** → Branches for specific features or tasks.

## Commands
```bash
# Create dev branch
git checkout -b dev
git push -u origin dev

# Create a feature branch
git checkout -b feature-setup-ci
```

## Open a Pull Request (PR)
- From feature-setup-ci → dev
- Add description of changes
## Review and Merge
- Team reviews the PR
- Merge into dev after approval
## Release
- Once tested, create PR from dev → main

✅ All merges are done through PRs.



