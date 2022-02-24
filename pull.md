# git pull

Similar to a [git push](./push.md) , a `git pull` will interact witha remote repostory.
Only this time it will **pull** the changes it does not have from the remote repository.

This means any commits made that are on the remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
```
git pull orgin main
```

If there is any upstream connection established, you can use `git pull` without specifyinga remote or branch.

## Resources
- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

---
[Back to Home](../README.md)