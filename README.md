## How to release

- Merge some PRs (with conventional commit titles, which is ensured by a workflow check)
- Visit the [Release version actions page](https://github.com/Timmitry/conventional-changelog/actions/workflows/release-version.yml) and click on "Run workflow" for branch `main`.
- This will create a Version-PR, which you can check and then merge
- After merging, run the action again, which will create the release
