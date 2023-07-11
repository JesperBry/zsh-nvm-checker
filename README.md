# zsh-nvm-checker

No more need for `nvm use` or forgetting changing the node version between projects

Zsh plugin that looks for a `.nvmrc` file in the current directory and automatically change to the correct node version or installs it if not on the system.

## Usage

[antigen](https://github.com/zsh-users/antigen):

Add antigen bundle to your `~/.zshrc` (This must be below the nvm initialization).

```zsh
antigen bundle JesperBry/zsh-nvm-checker --branch=main
```
