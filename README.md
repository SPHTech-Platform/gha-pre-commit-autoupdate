# gha-pre-commit-autoupdate

This action runs pre-commit autoupdate command to update the versions in the pre-commit yaml file and makes a PR to the repo for updates

# Example usage

Insert into part of the steps workflow

```yaml
steps:
  - uses: SPHTech-Platform/gha-pre-commit-autoupdate@main
    name: Update pre-commit config automatically
    with:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
