# Git Configuration

## Maintencae

```bash
git maintenance start
```

## Commands

```bash
# Rebase with autosquash
git rebase --autosquash [ref-to-commit]
# Fixup Commit for autosquash 
git commit --fixup=[ref-to-commit]
```

## Configuration

```bash
maintenace.auto false
maintenace.strategy incremental

# # Enable rerere (reuse recorded resolution)
rerere.enabled true
 
column.ui auto

# Sort branches by committer date
branch-sort -commiterdate

# Aliases
alias.st status
alias.co checkout
alias.ci commit
alias.br branch
alias.hist log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
## force push with lease (safely)
alias.puush push --force-with-lease
```

## Links

- [Git-SCM](https://git-scm.com/)
- [Gitbutler](https://gitbutler.com/)