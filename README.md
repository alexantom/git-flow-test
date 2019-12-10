# git-flow-test
Git Flow test

https://github.com/eadz/Git-Flow-Example
https://zellwk.com/blog/git-flow/


### Reset Git Flow

 ```
git config --remove-section "gitflow.path"
git config --remove-section "gitflow.prefix"
git config --remove-section "gitflow.branch"
```

### Git Flow

- `git flow init`
- `git flow release start 1.0.2`
- `git flow release finish '1.0.2'`
- `git push --tags`
