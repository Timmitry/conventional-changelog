## How to release

- Merge some PRs (with conventional commit titles, which is ensured by a workflow check)
- A workflow will automatically create a version bump pr
- Merging this pr will release a version
- CI will not run on main, but in the version bump PR - this is to avoid duplicate CI runs
