# My Agnoster ZSH Theme Fork

A fork of [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) which contains some of the DevOps features from [Senpai](https://github.com/sergibarroso/senpai-zsh) and a few personal tweaks for my use-case.

As well as all the normal Agnoster features, it also add's contexts for the following:

- Active Kubernetes Config
- AWS ~~Profile~~ Vault
- Azure Config
- Google Cloud Profile

## Installation

```
git clone git@github.com:karlbaillie/agnoster-zsh-theme.git $ZSH_CUSTOM/themes/karlbaillie
vim ~/.zshrc
```
Set `ZSH_THEME` to `"karlbaillie/agnoster"`, then `exec zsh` to have the changes effect

## Plugins

As I only come here once in a blue moon when setting up a fresh work environment, here's a list of plugins I use for my benefit:

```
git
copyfile
zsh-autosuggestions
emoji
encode64
```