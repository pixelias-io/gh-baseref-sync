
This [gh](https://github.com/cli/cli) extension pulls changes from the base ref associated to your PR, so you don't run into issues when comparing changes.

## Installation

```sh
gh extension install pixelias-io/gh-baseref-sync
```

## Usage

```sh
gh baseref-sync
```

## FAQ

### What if my branch isn't associated to any PR?

It will pull from your repo's default branch.

### I don't like the command, can I change it?

Yes, you can set an alias with [gh alias set](https://cli.github.com/manual/gh_alias_set). (e.g. `gh alias set sync-pr baseref-sync`)
