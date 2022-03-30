<div align="center">
  <a href="https://git-scm.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/git/git-plain.svg" title="Git" alt="Git" width="64" height="64"></a>
</div>

## :book: Style Guide - Commit

| Type      | Description                                                              |
| --------- | ------------------------------------------------------------------------ |
| build:    | Affect the build system or external dependencies (npm, gulp)             |
| chore:    | Change unrelated to fix/feature/src/tests (bumping dependencies)         |
| ci:       | Change continuous integration files/scripts                              |
| docs:     | Change documentation                                                     |
| feat:     | Introduce a new feature                                                  |
| fix:      | Patch a bug                                                              |
| perf:     | Improve performance                                                      |
| refactor: | Neither fixes a bug nor adds feature                                     |
| revert:   | Revert a previous commit                                                 |
| style:    | Do not affect meaning of code (formatting, whitespace, semi-colons, etc) |
| test:     | Add/Correct tests                                                        |

Further reading: https://www.conventionalcommits.org

## Set upstream

```gitattributes
git remote add upstream https://github.com/<USER>/<REPO>.git
```

## Sync `feature` branch with `main` branch

```gitattributes
git checkout feature
git rebase main
git push --force-with-lease origin feature
```

## Reset `feature` local branch with `upstream`

```gitattributes
git checkout feature
git reset --hard upstream/main
```

## Display `feature` local branch commits not in `origin/main`

```gitattributes
git log --oneline origin/main..feature
```

## Fetch & remove any remote-tracking references that no longer exist on the remote

```gitattributes
git fetch --prune
```
