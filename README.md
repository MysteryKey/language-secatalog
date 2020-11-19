# Language-SECatalog
This repository contains a simple Atom package that provides basic syntax highlighting of SpaceEngine catalog files (.sc).
For more information about SpaceEngine, see https://spaceengine.org. (Warning: proprietary software ahead)
## Installation
```sh
# You would probably want to cd into a clean directory here
git clone https://hub.fastgit.org/MysteryKey/language-secatalog.git
# If the above doesn't work just use the normal GitHub.com URL
apm link language-secatalog
```
## Updating
```sh
cd language-secatalog
# This is suggested if you aren't messing around with local changes
git config pull.rebase true
git pull
```
## Uninstalling
```sh
apm unlink language-secatalog
rm -rf language-secatalog
