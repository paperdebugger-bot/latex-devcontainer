```bash
# first time clone
git submodule add https://github.com/paperdebugger-bot/latex-devcontainer.git .devcontainer

# clone but find there is a submodule
git submodule update --init --recursive

# update to the latest
git pull --recurse-submodules
git submodule update --recursive --remote
```