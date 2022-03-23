<div align="center">
  <a href="https://git-scm.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/git/git-plain.svg" title="Git" alt="Git" width="64" height="64"></a>
</div>

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
