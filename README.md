# Git userfull commands

## Taging
```
git tag -am "annotation goes here" tagname_goes_here # cut a tag
git tag -d tagname_goes_here                         # burn it
git tag -am "annotation goes here" tagname_goes_here # cut another tag
git push --tags                                      # push tags to remote
git push origin :refs/tags/tagname_goes_here         # delete tag from remote
```
