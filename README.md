# howtos
Here I collect tutorials about scripting, git and github


## Sync a fork of a repository to keep it up-to-date with the upstream repository.
### configuring a remote for a fork
from: https://help.github.com/en/articles/configuring-a-remote-for-a-fork

only the first time you prepare your fork:

    git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git

### Syncing a fork
from: https://help.github.com/en/articles/syncing-a-fork

    git fetch upstream
    git checkout master
    git merge upstream/master
    git push

