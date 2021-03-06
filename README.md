# emorypi-cluster
Emory Raspberry Pi Cluster Project

## For Developers

After cloning
```
git checkout develop
```

Don't ever try to work on `master`. You can't push to it anyways. If you started working on `master` by error, rebase your working branch onto `develop`.

Every time you want to start working on some feature
```
git checkout develop
git branch new-feature
git checkout new-feature
git push -u new-feature
```
Obviously, rename `new-feature` to the issue name/# you are working on.

When you're done writing your feature
1. Rebase your branch on develop
2. Push your branch one last time
3. Initiate a pull request from `new-feature` to `develop` (*NOT* to `master`!)
4. Add at least *one* reviewer.
