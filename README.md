# Git Submodules Demo - Unique #1

This repo will use shared code from repo `git-submodule-share-1`

```sh
# Import submodule (must be an existing github repo)
# Note: `share` is folder the submodule will be imported into
git submodule add https://github.com/ijklim/git-submodule-share-1.git share
# Note: Once command above ran, `.gitmodules` will be created
```

Code update in submodule folder (i.e. `share`) needs to be pushed to github separately