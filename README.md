# git-submodules-root

Simple git repo that includes sample scripts to:

1) `./init` - Initialize all submodules that are define in the file `.gitmodules`.
2) `./check` - Checks for changes in all submodules (recursive to 3 levels deep)
3) `./update` - Will try to update all submodules (skips repos with uncomitted changes)

You can add a new submodule in any subfolder like so:
```
git submodule add git@github.com:chaconinc/DbConnector.git path/to/DbConnector
```

For additional info on git submodules, please see:
 - https://git-scm.com/book/en/v2/Git-Tools-Submodules